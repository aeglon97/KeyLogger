# KeyLogging Detector
Implantable keylogger program

**Goal:** A virus that detects when someone is committing crimes against humanity. 

Workflow:

1. Stream all user keyboard input AND click events to an external server

2. Server-side User Listener reads and processes all live user input from the database.

3. If the listener's AI detects activity suggesting 1) human trafficking, 2) terrorism, and/or 3) domestic abuse, send an alert to an authorized email. Generate a report that includes all the relevant logs which triggered that alert.  

MVP reqs:

---

- Must work on Windows.

- 3 crime categories to detect: human trafficking, terrorism, and domestic abuse.

- All outbound communications untraceable


Stretch goals:
---

- Undetectable by antivirus

- Does not show up as a running process in task manager; must not contribute to CPU/Memory usage reporting 
