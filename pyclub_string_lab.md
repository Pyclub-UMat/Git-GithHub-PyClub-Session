# PYCLUB PRACTICAL: STRING METHODS

---

## Backend Developer Task

You are a **backend developer** building a registration system for a website. Users often type their usernames and passwords with extra spaces, uppercase letters, or weak passwords. It’s your job to clean and check their inputs.

**Given variables:**
```python
username = "  JohnDoe12  "
password = " MyPass123 "
```

**Tasks:**
- Clean the username by removing spaces at the start and end and converting all letters to lowercase. Print the cleaned username.
- Check if the username has **at least 5 characters** using `len()`.
- Make sure the username contains **only letters and numbers** using `.isalnum()`.
- Check if the password has **at least 8 characters** using `len()`.
- Check if the password contains **at least one number** using `.isdigit()` in a loop over characters.
- Print a final message showing whether the **username and password are valid**.

---

## Data Analyst Task

You are a **data analyst** receiving text from online surveys. The sentences are messy, with extra spaces, uppercase letters, and punctuation. You need to clean them so you can analyze the text.

**Given variable:**
```python
sentence = "  Python is AMAZING!! Data science is POWERFUL.  "
```

**Tasks:**
- Remove spaces at the start and end and convert it to lowercase.
- Remove punctuation marks `. , ! ?` using `.replace()`.
- Split the sentence into words using `.split()` and count the total number of words using `len()`.
- Find the **longest word** in the sentence.
- Print a small report showing:
  - Cleaned sentence
  - Total number of words
  - Longest word

---

## Cybersecurity Intern Task

You are a **cybersecurity intern** helping users create strong passwords. Weak passwords are a major security risk, so you must check them carefully.

**Given variable:**
```python
password = " StrongPass1 "
```

**Tasks:**
- Remove spaces at the start and end and convert letters to the appropriate case if needed.
- Check if the password has **at least 8 characters** using `len()`.
- Check if it contains **at least one number** using `.isdigit()` in a loop.
- Check if it contains **at least one uppercase letter** using `.isupper()` in a loop.
- Print a message showing whether the password is **strong or weak**, and explain why.

---

## Social Media Manager Task

You are a **social media manager**. You just received a messy post that contains extra spaces, punctuation, and possibly banned words. Your job is to clean it and summarize it before posting.

**Given variables:**
```python
post = "  OMG!!! This is AMAZING!! But some badword is here.  "
banned_word = "badword"
```

**Tasks:**
- Remove spaces at the start and end and convert the post to lowercase.
- Remove punctuation marks `. , ! ? : ;` using `.replace()`.
- Split the text into words using `.split()` and count the total number of words with `len()`.
- Find the **first and last words** of the post.
- Replace the banned word with `"***"` using `.replace()`.
- Print a summary including:
  - Cleaned post
  - Total words
  - First and last words
  - Post with banned words censored
