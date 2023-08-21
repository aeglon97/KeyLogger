# Smart Crime Detector 
Implantable keylogger program

**Goal:** Create a virus that detects when someone is committing crimes against humanity. 

Workflow:

1. Stream all user keyboard input AND click events to an external server.

2. Server app reads and processes all NEW live user input from the database.

3. Wait until the AI detects activity suggesting 1) human trafficking, 2) terrorism, and/or 3) domestic abuse.

4. Generate a report containing all the relevant information which triggered that alert.  

5. Send that report to an authorized 3rd party.

MVP reqs:

---

- Must work on Windows.

- 3 crime categories to detect: human trafficking, terrorism, and domestic abuse.

- All outbound communications untraceable


Stretch goals:
---

- Undetectable by antivirus

- Multi platform, including mobile support 

- Does not show up as a running process in task manager; must not contribute to CPU/Memory usage reporting 
