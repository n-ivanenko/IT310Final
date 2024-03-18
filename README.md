#IT310Final

For my final, I took inspiration from my ballet company's rehearsal schedule as it is only ever distributed in paper form. I thought I can utilize my diagramming knowledge I have acquired this quarter to plan out a hypothetical online calendar that can be shared and distributed virtually rather than physically. 


In this repo, there is my UML class diagram, ERD, and UI wireframes of some basic pages to outline a rough foundation of how I would go about creating a webpage like this.


Below I will paste some brainstorm ideas I had when first coming up with the requirements this webpage would have. Obviously this can be expanded upon exponentially, adding more features and concepts, but this is a representation of this webpage at its most basic form.


Calendar Website Brainstorm


User:
- User must create account to access calendars
- User can manage Username and Password
- User can CRUD personal Calendars and Events
- User can share calendars with other users via username to grant viewing access


Calendar:
- Calendars can only be accessed by users who have been granted permission
    - Calendar can be viewed (not edited) by other users who have been granted permission
- Calendar can only be updated by creator
    - Updates include:
        - edit calendar name
        - share calendar
        - edit permissions
        - delete calendar
- Once calendar has been deleted no users can access it


Event:
- Multiple events can be created for the same slot
- Event can still be edited once it has passed
- Event can be viewed by user who has access
- Events can only be created and edited by creator
   - Updates include:
       - edit event name
       - edit the calendar to which event belongs to
       - edit event date
       - edit event start time
       - edit event end time
       - add notes
