# 🧪 Lab: 103.6 Modify Process Execution Priorities

## 📌 What I did in this lab:
I launched processes with default and custom priorities, examined running processes, and modified the priority of live processes using both terminal commands and interactive tools. This gave me practical experience with real-world Linux resource management. 🧠

[EXAM OBJECTIVE 103.6](https://www.lpi.org/our-certifications/exam-101-102-objectives/#103.6_Modify_process_execution_priorities)

[OBJ. 103.6 NOTES](https://1drv.ms/w/c/354f1c8d534fbced/EQ1wyEsZCAtLtJpy3U1QrEwBCwvflYx-NC4DoQAZalZeDw?e=8rq4Nj)

[OBJ. 103.6 LAB](https://1drv.ms/w/c/354f1c8d534fbced/EQ1wyEsZCAtLtJpy3U1QrEwBJ1Fi_mK_PKlfjVkXrQipTg?e=PFEGl2)

---

## 1️⃣ Understanding Default Priorities

🔹Check the default nice value of a running shell

🔹Run a basic command and observe its priority

![0kjGznv](https://github.com/user-attachments/assets/b29851cf-7030-4246-b1fe-041a99b0e549)

## 2️⃣ Running a Program with a Custom Priority

🔹Start a process with lower priority (nice value +10)

![9fwh0oF](https://github.com/user-attachments/assets/e5d62367-561f-400a-a539-fb45cb8c9df3)

🔹Start a process with higher priority (only as root)

![V7nARaL](https://github.com/user-attachments/assets/23b4801e-5101-4316-989a-c389ee512a35)

🔹Verify both with ps

![FNXY3be](https://github.com/user-attachments/assets/1206b01f-097f-4990-958b-d757363338b3)

## 3️⃣ Changing the Priority of a Running Process

🔹Find the PID of the running sleep command

![q8YpBkh](https://github.com/user-attachments/assets/837a9888-2278-48e0-a210-2c7c85638a10)

🔹Change the priority using renice

🔹Try again with root privileges to increase priority

![oZ3TunU](https://github.com/user-attachments/assets/31043925-4dd6-4022-b7bc-bff06a250c16)

## 4️⃣ Monitor Processes Interactively

🔹Use top to observe nice values and real-time CPU use

🔹Press r inside top to renice a process interactively

![M8fj7nn](https://github.com/user-attachments/assets/28318d1c-d740-461a-822e-9d91494fa03e)

🔹Enter the PID and the new nice value.

![xHOppy5](https://github.com/user-attachments/assets/96cb0056-81d4-436a-ba34-4f20225de017)

![IhtnxJM](https://github.com/user-attachments/assets/608c6cec-54cd-4217-816b-59bc29847c0c)

##💡 What I learned
Through this lab, I learned how Linux assigns default process priorities and how I can adjust them dynamically. I now understand how nice and renice influence CPU scheduling and why adjusting priorities can improve system responsiveness. This is essential for performance tuning in production environments. ⚙️📈🐧

