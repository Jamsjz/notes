---
title: Hash Tables
date: 2024-08-03
tags:
  - Permanent
refs:
  - "[[Data Structures]]"
netlinks: 
bookref:
  - "[[Grokking Algorithms|Grokking Algorithms]]"
---
# Hash tables

## Hash Functions

```ad-important
title: What are they?
Hash function maps keys to indices
![[Pasted image 20240803162923.png]]
```

### Working

```ad-note
title:Working

We work with indices of array.

-  The hash function consistently maps a **key** to the same index which has a **value**. 
-  The hash function maps different **keys**  to different indices.
-  The hash function knows how big your array is and only returns valid indices.
```

## Hash Table from Hash Functions

```ad-important
title: Just connect hash functions to an array!
Take an array.
1. First you give a key to hash function. An index is generated within the valid range of the array.
2. The value you want to associate with the key is kept in the index.
```

## Use Cases

```ad-example
title: Caching and Memorization of visited websites
```python
cache = {}
def get_page(url)
	if cache.get(url):
		return cache[url] # Returns cached data
	else:
		data = get_data_from_server(url) # saves data in cache
		cache[url] = data
		return data # then returns data
```

```ad-example
title: Hash for preventing duplicates by doing lookups
```python
votes = {}
def add_vote(voters_name, candidate):
	if votes.get(voters_name):
		votes[voters_name]=candidate
		return "Voters vote has been registerd"
	else:
		return "Voter has already voted."
```

## Collision

If hash function gives same index for two different keys, then the values for those keys will be added to same location in a linked list.
![[Pasted image 20240803160909.png]]

```ad-important
If those linked lists get long, it slows down your hash table a lot. But they won’t get long if you use a good hash function! 
```


## Load Factor

```ad-info
title: Calculating load factor
$$\frac{\text{number of items in the table}}{\text{total number of slots }}$$

0.7 is the max you want.
It's time to resize your hash table if it reaches 0.7 LF.
```

## Summary
```ad-summary
title:About Hash Tables
1. Hash funcitons maps keys to indices
[[#Hash Functions]]

2. Created by assigning a hash function to an array.
[[#Hash Table from Hash Functions]] 

3. Used in caching, memorization, search(lookups) and preventing duplications.
[[#Use Cases|Hash Tables]]

4. Different keys assigned by hash function to same index causes collision forming linked list.

![[Pasted image 20240803160909.png]]

5. Once load factor reaches 0.7, hash table should be resize.
```

---

## References
