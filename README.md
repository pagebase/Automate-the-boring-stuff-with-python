# Table of content

0. [Book content](#book-content)
1. [This book audience](#This-book-audience)
2. [AI Won’t Replace Programmers](https://github.com/pagebase/Automate-the-boring-stuff-with-python/tree/patch-1?tab=readme-ov-file#ai-wont-replace-programmers)
3. [How to find Help?](#how-to-find-help)

---
# Book content

Chapter 1 - Python Basics

Chapter 2 - if-else and Flow Control

Chapter 3 - Loops

Chapter 4 - Functions

Chapter 5 - Debugging

Chapter 6 - Lists

Chapter 7 - Dictionaries and Structuring Data

Chapter 8 - Strings and Text Editing

Chapter 9 - Text Pattern Matching with Regular Expressions

Chapter 10 - Reading and Writing Files

Chapter 11 - Organizing Files

Chapter 12 - Designing and Deploying Command Line Programs

Chapter 13 - Web Scraping

Chapter 14 - Excel Spreadsheets

Chapter 15 - Google Sheets

Chapter 16 - SQLite Databases

Chapter 17 - PDF and Word Documents

Chapter 18 - CSV, JSON, and XML Files

Chapter 19 - Keeping Time, Scheduling Tasks, and Launching Programs

Chapter 20 - Sending Email, Texts, and Push Notifications

Chapter 21 - Making Graphs and Manipulating Images

Chapter 22 - Recognizing Text in Images

Chapter 23 - Controlling the Keyboard and Mouse

Chapter 24 - Text-to-Speech and Speech Recognition Engines

Appendix A - Installing Third-Party Packages

Appendix B - Answers to the Practice Questions

---
# This book audience

Software is at the core of so many of the tools we use today: nearly everyone uses social networks to communicate, virtually all people have internet-connected phones in their purse or pocket, and most office jobs involve interacting with a computer to get work done. As a result, the demand for people who can code has skyrocketed. Countless books, online tutorials, and developer boot camps promise to turn ambitious beginners into software engineers with six-figure salaries.

This book is not for those people. It’s for everyone else.

On its own, this book won’t turn you into a professional software developer any more than a few guitar lessons will turn you into a rock star. But if you’re an office worker, administrator, academic, or anyone else who uses a computer for work or fun, you will learn the basics of programming so that you can automate simple tasks such as these:

- Moving and renaming thousands of files and sorting them into folders
- Filling out online forms—no typing required
- Downloading files or copying text from a website whenever it updates
- Having your computer text custom notifications to your phone
- Updating or formatting Excel spreadsheets
- Checking your email and sending out prewritten responses
- Creating databases and querying them for information
- Extracting text from images and audio files

These tasks are simple but time-consuming for humans, and they’re often so trivial(Important) or specific that there’s no ready-made software to perform them. Armed with a little bit of programming knowledge, however, you can have your computer do these tasks for you.

> Program 1

```python
with open("Sample.text","r") as f:
    user_password=input("Enter your password: ")
    database_password=f.read()
    if (user_password==database_password):
        print("Access granted")
    else:
        print("Account blocked for 24 hours")
```

## AI Won’t Replace Programmers

In the 1990s, nanotechnology promised to change everything. New manufacturing processes and scientific innovation would revolutionize society, the thinking went. Carbon nanotubes, buckyballs, and diamonds the price of pencil lead, all assembled one atom at a time out of plentiful carbon by germ-size nanobots, would pave the way for materials 10 times stronger than steel at a fraction of the weight and cost. This would lead to space elevators, medical miracles, and home appliances that could create anything, just like the replicators on Star Trek! It would mean an end to economic scarcity, world hunger, and war. It would bring on a new age of enlightenment—as long as the nanobots didn’t turn on their human creators in a tiny robot uprising. And the technology was only 10 years away!

Of course, the hype never happened. Real innovations certainly occurred at the nanoscale (the smartphone in your pocket uses a number of them). But the Star Trek replicators and other grandiose promises didn’t arrive, and the excitement over nanotechnology deflated to more realistic proportions.

Let’s talk about AI.

Personal computers changed everything. The internet changed everything. Social media changed everything. Smartphones changed everything. Cryptocurrency did not change everything, but it did reveal which of your cousins and co-workers were susceptible to get-rich-quick scams. Today, AI is the latest marvel to emerge from the tech industry. People use the term AI to mean everything from chess-playing computers to chatbots, so-called expert systems, and machine learning. In this book, I’ll use the term large language model (LLM), which is the conceptual category behind OpenAI’s ChatGPT, Google’s Gemini, Facebook’s LLaMA, and other generative text systems.

- LLMs have caused many breathless claims and questions. Is AI going to take all of our jobs? Is it still worth learning to code? Are the AIs alive, and can I survive the AI-robot uprising?

- LLM technology is exciting, but to make it useful, we need to set realistic expectations so that we can avoid falling prey to sensationalist journalism and questionable “investment opportunities.” I hope I can deflate the hype and give you a more realistic view of how LLMs can help you learn to code. Let’s get some of these misconceptions out of the way right now:

- LLMs are not conscious or sentient.
- LLMs will not replace human software engineers.
- LLMs do not alleviate the need to learn programming.
- LLMs will not replace most human jobs (though this won’t prevent your manager from thinking they can and laying you off anyway).
- LLMs are far from perfect, and are even often wrong.

Those who insist on these misconceptions get their information from science fiction movies and internet videos, not from experience with actual LLMs. I highly recommend Simon Willison, Python Software Foundation board member and co-creator of the Django Web Framework, for his writing about AI at https://simonwillison.net/about. You can watch his sober and illuminating PyCon 2024 keynote speech on LLMs at https://autbor.com/pycon2024keynote.

How could LLMs help you as a programmer? What is obvious at this early stage is that learning to communicate with LLMs (so-called prompt engineering) is a skill, just like learning to effectively use a search engine is a skill. LLMs are not people, and you need to learn how to phrase your questions to get relevant and reliable answers. When LLMs confidently make up incorrect answers, we say that they are hallucinating. But this is just another way of anthropomorphizing an algorithm. LLMs don’t think; they generate text. That is to say, LLMs are always hallucinating, even when their answers happen to be correct.

LLMs make large, obvious mistakes and simple, subtle mistakes, however. If you use them as a learning aid, you must vigilantly check everything the LLM tells you, big or small. It’s entirely valid to choose to forgo learning with LLMs altogether. At this point, the effectiveness of using LLMs in education is unproven. We don’t know for sure in what situations LLMs are useful as learning tools, or even if their benefits outweigh their costs.

It’s no wonder that so many buy into the hype of LLMs. We carry devices in our pockets that scientists of the last century would consider supercomputers. They connect us to a global network of information (and misinformation). They can identify their position anywhere on Earth by listening to satellites in outer space. Software can already do seemingly magical things, but software isn’t magic. And by learning to program, you’ll get a far more grounded idea of what computers are capable of versus what is just hype.

# How to find Help?

If you can’t find the answer by searching online, try asking people in a web forum such as Stack Overflow (https://stackoverflow.com) or the “learn programming” subreddit at https://reddit.com/r/learnprogramming. But keep in mind there are smart ways to ask programming questions that help others help you. To begin with, be sure to read the Frequently Asked Questions sections at these websites about the proper way to post questions.

When asking programming questions, remember to do the following:

- Explain what you are trying to do, not just what you did. This lets your helper know if you are on the wrong track.
- Specify the point at which the error happens. Does it occur at the very start of the program or only after you do a certain action?
- Copy and paste the entire error message and your code to https://pastebin.com or https://gist.github.com. These websites make it easy to share large amounts of code with people online, without losing any text formatting. You can then put the URL of the posted code in your email or forum post. For example, here are the locations of some pieces of code I’ve posted: https://pastebin.com/2k3LqDsd and https://gist.github.com/asweigart/6912168.
- Explain what you’ve already tried to do to solve your problem. This tells people you’ve already put in some work to figure things out on your own.
- List the version of Python you’re using. Also, say which operating system and version you’re running.
- If the error came up after you made a change to your code, explain exactly what you changed.
- Say whether you’re able to reproduce the error every time you run the program or whether it happens only after you perform certain actions. In the latter case, also explain what those actions are.

Always follow good online etiquette as well. For example, don’t post your questions in all caps or make unreasonable demands of the people trying to help you.

You can find more information on how to ask for programming help in the blog post at https://autbor.com/help. I love helping people discover Python. I write programming tutorials on my blog at https://inventwithpython.com/blog, and you can contact me with questions at al@inventwithpython.com, although you may get a faster response by posting your questions to https://reddit.com/r/inventwithpython.

---
# Copying and pasting clipboard data

`pypeclip` module used to copy data into clipboard and paste clipboard data out of clipboard. It has 2 methods:

- `pyperclip.copy("Data to copy in clipboard")`: This method copy data into clipboard.

- `pyperclip.paste()`: This method paste clipboard data out of clipboard.

#### Example:
```python
import pyperclip

# Copy text to clipboard
pyperclip.copy("Hello, world!")

# Paste text from clipboard
text = pyperclip.paste()
print(text)
```