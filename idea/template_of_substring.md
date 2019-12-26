# [template of solving substring problems](https://leetcode.com/problems/minimum-window-substring/discuss/26808/here-is-a-10-line-template-that-can-solve-most-substring-problems)
```cpp
int findSubstring(string s){
        vector<int> map(128,0);
        int counter; // check whether the substring is valid
        int begin=0, end=0; //two pointers, one point to tail and one  head
        int d; //the length of substring
        for() { /* initialize the hash map here */ }
        while(end<s.size()){
            if(map[s[end++]]-- ?){  /* modify counter here */ }
            while(/* counter condition */){   
                 /* update d here if finding minimum*/
                //increase begin to make it invalid/valid again
                if(map[s[begin++]]++ ?){ /*modify counter here*/ }
            } 
            /* update d here if finding maximum*/
        }
        return d;
  }
```

# [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)
> pure template
```cpp
string minWindow(string s, string t) {
    vector<int> map(128,0);
    for(auto c: t) map[c]++;
    int counter=t.size(), begin=0, end=0, d=INT_MAX, head=0;
    while(end<s.size()){
        if(map[s[end++]]-->0) counter--; //in t
        while(counter==0){ //valid
            if(end-begin<d)  d=end-(head=begin);
            if(map[s[begin++]]++==0) counter++;  //make it invalid
        }  
    }
    return d==INT_MAX? "":s.substr(head, d);
}
```
> clear code:

```cpp
string minWindow(string s, string t) {
	unordered_map<char, int> m;
	// Statistic for count of char in t
	for (auto c : t) m[c]++;
	// counter represents the number of chars of t to be found in s.
	size_t start = 0, end = 0, counter = t.size(), minStart = 0, minLen = INT_MAX;
	size_t size = s.size();
	
	// Move end to find a valid window.
	while (end < size) {
		// If char in s exists in t, decrease counter
		if (m[s[end]] > 0)
			counter--;
		// Decrease m[s[end]]. If char does not exist in t, m[s[end]] will be negative.
		m[s[end]]--;
		end++;
		// When we found a valid window, move start to find smaller window.
		while (counter == 0) {
			if (end - start < minLen) {
				minStart = start;
				minLen = end - start;
			}
			m[s[start]]++;
			// When char exists in t, increase counter.
			if (m[s[start]] > 0)
				counter++;
			start++;
		}
	}
	if (minLen != INT_MAX)
		return s.substr(minStart, minLen);
	return "";
}
```

# Longest Substring with At Most Two Distinct Characters
```cpp
int lengthOfLongestSubstringTwoDistinct(string s) {
    vector<int> map(128, 0);
    int counter=0, begin=0, end=0, d=0; 
    while(end<s.size()){
        if(map[s[end++]]++==0) counter++;
        while(counter>2) if(map[s[begin++]]--==1) counter--;
        d=max(d, end-begin);
    }
    return d;
}
```

# [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)

> One thing needs to be mentioned is that when asked to find maximum substring, we should update maximum after the inner while loop to guarantee that the substring is valid. On the other hand, when asked to find minimum substring, we should update minimum inside the inner while loop.

```cpp
int lengthOfLongestSubstring(string s) {
    vector<int> map(128,0);
    int counter=0, begin=0, end=0, d=0; 
    while(end<s.size()){
        if(map[s[end++]]++>0) counter++; 
        while(counter>0) if(map[s[begin++]]-->1) counter--;
        d=max(d, end-begin); //while valid, update d
    }
    return d;
}
```
