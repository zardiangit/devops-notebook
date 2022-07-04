---
id: epb0qgtdkyalbf2fq8ata2q
title: Jobs
desc: ''
updated: 1656831442459
created: 1650467559384
---

### Background and Foreground Jobs  
  - Jobs can be run as foreground as well as background processes.
   
   - A job can be sent to the background by suffixing `&` to the command. eg: `updatedb &`.
   
   - Use `ctrl+z` to suspend or `ctrl+c` to terminate a foreground job.
   
   - `bg` and `fg` commands can be used to run a process in background or foreground when suspended or with PID.

### Managing Jobs
   - `jobs -l` provides the same information as `jobs` with added **PID** of the background jobs.