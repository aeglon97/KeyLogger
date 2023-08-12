# KeyLogging Detector
Implantable keylogger program

**Goal:** to track any suspicious or dangerous conduct on the devices the program implanted in and send a secure, untraceable alert to a destination host.

MVP reqs:

---

- Must be easily transferrable and replicated between devices.
- Use AI to read all user key input and detect suspicious/dangerous behavior (abusive, criminal, etc.)
- Authorized users should be able to 1) stream user key input live, and 2) generate a properly formatted .txt file at any given time (filtered by time range and/or key words)


Stretch goals:

---

- When an anomaly is detected, send the appropriate *untraceable* alert to a specified third party.
- Undetectable by antivirus
- Does not show up as a running process in task manager; must not be included in local CPU/Memory calculation reports
