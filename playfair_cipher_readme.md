This Python code implements a **Playfair Cipher** encryption tool using the `tkinter` library for a graphical user interface (GUI). The Playfair Cipher is a digraph substitution cipher that encrypts pairs of letters based on a 5x5 matrix. 

### Key Features:
1. **Keyword Input**:
   - Users enter a keyword, which generates the Playfair matrix by removing duplicate letters, excluding 'J' (replaced by 'I'), and filling in the remaining letters of the alphabet.

2. **Word Encryption**:
   - Users input a plaintext word, which is formatted into pairs of letters (inserting 'X' for duplicate letters or odd-length inputs).
   - Each pair is encrypted based on the rules of the Playfair Cipher:
     - **Same Row**: Letters are replaced by their immediate right neighbors.
     - **Same Column**: Letters are replaced by the ones below them.
     - **Rectangle Rule**: Letters swap their columns to form opposite rectangle corners.

3. **Dynamic GUI**:
   - Displays the Playfair matrix.
   - Provides step-by-step encryption rules and the transformation process for each letter pair.

### Purpose:
The code is a learning tool that visualizes how the Playfair Cipher works, making it easier for users to understand the encryption process interactively.
