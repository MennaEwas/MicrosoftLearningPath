Literals and special characters
Steps in the Azure Cloud Shell sandbox:
1. Open the NASA-software-API.txt file in Cloud Shell by using code <filename>.
2. Next, open the search box by using the key combinations Cmd+F in macOS or Ctrl+F in Windows and Linux.
3. Make sure that the regex option is switched on.
4. Enter the words Open Source in the search box. Cloud Shell matches all of the string instances.

  
Wildcards:
  The . character is a special character type called a wildcard. It can be used to represent any character, such as letters,
  numbers, white spaces, newlines, punctuation, and symbols.
  A common pattern used in regex is .*, which allows you to match any character zero or more times.
  When you match sequences that appear at a specific part of a line of characters or a word, it's called anchoring. You use the caret (^) symbol to indicate the search pattern should consider a character sequence a match only if it appears at the start of a line. The $ symbol is used to indicate that the search pattern should consider a match only if it appears at the end of a line.
 
 Check: https://docs.microsoft.com/en-us/visualstudio/ide/using-regular-expressions-in-visual-studio?view=vs-2019
  
