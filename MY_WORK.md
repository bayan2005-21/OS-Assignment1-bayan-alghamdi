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
| **Full Name** | [bayan mohammed alghamdi] |
| **Student ID** | [445052469] |
| **University Email** | [445052469@std.psau.edu.sa] |
| **GitHub Username** | [bayan2005-21] |
| **Repository Link** | [https://github.com/bayan2005-21/OS-Assignment1-bayan-alghamdi] |
 
---

## 🎥 Video Link

**Video Link**: [https://www.loom.com/share/731680e3a8b74a00b61cab0fd2b09c26]

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

### Entry 1 - [september 26,2026, 3:27 PM]

**What I did**: Forked the repository set up my student ID

**Details**: - i creat a github account with my university email
             - change the student id in line 150 to my student id (445052469)
             - committed the changes and save the repository

**Challenges**: i have to download JDK and VS code because they were not 
                in my laptop and it take me so long

**Solution**: download it and set the VS code to java language

**Time spent**: 1 hour

---

### Entry 2 - [october 1,2026 , 4:15 PM]

**What I did**:Implemented Feature 1 (Priority Scheduling).

**Details**:Added a priority attribute to the Process class and updated constructor to initialize random priority values between 1 and 10. Modified console outputs to log process priority levels when processes enter the ready queue.

**Challenges**:Output formatting issues where priority values were not displaying properly alongside ANSI color sequences.

**Solution**:Adjusted color constants concatenation and formatted the printed strings correctly.

**Time spent**: 1.5 hours

---

### Entry 3 - [october 4,2026 , 9:20 AM]
**What I did**: mplemented Feature 2 (Context Switch Counter).

**Details**: Added a static int contextSwitchCount variable inside SchedulerSimulation to keep track of CPU context switches. Incremented the counter each time a process was dequeued from processQueue and executed during the simulation loop, then printed the final total.

**Challenges**: Deciding where to place the counter increment to accurately reflect each switch without overcounting.

**Solution**: Placed contextSwitchCount++ right after dequeuing a new thread from the scheduling queue in the main loop.

**Time spent**: 1 hour

---

### Entry 4 - [october 6,2026 , 9:37 PM]
**What I did**: Implemented Feature 3 (Waiting Time Tracking & Average Calculation).

**Details**: Added timing attributes (arrivalTime, completionTime, waitingTime) and their getters/setters in Process.java. Updated SchedulerSimulation.java to calculate waiting time using CompletionTime - ArrivalTime - BurstTime upon process completion. Added a report loop using processMap.values() to print individual waiting times and average waiting time.

**Challenges**: Encountered compilation errors when trying to call .getRemainingTime() on processQueue instead of individual Process objects, and duplicate variable scope issues with Process process in loops.

**Solution**: Fixed data structure access by retrieving processes via processMap.get(currentThread) and renamed loop iterator variables to p.

**Time spent**: 2 hour

---

### Entry 5 - [october 7,2026 , 1:40 PM ]
**What I did**: Terminal Character Encoding Fixes & Documentation Finalization.

**Details**: Resolved terminal output artifacts (Arabic-like character symbols) caused by Windows PowerShell ANSI color code rendering by setting terminal encoding to UTF-8 (chcp 65001). Verified full simulation run and completed the final entries for MY_WORK.md.

**Challenges**: ANSI escape codes rendered as garbled characters (طُظ) in default VS Code Windows Terminal.

**Solution**: Configured active terminal session to code page 65001 (UTF-8) before running java SchedulerSimulation.

**Time spent**: 1.5 hours

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [7 hours]

**Most challenging part**: Handling waiting time calculations in Round-Robin scheduling across multiple context switches, and fixing local variable scope conflicts in the scheduler loop.

**Most interesting learning**: Understanding how CPU schedulers process tasks in discrete time quanta and seeing the direct trade-off between smaller quantum sizes and context switching overhead.

**What I would do differently next time**: Plan process data structures and timing formulas thoroughly on paper before starting the implementation in code.

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

[During this assignment, I learned how Java manages process tasks using threads by looking at the thread creation process in the codebase. I observed how each process task was wrapped in a ⁠Runnable⁠ lambda and started using ⁠currentThread.start()⁠ inside the scheduler loop. To synchronize execution and ensure time quanta were respected, ⁠currentThread.join()⁠ was used to make the main simulation thread wait for the task thread to complete. I also saw how simulated CPU execution work was performed using ⁠Thread.sleep()⁠ to pause thread execution for specific durations. A surprising aspect was realizing that ⁠Thread.sleep()⁠ required explicit exception handling with try-catch blocks to handle potential interrupts. Overall, this gave me a practical understanding of thread synchronization and lifecycle management in Java.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was correctly tracking and calculating the waiting time for each process in the Round-Robin simulation. Unlike simple FCFS, Round-Robin splits execution across multiple time quanta, which made tracking the accurate completion time tricky. Initially, I hit compilation errors when accidentally invoking methods like ⁠.getRemainingTime()⁠ on ⁠processQueue⁠ rather than the ⁠Process⁠ instance. Additionally, I faced variable scope conflicts within the scheduling loop when redeclaring the ⁠Process process⁠ variable. Fixing these scope issues while ensuring that waiting time was calculated only once the process fully completed required careful tracking. Seeing how time quanta directly impact thread scheduling made this both difficult and insightful.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame these challenges by taking an incremental debugging approach and systematically testing each change. First, I carefully reviewed the codebase structure to trace how objects were stored inside ⁠processMap⁠ and retrieved via threads. I added targeted print statements using ⁠System.out.println()⁠ to inspect remaining times and execution flow during each round. To solve the scope conflicts, I renamed local loop variables to distinct names like ⁠p⁠ to avoid duplicate identifier errors. I also adjusted the Windows terminal code page to UTF-8 using ⁠chcp 65001⁠ to properly display formatted outputs. Testing the code after every small modification ensured that existing functionality remained unbroken.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading concepts applied in this simulation are essential for building modern responsive software applications. For instance, modern web browsers like Google Chrome use separate threads or processes for each open tab to prevent one crashed tab from freezing the entire window. In media streaming platforms like Spotify or YouTube, background threads pre-buffer audio and video content while the main thread handles user interface interactions smoothly. Similarly, video game engines assign separate threads to physics processing, rendering graphics, and audio management. Just like our Round-Robin scheduler allocates CPU quanta, operating systems use these algorithms to ensure smooth multitasking across all background applications.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

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

[In operating systems, a process is an independent executing program with its own dedicated memory space, whereas a thread is a lightweight unit of execution that shares memory and resources with other threads within the same process. In our assignment, we used Java threads rather than separate operating system processes because thread creation introduces significantly less CPU creation overhead and enables direct memory sharing across simulated tasks. In ⁠SchedulerSimulation.java⁠, the class named ⁠Process⁠ is actually a custom data structure representing a simulated OS process, which is then executed by a real Java thread using the ⁠new Thread(process)⁠ call inside ⁠addProcessToQueue()⁠. This distinction allowed us to schedule each simulated process efficiently inside the ready queue while taking advantage of fast inter-thread communication speed.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, when a process cannot finish execution within its allocated time quantum, the CPU pre-empts the process, performs a context switch, and places it back at the end of the ready queue. In my program execution, process P2 had a total burst time of 6129ms with a time quantum of 4000ms, which required it to be re-queued once before completing. Re-queueing incomplete processes ensures CPU fairness because it prevents a long process from monopolizing the processor, allowing other threads in the ready queue to receive their fair share of execution time. This mechanism keeps the system responsive for all active tasks instead of blocking them behind long-running operati.]

Example from my output:
```
[process P2 enterd the rady queue with priority: 2
P2 added to ready queue 🧩é Burst time: 6129ms
Process          | Burst Time    | Waiting Time
P1               | 3626          | 0
P2               | 6129          | 0
]

```
**Explanation of example:**
[In this output snippet from my run, process P2 entered the ready queue with a priority of 2 and a burst time of 6129ms. Since my time quantum is set to 4000ms, P2 could not finish in its first CPU cycle, so the scheduler printed ⁠P2 added to ready queue⁠ to show it being re-queued at the back of ⁠processQueue⁠ to await its next time]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [Process P1 enters the New state when a new thread object is instantiated for it using ⁠new Thread(process)⁠ inside the ⁠addProcessToQueue()⁠ method.]

2. **Runnable**: [P1 moves to the Runnable state when the scheduler invokes ⁠currentThread.start()⁠, placing it in the ready queue eligible for CPU allocation.]

3. **Running**: [P1 transitions to the Running state when the Java virtual machine assigns CPU execution time to its thread and starts executing the instructions inside its ⁠run()⁠ method.]

4. **Waiting**: [P1 enters Timed Waiting when it executes ⁠Thread.sleep()⁠ to simulate CPU burst execution work, while the main simulation thread enters the Waiting state when it calls ⁠currentThread.join()⁠ to pause until P1 finishes its quantum.]

5. **Terminated**: [P1 reaches the Terminated state once its execution block in ⁠run()⁠ completes and the thread finishes execution permanently.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[In modern desktop operating systems like Windows or Linux, multiple user applications (such as a web browser, word processor, and music player) run concurrently on a single CPU core. Each open application acts as a process, and the OS CPU scheduler uses Round-Robin scheduling to allocate short CPU execution time slices (time quantum) to each process's threads. A context switch occurs when the OS switches execution registers from one active application thread to another.]

**Why Round-Robin works well here**:
[Round-Robin ensures absolute fairness because no single application can monopolize the CPU regardless of its burst size. It guarantees high responsiveness, allowing user input events like mouse clicks or typing to be processed promptly without noticeable lagging.]

### Example 2: [Name of application/scenario]

**Description**:
[In web browsers like Google Chrome, each open browser tab acts as a separate thread or process handling page rendering, JavaScript execution, and network downloads. The browser's internal task manager schedules execution time across these active tabs using time slicing. Here, each tab is a process, its execution quantum is a few milliseconds, and context switching transfers execution focus between tab renderers.]

**Why Round-Robin works well here**:
[Round-Robin maintains system responsiveness and predictability by ensuring that heavy JavaScript scripts in one background tab do not completely freeze the user interface or stop audio playback in active tabs.]

## Summary

**Key concepts I understood through these questions:**
1.How CPU Round-Robin scheduling manages fairness and responsiveness by distributing execution quanta across active processes.
2.The operational difference between lightweight Java threads and heavy simulated OS processes.
3.The exact state transitions of a thread lifecycle (New, Runnable, Running, Waiting, Terminated) during CPU context switching.

**Concepts I need to study more:**
1.Advanced scheduling algorithms like Multi-Level Feedback Queues (MLFQ) and Priority Preemption.
2.Thread synchronization mechanisms and avoiding race conditions in shared memory environments.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [x] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [x] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [x] Student ID is set in `SchedulerSimulation.java` (line 150)
- [x] Code compiles and runs with no errors
- [x] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [x] Each feature has clear comments

**Commits**
- [x] **At least 3 meaningful commits, ideally 6 or more**
- [x] **One commit per feature**
- [x] Commits are spread over **different dates** (not all in the last hour)
- [x] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [x] Full name and student ID filled in at the top
- [x] Development log has **5+ entries** on different dates
- [x] Reflection: 4 questions, 5-7 sentences each
- [x] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [x] No `[...]` placeholders left
- [x] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
