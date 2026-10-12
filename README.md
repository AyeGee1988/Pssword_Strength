**Password Strength Analyzer**

This is a simple yet effective tool that lets a user know whether a password is weak, moderate, or strong. It can also let a user know that the chosen password is common and that they have to create a new one. 

**Files in This Folder**

Python_Strength - The main Python script that runs the password analyzer 
common.txt - A list of commonly used/known weak passwords (200 entries) that was found via Google.

**How to Run**

1.	Navigate to this link:
https://github.com/AyeGee1988/Pssword_Strength
2.	Run the script:  
3.	Enter a password when prompted

**How It Works**

Step 1 — Common Password Check
When creating a password, the tool scans the file “common.txt” to see whether the password matches any text in that file. Then it will let the user know it was detected and prompt them to try creating another one. 
Step 2 — Minimum Length Check
Your password must be at least 8 characters long. Shorter passwords are rejected immediately, and the user will be notified. 
Step 3 — Character Variety Check

Your password must contain at least 3 of the 4 characters below:
Capitalized letters 
Non-capitalized letters 
Numbers
Special characters like the following: “!”, “@”, “etc.”

Step 4 — Scoring
The script calculates a point system that scores from 0 to 7 based on the following:

8+ characters  = | +1 |
12+ characters  = | +1 |
16+ characters = | +1 |
20+ characters = | +1 |
Uses 2+ character types | +1 |
Uses 3+ character types | +1 |
Uses all 4 character types | +1 |

Step 5 — Strength Rating
A score rating populates when a password is scanned and notifies the user. 
| 0 – 3 | ❌ Weak |
| 4 | ⚠️ Moderate |
| 5 or higher | ✅ Strong |

**Tips for a Strong Password**

Ensure you use 16+ characters for the best score
Attempt to mix uppercase, lowercase, numbers, and symbols
Do your best to avoid common words, names, or number sequences
Lastly, never reuse passwords from the “common.txt” list

**Requirements**

- Python 3.x (no additional packages required — uses only the standard library)
- `common.txt` must be in the same folder as `Python_Strength`

*Created by Adrian Gonzalez


