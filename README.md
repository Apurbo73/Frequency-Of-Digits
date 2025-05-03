# Frequency Of Digits In A Number
### What is frequency of a number?
**Frequency of digits in a number** refers to how many times each digit (from 0 to 9) appears in that number. For example, in the number `112345511`, the digit `1` appears **4 times**, `2` appears **1 time**, `3` appears **1 time**, `4` appears **1 time**, and `5` appears **2 times**. Digits that are not present (like `0`, `6`, `7`, `8`, and `9` in this case) have a frequency of **0**. This concept is commonly used in programming to analyze numbers or detect patterns.


 
This C++ program counts the frequency of each digit in a given number. It starts by declaring an array of size 10 to store the count of each digit (0–9), initializing all values to zero. After taking the input number from the user, it handles the special case when the number is 0 by manually incrementing the count for digit 0. Then, it enters a loop that extracts each digit from the number using the modulus operator (`% 10`), increments the corresponding count in the array, and removes the last digit using integer division by 10. Finally, it prints out only the digits that appeared at least once in the input along with their frequencies.

