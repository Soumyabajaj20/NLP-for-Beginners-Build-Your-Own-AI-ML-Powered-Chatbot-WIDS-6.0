# Week 1: Python from Zero 🐍

**Goal:** By the end of this week you'll be comfortable writing small Python programs that work with **text**, which is the foundation of everything we do in NLP.

**Time:** ~7–9 hours · **Prerequisites:** none!

| Notebook | Open |
|----------|------|
| 📘 Guided learning notebook | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IJExaKvupSQUmj0T1GsVwPxkF9w2KNLW?usp=sharing) |
| 📝 Assignment | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uct_CtJz_WnhT8BAF1pjIzuNZIoa7UDZ?usp=sharing) |

> 💡 **How to use this week:** Watch the video for the day, then run the matching section of `Week1_Learn.ipynb` and try the 🧪 exercises. Don't just watch. **Type the code yourself.**

---

## Day 1: Setup & the Big Picture (≈1 hr)

**Why are we here?** See what we're building towards:
- 🎥 [Large Language Models explained briefly, by 3Blue1Brown (8 min)](https://www.youtube.com/watch?v=LPZh9BOjkQs): the best short explanation of how ChatGPT works. Don't worry if you don't get everything; by Week 4 you will.

**Get set up with Google Colab:**
- 🎥 [Colab 101: Your Ultimate Beginner's Guide](https://www.youtube.com/watch?v=Ii6gs9zADEA)
- ✅ Open `Week1_Learn.ipynb` in Colab, save a copy to Drive, and run **Section 0**.

---

## Day 2: Python Basics, Part 1 (≈1.5 hrs)
*Variables, data types, print, input, if/else*

- 🎥 [Python Tutorial for Beginners: Learn Python in 1 Hour, by Programming with Mosh](https://www.youtube.com/watch?v=kqtD5dpn9C8). Watch the **first half** today.
- 📖 Reference: [W3Schools: Variables](https://www.w3schools.com/python/python_variables.asp) · [Data Types](https://www.w3schools.com/python/python_datatypes.asp) · [If...Else](https://www.w3schools.com/python/python_conditions.asp)
- ✅ Notebook: **Sections 1–2**

---

## Day 3: Python Basics, Part 2 + Strings (≈1.5 hrs)
*Loops, and strings, the most important data type for NLP!*

- 🎥 Finish the [Mosh 1-hour video](https://www.youtube.com/watch?v=kqtD5dpn9C8) (second half: loops, lists).
- 📖 Strings are *everything* in NLP. Read carefully:
  - [W3Schools: Strings](https://www.w3schools.com/python/python_strings.asp)
  - [W3Schools: String Methods](https://www.w3schools.com/python/python_strings_methods.asp) (focus on `lower()`, `split()`, `replace()`, `strip()`, `join()`)
  - [W3Schools: For Loops](https://www.w3schools.com/python/python_for_loops.asp)
- ✅ Notebook: **Sections 3–4**

---

## Day 4: Lists & Dictionaries (≈1.5 hrs)
*How we store words and count them*

- 🎥 [Python Tutorial for Beginners 4: Lists, Tuples, and Sets, by Corey Schafer](https://www.youtube.com/watch?v=W8KRzm-HUcc)
- 📖 [W3Schools: Dictionaries](https://www.w3schools.com/python/python_dictionaries.asp). A dictionary is how we'll count how often each word appears in a text.
- ✅ Notebook: **Sections 5–6**

---

## Day 5: Functions (≈1 hr)
*Writing reusable code*

- 📖 [W3Schools: Functions](https://www.w3schools.com/python/python_functions.asp)
- 🎥 Optional, if you prefer video: the [W3Schools Python video series](https://www.w3schools.com/python/python_videos.asp), one short video per topic.
- ✅ Notebook: **Sections 7–8** (you'll build a mini text analyser!)

---

## Day 6: NumPy & pandas Intro (≈1.5 hrs)
*Working with tables of data, because real NLP datasets come as CSV files*

- 🎥 [NumPy tutorial for beginners](https://www.youtube.com/watch?v=QUT1VHiLmmI) (watch the first ~30 min; we only need the basics)
- 🎥 [Complete Python Pandas Data Science Tutorial](https://www.youtube.com/watch?v=vmEHCJofslg) (watch up to *filtering data*)
- ✅ Notebook: **Section 9**

---

## Day 7: Assignment 📝

Complete `Week1_Assignment.ipynb`. It has built-in ✅ checks so you'll know if your answer is right.

**You'll build:**
1. A text cleaner
2. A word counter & word-frequency finder
3. A stopword remover
4. A **rule-based sentiment analyser** (your first NLP model!)
5. A pandas analysis of movie reviews
6. 🌟 Bonus: a tiny rule-based chatbot

**Submission:** push the completed notebook to your repo under `Week_1_Python_Basics/` and submit the link in the Google Form shared in the group.

---

## 📚 Extra Resources (optional, for those who want more)

- [Kaggle Learn: Python](https://www.kaggle.com/learn/python): free, interactive, with exercises in the browser
- [CS50's Introduction to Programming with Python (Harvard)](https://cs50.harvard.edu/python/): the gold standard if you want depth
- [Official Python Tutorial](https://docs.python.org/3/tutorial/)
- [W3Schools Python Exercises](https://www.w3schools.com/python/python_exercises.asp): quick practice questions

---

## ❓ Stuck?
1. Read the error message. The **last line** usually tells you what's wrong.
2. Google the error (or ask an AI to *explain* it, not solve it).
3. Still stuck after 30 min? Ask in the WhatsApp group. Someone else probably has the same doubt.

**Next week:** we teach computers to read, turning text into numbers and building a spam detector! 📨
