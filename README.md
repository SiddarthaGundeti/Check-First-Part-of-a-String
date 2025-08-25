# Check-First-Part-of-a-String

Question Explanation

Input: rainbow
rain

Output: True

You're tasked with writing a program that reads two strings, S1 and S2, and determines if S2 is the first part of S1. The condition for S2 to be considered the first part is that the number of characters in S2 must be equal to the number of characters at the beginning of S1.

Approach

Read the first string input given as S1.

Read the second string input given a S2.

Get the length of S2.

Now, you need to create a new string from S1, which starts from the beginning of S1 (index 0) and includes the first N characters (where N is the length of S2). This means you are taking a portion of S1 that is exactly as long as S2.

If they are equal, print True; otherwise, print False.

This approach ensures that we're comparing the first part of S1 with S2 and returning the appropriate boolean result.
