# PA-1-
Introduction to Python Programming

1. # ALPHABET SOUP PROBLEM
   - **Purpose:** This function takes a word or sentence, removes spaces, and checks if it only contains letters. It then sorts all the characters alphabetically.
   - **Details:**
     - Removes spaces and converts input to lowercase.
     - Ensures all characters are alphabetic.
     - Sorts the characters alphabetically and returns the result.
   - **Example:**
   ```python
     alpha_soup("Hello World")
     # Output: dehllloorw
     ```
    

2. # EMOTICON PROBLEM
   - **Purpose:** This function replaces specific words in a sentence with their corresponding emoticons.
   - **Details:**
     - Uses a dictionary to map keywords to emoticons.
     - Processes input text word by word.
     - Replaces words like "smile", "grin", "sad", and "mad" with symbols.
   - **Supported conversions:**
     - `"smile"` → `:)`
     - `"grin"` → `:D`
     - `"sad"` → `:((`
     - `"mad"` → `>:(`
   - **Example:**
     ```python
     emoticon("I smile and grin")
     # Output: i :) and :D
     ```

3. # UNPACKING LIST PROBLEM
   - **Purpose:** This function takes a list of numbers and separates them into first, middle, and last elements.
   - **Details:**
     - Identifies and prints the first element.
     - Extracts and prints the middle elements.
     - Identifies and prints the last element.
   - **Example:**
     ```python
     unpack([1, 2, 3, 4, 5])
     # Output:
     # First: 1
     # Middle: [2, 3, 4]
     # Last: 5
     ```
