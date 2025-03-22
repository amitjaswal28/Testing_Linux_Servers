
**Task 1: System Monitoring Setup**

**Objective:** Configure a monitoring system to ensure the development environment’s health, performance, and capacity planning.

**Implementation Steps:**

1. Install monitoring tools (`htop`, `nmon`).
2. Set up disk usage monitoring (`df`, `du`).
3. Implement process monitoring (`ps`, `top`).
4. Store logs in `/var/log/system_monitor/` for review.

![image](https://github.com/user-attachments/assets/8e7092a1-3581-45e5-afeb-191b5c520ed8)


**Task 2: User Management and Access Control**

**Objective:** Set up user accounts and configure secure access controls for the new developers.

**Implementation Steps:**

1. Create user accounts for sarah and mike with secure passwords.
2. Set up dedicated workspace directories.
3. Restrict access to respective users.
4. Implement a password policy enforcing expiration and complexity.

![image](https://github.com/user-attachments/assets/28b04e07-5071-45a8-a4bd-fd6bffa8d3b3)
![image](https://github.com/user-attachments/assets/40a84df2-4d72-45f5-ae11-d2f25ccf23d6)
![image](https://github.com/user-attachments/assets/dee9f130-15cf-403c-8adf-d983a2c212cc)



**Task 3: Backup Configuration for Web Servers**

**Objective:** Configure automated backups for sarah’s Apache server and mike’s Nginx server to ensure data integrity and recovery.

**Implementation Steps:**

1. Create a backup directory (`/backups/`).
2. Create and configure a backup script.
3. Schedule backups using a cron job (runs every Tuesday at 12:00 AM).
4. Verify backup integrity and log results.

![image](https://github.com/user-attachments/assets/a7103fdb-3726-4c0e-93c7-7d5e0dbcca7d)


**Expected Output:**

- **Monitoring System:** Logs stored in `/var/log/system_monitor/`
- **User Management:** Secure user directories created with proper access restrictions.
- **Backups:**
  - Backup files stored in `/backups/`
  - Verification logs stored in `/var/log/backup_verification.log`
  - Last backup status recorded in `/var/log/last_backup.log`
