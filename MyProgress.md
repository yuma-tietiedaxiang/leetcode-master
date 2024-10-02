# Array
1. 704 binary search
2. 27 Remove Element (fast pointer & slow pointer)
3. 977 Squares of a Sorted Array (two pointers)
4. 209 Minimum Size Subarray Sum (mid; moving window)
5. 59 Spiral Matrix II  (loop logic)
6. 58 Length of last word
                           class Solution {
                                public int lengthOfLastWord(String s) {
                                    String[] words = s.split("\\s+");
                                    return words[words.length - 1].length();
                                }
                            }

# Linked list
7. 203 Remove linked list element
