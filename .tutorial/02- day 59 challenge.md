# 👉 Day 59 Challenge

You're going to write a program that checks a string to see if it is a palindrome.

Yes. We *know* that Python has the built in function `string.reverse()` that you could use.  

Zero points for that today, we want you to think hard and utilize your skills in:
- recursion
- string slicing
- looping

Your program should:

1. Prompt the user to input a word.
2. Analyze the word to see if it is a palindrome.
3. Output a relevant 'yes/no message. 


Example:

```
🌟Palindrome Checker🌟

Input a word > Racecar

Racecar is a palindrome. Yay!
```

<details> <summary> 💡 Hints </summary>

This is a tough one, so I've given you some hints about the algorithmic thinking needed for a problem like this:
  
- Don't forget to standardize the case on input.
- Think about which characters in a word are compared first. Check if they are the same.
- If they've been compared and are the same, remove them and repeat the process with the shorter string.
- Keep going until you're down to a string of length 1 or 0 (depending on whether the original word had an odd/even number of characters. If you get to this point, then you've got a palindrome. 

</details>