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
| **Full Name** | [Hessa Alrumayli] |
| **Student ID** | [446051692] |
| **University Email** | [446051692]@std.psau.edu.sa |
| **GitHub Username** | [hessa-alrumyli] |
| **Repository Link**|[https://github.com/hessa-alrumyli/OS-Assignment1-Hessa-Alrumayli.git] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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

### Entry 1 - October 5, 2026, [1:30]

**What I did**: I set up the assignment and added my student ID.

**Details**:
- I opened the assignment in VS Code.
- I changed the student ID in `SchedulerSimulation.java` to 446051692.
- I installed and configured Git and JDK 17.
- I ran the program to make sure it worked.
- I committed and pushed the student ID change.

**Challenges**: Git and Java were not set up on my laptop at first.

**Solution**: I installed Git and JDK 17 and configured them in VS Code.

**Time spent**: About 2 hours

---

### Entry 2 - October 5, 2026, [3:20pm]

**What I did**: I added a priority value for each process.

**Details**:
- I added a priority variable to the `Process` class.
- Each process gets a random priority from 1 to 10.
- I displayed the priority when the process enters the ready queue.
- I ran the program to check that the priorities appeared correctly.

**Challenges**: I was not sure where to add the priority and how to display it in the ready queue.

**Solution**: I added the priority to the `Process` class and used `getPriority()` when printing the process information.

**Time spent**: about 20 m 



---
### Entry 3 - October 5, 2026, [Tim: 4pm]
**What I did**: I added a context switch counter to the scheduler.

**Details**:
- I added a static variable to count context switches.
- I increased the counter each time a process started running.
- I printed the total number of context switches at the end of the program.
- I ran the program and checked the result.

**Challenges**: I was not sure where the counter should be increased.

**Solution**: I placed the counter before `currentThread.start()` so it increases when a new process starts running.

**Time spent**: About 30 minutes

---

### Entry 4 - October 5, 2026, [5 pm]
**What I did**: I added waiting time tracking for each process.

**Details**:
- I added variables to store the waiting time.
- I used `System.currentTimeMillis()` to calculate how long each process waited.
- I updated the waiting time before the process started running.
- I added a final table showing the process name, burst time, waiting time, and turnaround time.
- I ran the program and checked that the values were displayed correctly.

**Challenges**: I was confused about when the waiting time should start and stop.

**Solution**: I tracked the time when the process entered the ready queue and updated it before the process started running.

**Time spent**: About 45 minutes
---

### Entry 5 - October 5, 2026, [6 pm]
**What I did**: I tested the final program and checked all the required features.

**Details**:
- I ran the program after finishing the three features.
- I checked that the priority values appeared in the ready queue.
- I checked that the context switch counter was printed at the end.
- I checked the waiting time and turnaround time table.
- I made sure the program ran without errors.

**Challenges**: I wanted to make sure all the values in the final output were correct.

**Solution**: I reviewed the output and checked some of the calculations, especially the turnaround time.

**Time spent**: About 20 minutes

---

### Entry 6 - October 6, 2026, [1:30 pm]

**What I did**: I updated the documentation in `MY_WORK.md`.

**Details**:
- I filled in my student information.
- I added my development log entries.
- I organized the details of each work session.
- I checked that the dates, tasks, and time spent were included.

**Challenges**: I needed to organize the work I had completed into clear development log entries.

**Solution**: I reviewed my work sessions and documented each task separately.

**Time spent**: in spreated time
---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [5-6 hours]

**Most challenging part**:The most challenging part was understanding how to calculate and track the waiting time correctly.

**Most interesting learning**:The most interesting part was seeing how Round-Robin scheduling gives each process a time quantum and returns unfinished processes to the ready queue.

**What I would do differently next time**: I would read the full code earlier and test each change immediately before moving to the next task

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

[I learned that threads are used to execute tasks inside a program. In this assignment, each simulated process is executed using a Java thread. I understood that `Thread.start()` starts the thread and allows its `run()` method to execute. I also learned that `Thread.join()` makes the main thread wait until the current thread finishes. The existing code uses `Thread.sleep()` to simulate the CPU working for a certain amount of time. I also learned that a process can return to the ready queue if it does not finish within the time quantum.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[I think the most challenging part was adding the waiting time tracking feature. At first, I was not sure when the waiting time should start and when it should be updated. I also needed to understand how the ready queue works before adding the code. It was confusing to decide where to use `System.currentTimeMillis()`. I tested the program several times and checked the final table after each change. After that, I understood how the waiting time was calculated for each process.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by working on the assignment step by step. I read the README again when I was not sure what to do. I also reviewed the code to understand where each feature should be added. After every change, I ran the program and checked the output. When something was confusing, I asked for help and compared the result with the assignment requirements. This helped me understand the code better and fix the problems.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading can be used in many real-world applications to make programs more responsive. For example, a web browser can use different threads for loading a page, playing media, and responding to user actions at the same time. A game can also use separate threads for graphics, sound, and player input. This is similar to the assignment because different tasks share CPU time instead of one task using it for too long. Round-Robin scheduling can help give each task a fair amount of CPU time. Multithreading helps programs handle several tasks efficiently without making the whole application stop and wait.]

### Optional: What would you like to learn more about?

I would like to learn more about how threads are scheduled by the operating system.

### Optional: How confident do you feel about multithreading concepts now?

Intermediate. I understand the basic ideas of threads, the ready queue, and Round-Robin scheduling, but I still need more practice.

### Optional: Feedback on the assignment

The assignment was useful and helped me understand multithreading better through practice.

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

[A process is an independent program with its own memory, while threads inside the same process share memory and resources. Threads are usually faster to create and have less overhead than separate processes. In this assignment, the `Process` class represents a simulated process, but it is executed using a real Java thread. In `addProcessToQueue()`, the line `new Thread(process)` creates a thread for each simulated process, which allows the scheduler to manage and run them efficiently.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[When a process does not finish within its time quantum, it is added back to the ready queue. In my program, P2 had a burst time of 11247 ms and the time quantum was 5000 ms. P2 was re-queued two times before it finished because it needed three CPU runs to complete. Re-queueing gives the other processes a chance to use the CPU, which makes Round-Robin scheduling fair.]

Example from my output: 
P2 executing quantum [5000ms]
P2 completed quantum 5000ms
Remaining time: 6247ms
P2 yields CPU for context switch
P2 added to ready queue - Burst time: 11247ms priority: 7

P2 executing quantum [5000ms]
P2 completed quantum 5000ms
Remaining time: 1247ms
P2 yields CPU for context switch
P2 added to ready queue - Burst time: 11247ms priority: 7
```
[P2 completed quantum 5000ms
Remaining time: 6247ms
P2 yields CPU for context switch
P2 added to ready queue - Burst time: 11247ms priority: 7]
```

**Explanation of example:**
[P2 did not finish after the first 5000 ms, so it returned to the ready queue with 6247 ms remaining. After another 5000 ms, it still had 1247 ms remaining, so it was re-queued again. It then finished during its final CPU run.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 is in the New state when `new Thread(process)` creates its thread inside `addProcessToQueue()`.

2. **Runnable**: P1 becomes Runnable when `Thread.start()` is called and the thread is ready to be scheduled.

3. **Running**: P1 is Running when its `run()` method is executing and it uses its time quantum.

4. **Waiting**: P1 pauses during `Thread.sleep()` while simulating CPU work, while the main thread waits for P1 when `Thread.join()` is called.

5. **Terminated**: P1 reaches the Terminated state when its thread finishes executing the `run()` method.


## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU Scheduling

**Description**:
An operating system can use Round-Robin scheduling to share CPU time between different running programs. Each running program acts like a process, and each one gets a time quantum to use the CPU.

**Why Round-Robin works well here**:
Round-Robin gives every process a fair chance to run and helps keep the system responsive. A context switch happens when the CPU moves from one process to another.

### Example 2: Web Server

**Description**:
A web server can use multiple threads to handle requests from different users. Each request can act like a task that needs CPU time.

**Why Round-Robin works well here**:
Round-Robin can give each thread a time quantum so one request does not use the CPU for too long. This improves fairness and responsiveness, and a context switch happens when the CPU moves from one thread to another.

## Summary

**Key concepts I understood through these questions:**
1. The difference between a thread and a process.
2. How Round-Robin scheduling uses a ready queue and time quantum.
3. How context switches happen between running processes.

**Concepts I need to study more:**
1. Thread lifecycle states.
2. How operating systems schedule threads in real systems.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
