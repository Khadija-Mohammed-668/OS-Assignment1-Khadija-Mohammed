# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Khadija Abdelhai Mohammed] |
| **Student ID** | [446052668] |
| **University Email** | [446052668]@std.psau.edu.sa |
| **GitHub Username** | [Khadija-Mohammed-668] |
| **Repository Link** | [https://github.com/Khadija-Mohammed-668/OS-Assignment1-Khadija-Mohammed] |
 
---

## 🎥 Video Link

**Video Link**: [(https://youtu.be/Fl9oFO8-ilc?si=Fi8JfqSqh5_-1sTK)]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 7,2026, 3:00 PM]
**What I did**:Forked  the repository into VS code and changed line 150 into my student ID

**Details**:
-Created my GitHub account with uni  email
-Forked the starting ripository and renamed it 
-Changed line 150 to my student Id


**Challenges**:VS code did not  recognize JDK nor git and couldn't sync to my GitHub account

**Solution**:Reinstalled JDK and git, changed .java file into src folder

**Time spent**:1 hour

---

### Entry 2 - [October 8, 2026, 4:30 PM]
**What I did**:Reinstalled JDK and git, installed other extentions,commited my student ID

**Details**:
-Reinstalled JDK and git to fix the recognition problem 
-Installed needed extentions 
-Commited the changes I made yesterday

**Challenges**:Finding the right extentions to install

**Solution**:Asking friends

**Time spent**:3 hours

---

### Entry 3 - [October 9, 2026, 11:00 AM, 10 PM]
**What I did**: Added Feature 1 and commited it ,Added Feature 2 and commited it

**Details**:
-read the requirements of the features
-searched implementation techniques to add process priority and context switch counter
-implemented code
-commited changes

**Challenges**:Searching and understanding how to implement code

**Solution**:Using AI ,asking friends

**Time spent**:4 hours

---

### Entry 4 - [October 10,2026, 8:00 AM , 4:30 PM]
**What I did**:Added Feature 3 and commited it , worked on the entrys 

**Details**:
-Added the entrys of the previous days 
-Read the requirements of Feature 3
-Searched implementation techniques to make a time tracking table 
-Commited changes 

**Challenges**: The code for the table is hard to understand and implenent

**Solution**:Used AI and Asked friends

**Time spent**: 4 hours 

---

### Entry 5 - [October 10, 2026, 6:00 PM]
**What I did**:Answered the questions at MY_WORK.md

**Details**:
Answered all the questions in the file

**Challenges**: Understandin questions

**Solution**: Reread the questions

**Time spent**:3 and 1/2 hours 

---

### Entry 6 - [October 11, 2026, 12:00 AM]
**What I did**: Added the video link to the file and commited the last changes

**Details**:
-Filmed and edited the video
-Pasted the link to the file 
-Made some final changes and commited them

**Challenges**:Editing the video took so much time

**Solution**:Asked friends for help

**Time spent**: 2 and 1/2 hours

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [18 hours]

**Most challenging part**: Implementing features in the SchedulerSimulation file

**Most interesting learning**:How I can use Java to implement Scheduling algorithms and visualize them

**What I would do differently next time**: Start working on the assignment earlier

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[This Assignment helped me visualize how  multithreadeing happens in real time, I also learned the implementation of the Runnable interface and how to create threads for each process  using Thread.start(), I also understood how Thread.join()pauses the Scheduler loop and wait for a process to finish its time quantum before moving to the next one, I saw Thread.sleep() being used to simulate real CPU burst execution, what surprised me the most was that I had to create a brand new Thread instance every time a process needed to re-enter the ready queue. ]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[I think the most challenging part of the assignment was dealing with the development environment setup on VScode, as the first time I forked the repository, the code did not run at all and debugger kept throwing a (java.util.concurrent.TimeoutExeption), and I had to keep working on  figuring out what was wrong,the code itself seemed fine so I couldn't understand the problem, other than that the output seemed to come in gibberish instead of the lines in the code.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I had to look at the whole README again and again to find what I can do about the exeption, asked my friends and search for a solution, finally I decided to ask AI and it gave me the solution of using the terminal to manually compile the program and run it, and for the output coming out in weird characters I had to change the language of my device and activate the beta setting.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is used in modern day in alot of applications and softwares, for example : a web browser uses multithreading in managing tabs,so if a website crashes others remain up and responsive, or in a music player app , multithreading keeps music running while the user interface is still responsive, and the scheduling simulation we worked on shows how an OS manages CPU time between multiple open apps.]

### Optional: What would you like to learn more about?

[I would like to practice creating threads from scratch to confirm my understanding ]

### Optional: How confident do you feel about multithreading concepts now?

[ Intermediate, I can use some more practice to fully anderstand the structure of the code ]

### Optional: Feedback on the assignment

[very helpful assignment to under stand and visualize how multithreading works ,but can be more begginer friendly]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is an independent program with its own memory space, while a thread is a lighter unit and is a part of a process and shares memory with other threads within the process,and as a result to using threads, the communication is faster and creation overhead is lower,and it is why we used threads to simulate the CPU scheduler. In the code the process class is a simulated process that defines the burst time and time quantum, while the real Java Thread is created using the new Thread(process) line inside  addProcessToQueue() to actually execute the run() method .when a thread finishes its time quantum, a context switch occurs, and it is placed back into the ready queue until it completes its execution  .]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In a Round-Robin scheduling algorithm, when a process does not finish execution within the given time quantum, a context switch occurs and the process is turned back to the end of the ready queue,the thread is re queued instead of terminated because it has remaining execution time to complete its task, in the code this is handeled by checking the remainingTime and calling  addProcessToQueue(), re queuing matters for fairness and it garentees every process had  and equal share of CPU time.]

Example from my output: P7 is requeued twice and enters CPU 3 times until it finishes execution

```
[▶ P7 executing quantum [2000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P7 completed quantum 2000ms │ Overall progress: [████████░░░░░░░░░░░░] 41%
     Remaining time: 2800ms
  ↻ P7 yields CPU for context switch

  ➕ P7(Priority:10) added to ready queue │ Burst time: 4800ms
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P9 → P10 → P11 → P12 → P1 → P2 → P3 → P5 → P7]
└───────────────────────────────────────────────────────────────────────────────]
```

**Explanation of example:**
[the snippet shows P7 being requeued after its first time quantum expired, as it needs more CPU time to finish execution]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 enters the New state when the Thread object is instantiated with new Thread(process) inside the addProcessToQueue() method ,before execution begins]

2. **Runnable**: [P1 enters the Runnable state when currentThread.start() is called in the main scheduler loop, meaning its ready and waiting for the CPU to allocate time to it]

3. **Running**: [P1 is Running when its selected by the scheduler and it activly executes the code inside the run() method to simulate its burst time ]

4. **Waiting**: [P1 is waiting when it calls Thread.sleep() inside the run() method to simulate execution, while the main thread separetely enters a waiting state when it calls currentThread.join()]

5. **Terminated**: [P1 is Terminated when its run() method finishes executing (completing quantum of via rnToCompletion()) causing the main thread's join()to stop waiting]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [General Purpose CPU Scheduler]

**Description**:
[A general purpose  OS like Linux or Windows , running multiple apps simultaneously, like a music player and a background antivirus scan, here, each running app acts as a process and the OS assigns the time quantum to limit CPU access,and a context switch occurs when the OS saves the state of an app to run another ]

**Why Round-Robin works well here**:
[Round-Robin is crucial for fairness and responsiveness, ensuring heavy background tasks do not freeze other tasks, by giving every app a turn on the CPU, so the system remains interactive and immediately responsive , it also provides predictability, garenteeing every program gets a regular slice of processing time  ]

### Example 2: [Web Server Request Handeling]

**Description**:
[A web server that handles thousands of simulatanous requests form different clients, in this system each user request acts as a process, and the server allocates a small time quantum to process data for each request]

**Why Round-Robin works well here**:
[Round-Robin is ideal for fairness and preventing starvation, as it ensures that no request blocks the entire server, for example, if a user requests a massive file the server performs a context switch to prevent slowdowns, this garentees every user has fast and predictable initial response time.]

## Summary

**Key concepts I understood through these questions:**
1.I understood how the Round-Robin mechanism is crucial for fairness and responsiveness
2.I understood how context switches occur and how they're implemented
3.I learned how a static counter can track global metrics like context switch

**Concepts I need to study more:**
1.I need to look more into the difference between the simulated Process class and the actual Java Thread that executes it
2.I would like to know how other scheduling mechanisms work in real time 

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [✓] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [✓] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [✓] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [✓] Student ID is set in `SchedulerSimulation.java` (line 150)
- [✓] Code compiles and runs with no errors
- [✓] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [✓] Each feature has clear comments

**Commits**
- [✓] **At least 3 meaningful commits, ideally 6 or more**
- [✓] **One commit per feature**
- [✓] Commits are spread over **different dates** (not all in the last hour)
- [✓] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [✓] Full name and student ID filled in at the top
- [✓] Development log has **5+ entries** on different dates
- [✓] Reflection: 4 questions, 5-7 sentences each
- [✓] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [✓] No `[...]` placeholders left
- [✓] No section headers deleted

**Video**
- [✓] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [✓] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [✓] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [✓] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
