# Architecture of Task Manager
Hosted on a computer on my network - RPi or Desktop (?)
Available offline (?)

## Features

### Projects
- Manage projects, which contain tasks
- Projects have their own metadata
    - Defer date
    - Due date
    - Status
        - Active
        - On hold
        - Completed
        - On hold
    - Tags
    - Project type 
        - Parallel tasks
        - Sequential task
        - Single actions
    - Estimated duration
    - Notifications
    - Time zone
        - Floating
        - Fixed
    - Date completed
    - Date dropped
    - Repeat schedule
    - Review schedule
    - Notes (text only)
    - Attachments (documents/images etc.) <-- optional feature!

### Tasks
- Tasks contain other metadata including date added:
    - Defer date
    - Due date
    - Status
        - Active
        - On hold
        - Completed
        - On hold
    - What project they are assigned to (Inbox if no other project)
    - Tags
    - Estimated duration
    - Notifications
    - Time zone
        - Floating
        - Fixed
    - Date completed
    - Date dropped
    - Repeat schedule
    - Review schedule
    - Notes (text only)
    - Attachments (documents/images etc.) <-- optional feature!

### Views
- Can view either projects, or perspectives (based on tags and other metadata)
