
# os-lab-quantum-IDTB110300


# Level 2: Audit Trails (Functions & File I/O)
![Level 2](<Level 2.png>)


# Level 3: The Exploit (TOC-TOU Vulnerability)
Run 1 final inventory: 76<br>
Run 2 final inventory: 78<br>
Run 3 final inventory: 78<br>
Run 4 final inventory: 68<br>
Run 5 final inventory: 82<br>

Explanation:
The final inventory changes because many processes run at the same time and access inventory.txt concurrently.
Several bots may read the same inventory value before another bot writes the updated value back, so the final
result depends on how the operating system schedules the processes.

# Level 4: The Patch (Mutex / File Locking)
![Level 4](<Level 4.png>)

# Level 5: Red Team vs. Blue Team (Cross-User Permissions)
![Level 5](<Level 5.png>)

# Level 6: Principle of Least Privilege (The Secure Drop Zone)
![Level 6](<Level 6.png>)

# Level 7: Forensic Cleanup (Log Management)
![Level 7](<Level 7.png>)



