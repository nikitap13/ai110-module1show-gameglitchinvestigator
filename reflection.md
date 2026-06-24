# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

  1) The game was not correctly identifying my guesses are lower than 0 or higher than 100. With every new number I guessed, the game was still saying go higher or go lower without actually comparing it to the secret number.
  2) The "submit guess" button did not work. The only way I had any insight as to whether my guess was high or low was through the "hint" button which was not even working right. 

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
| 50    | Guess lower       | Nothing         | none
| 10    | Guess lower       | Nothing         | none
| 15    | Guess higher      | You've won      | none

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

I used AI as help right from the beginning. I needed ChatGPT's help with setting up git. I did not understand that I still needed to install line command tools, so when git wasn't connecting to terminal I screenshotted my terminal and put it in chatGPT. Then it was able to tell me I need to let it install line command tools. I also was able to ask AI about certain issues that I had with the game and where that could possibly correlate in terms of code. I wanted to get a sense of what type of bug I should be looking for in the code, 
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

To decide whether a bug was really fixed, I had to just play the game again. AI was able to help me understand tests. It was able to show me what I was doing wrong, or at least how I could see what I was doing wrong, 
---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.

  This has made me really think about how AI is really useful and really not useful. Asking it good guiding questions and getting it to help me is a good way to use AI. However, asking it to generate code on all its own is probably not a good idea because there are so many random bugs it comes up with and it is hard to fix them or even find them at times. I will try to make sure when I use AI for technical things I am super smart about how I question and guide AI towards what I need. 
