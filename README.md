This project demonstrates a Python algorithm that automates the process of updating an allow list of IP addresses — a common cybersecurity maintenance task.
The script reads a text file containing IP addresses, removes those found on a separate remove list, and rewrites the updated addresses back into the file.
How It Works
Reads IP addresses from allow_list.txt.
Reads addresses to remove from remove_list.txt.
Compares both lists and removes any matches.
Writes the updated list back to the file.
Example Files
allow_list.txt
192.168.1.1
172.16.0.5
10.0.0.1
remove_list.txt
10.0.0.1
Output after running the algorithm:
192.168.1.1
172.16.0.5
Skills Demonstrated
Python File I/O
List operations and loops
Conditional logic
Automation concepts in cybersecurity
Screenshot
![screenshots](<img width="554" height="793" alt="Captură de ecran 2026-05-06 164304" src="https://github.com/user-attachments/assets/39eb7db0-0c6a-4833-9cbb-a10f4aba93a8" />
)

