REQUIREMENTS:
1. Use of a palindrome(A word is a palindrome if only if it can be read from left to right and vice-versa 
   for example: gag, pop, nun, radar....and so on.)
2. Use of loops.


Code in JavaScript:

function palindrome(enterdWord) {
  const reversedWord = '';
  for (const i = enteredWord.length - 1; i >= 0; i--) {
    reversedWord += enterdWord[i];
  }
  if(enteredWord === reversedWord;){
     return true;}else{
                 return false;
}

// Example
console.log(palindrome("level"))

//The result will be true

EXPLANATION OF CODE:

1. Inside the function, we initialize a variable called `reversedWord` as an empty string. 
   This variable will store the reversed version of the word.
2. We use a for loop to iterate through the characters of the word in reverse order. We start from 
   the last character (at index "enteredWord.length - 1") and go backwards to the first character (at index 0).
3. Within the loop, we concatenate each character to the "reversedWord" variable. By doing this, we build the 
   reversed version of the word.
4. After the loop finishes, we compare the original word (enteredWord) with the reversed word (reversedWord) using the === equality operator. 
   If they are exactly the same, it means the word is a palindrome, so we return true. Otherwise, we return false.


