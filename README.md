# 📩 Email Spam Detection (Beginner Level)

A simple email spam classifier using basic Python logic. This project simulates how spam messages can be identified using a list of common spam keywords.

## 🛠 Technologies Used
- Python (Basic)

## 🎯 Objective
To detect whether a given email message is spam or not based on the presence of known spam keywords.

## 💡 How It Works
The script checks if any words from a predefined list of spam keywords exist in the email content. If the number of spam words exceeds a threshold, it classifies the message as "Spam."
# List of spam keywords
spam_keywords = ["win", "free", "offer", "winner", "money", "prize", "lottery"]

# Sample emails
emails = [
    "You have won a free prize!",
    "Meeting is scheduled at 3 PM",
    "Congratulations, you are a lottery winner!",
    "Please submit your assignment",
]

# Check each email
for email in emails:
    email_lower = email.lower()  # convert to lowercase
    spam_count = sum(word in email_lower for word in spam_keywords)

    if spam_count > 1:
        print(f"Spam Detected: '{email}'")
    else:
        print(f"Not Spam: '{email}'")

