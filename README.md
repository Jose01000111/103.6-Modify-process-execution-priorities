# 🧪 Lab: 103.6 Modify Process Execution Priorities

## 📌 What I did in this lab:
I launched processes with default and custom priorities, examined running processes, and modified the priority of live processes using both terminal commands and interactive tools. This gave me practical experience with real-world Linux resource management. 🧠

[EXAM OBJECTIVE 103.6](https://www.lpi.org/our-certifications/exam-101-102-objectives/#103.6_Modify_process_execution_priorities)

[OBJ. 103.6 NOTES]()

[OBJ. 103.6 LAB]()

---

## 1️⃣ Understanding Default Priorities

🔹Check the default nice value of a running shell

🔹Run a basic command and observe its priority

## 2️⃣ Running a Program with a Custom Priority

🔹Start a process with lower priority (nice value +10)

🔹Start a process with higher priority (only as root)

🔹Verify both with ps

## 3️⃣ Changing the Priority of a Running Process

🔹Find the PID of the running sleep command

🔹Change the priority using renice

🔹Try again with root privileges to increase priority

## 4️⃣ Monitor Processes Interactively

🔹Use top to observe nice values and real-time CPU use

🔹Press r inside top to renice a process interactively

🔹Enter the PID and the new nice value.

##💡 What I learned
Through this lab, I learned how Linux assigns default process priorities and how I can adjust them dynamically. I now understand how nice and renice influence CPU scheduling and why adjusting priorities can improve system responsiveness. This is essential for performance tuning in production environments. ⚙️📈🐧

