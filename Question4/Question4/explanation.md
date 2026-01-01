## Question 4 – Command Explanations

1. uptime – Shows system uptime, logged-in users, and load averages.
2. ps -u $(whoami) – Lists active processes owned by the current user.
3. top – Displays real-time running processes and CPU usage.
4. sleep 300 & – Runs a sleep command in the background.
5. renice +5 -p <PID> – Changes process priority (niceness).
6. ps -o pid,ni,cmd -p <PID> – Verifies niceness change for the process.
7. free -h – Displays RAM and swap usage in human readable format.
8. df -h – Shows disk space usage of all mounted filesystems.
9. echo $SHELL – Shows the shell currently in use.
10. uname -a > system_report.txt – Saves system information into a report file.
11. ncdu ~ – Interactive disk usage viewer to analyze folder sizes.

