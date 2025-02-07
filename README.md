# Scripting-and-Automation
Using Bash for Scripting and Automating WorkFlows

# Bash Scripting & Automation

## Overview
Bash scripting is a powerful tool that can help automate repetitive tasks, streamline workflows, and improve efficiency. This guide walks through essential Bash scripting concepts and real-world automation use cases.

## Topics Covered
### Section 1: Basics of Bash
1. **Why Automate with Bash?**
2. **Creating and Running a Bash Script**
   - Using `nano` to create a script
   - Adding a shebang (`#!/bin/bash)

### Section 2: Practical Task Automation
1. **Automating Backups with `rsync` and `tar`**
   - Using `rsync` for incremental backups
     ![Screenshot 2025-02-06 013612](https://github.com/user-attachments/assets/946366a7-3db6-4095-91af-9bba2f20ed2b)

   - Compressing backups using `tar`
   - Logging backup status
     ![Screenshot 2025-02-06 014301](https://github.com/user-attachments/assets/e76fa58f-a085-452c-bfb2-7bb54d3a2dce)
   - OUTPUT OF SCRIPT:
     ![Screenshot 2025-02-06 014543](https://github.com/user-attachments/assets/104fa492-e689-45ad-8492-b91fd0ac6dd6)


   - Scheduling automated backups with `cron`: We will automate this script and let it do an automatic everyday at midnight
     ![Screenshot 2025-02-06 014832](https://github.com/user-attachments/assets/16a685ff-cab4-4fde-8a10-ce63fb3e08e4)
  
2. **Monitoring Server Health**
   - Checking CPU load, memory usage, and disk space
   - Logging system health status
     ![Screenshot 2025-02-06 015810](https://github.com/user-attachments/assets/d2427534-df64-46eb-8d3c-a04ec618dcde)
   - OUTPUT:
     ![Screenshot 2025-02-06 020014](https://github.com/user-attachments/assets/9847aec3-5b39-4d0c-9406-a09c27f8ff9f)

   - Scheduling system health checks using `cron: We will us cron to automate this to check and run every 10 minutes
     ![Screenshot 2025-02-06 020410](https://github.com/user-attachments/assets/7f014102-7a45-48c6-bf0d-d0bb720ea286)
 
3. **Automating System Updates and Maintenance**
   - A script for Updating installed packages
   - Cleaning up unnecessary packages
   - Logging update status
    - SCRIPT:
     ![image](https://github.com/user-attachments/assets/d990215b-a5e9-4fd7-8348-dcd7da72a2ea)

     OUTPUT:
     ![Screenshot 2025-02-06 021024](https://github.com/user-attachments/assets/1e0ebb85-6ad6-4adf-8d15-b8ef4453a957)

   - Running updates automatically using `cron`: Adding the line below in the crontab allows us to run this script at 2AM every Sunday
     ![Screenshot 2025-02-06 195915](https://github.com/user-attachments/assets/3d4e2716-ec34-4eae-afb3-57ed0ee900cb)





## Conclusion
-Bash scripting is a powerful tool for automating tasks and improving workflow efficiency. Mastering these basics will help you streamline repetitive processes and improve productivity. 
