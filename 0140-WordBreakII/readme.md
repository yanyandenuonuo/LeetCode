# Word Break II

## Description

&emsp;&emsp;Given a **non-empty** string s and a dictionary wordDict containing a list of **non-empty** words, add 
spaces in s to construct a sentence where each word is a valid dictionary word. Return all such possible sentences.

## Note

- The same word in the dictionary may be reused multiple times in the segmentation.
- You may assume the dictionary does not contain duplicate words.

## Example

### eg1

```
    Input:
    s = "catsanddog"
    wordDict = ["cat", "cats", "and", "sand", "dog"]
    
    Output:
    [
        "cats and dog",
        "cat sand dog"
    ]
```

### eg2

```
    Input:
    s = "pineapplepenapple"
    wordDict = ["apple", "pen", "applepen", "pine", "pineapple"]
    
    Output:
    [
        "pine apple pen apple",
        "pineapple pen apple",
        "pine applepen apple"
    ]
    Explanation: Note that you are allowed to reuse a dictionary word.
```

### eg3

```
    Input:
    s = "catsandog"
    wordDict = ["cats", "dog", "sand", "and", "cat"]
    
    Output:
    []
```

## Difficulty

&emsp;&emsp;Hard

## Other

&emsp;&emsp;todo，添加解题思路。