# Wedding-Certificate-Printing-GUI-Application
Use friendly GUI desigend for very specific certificate printitng requirement, where pre-printed (blank) certificates were available, and software to fill out the gaps was required. 

It uses tkinter to input information for making the printable file for certifiate. It uses csv file to store the data of the cerificates made. It also shows the history of the forms made in the past along with its data. 

### Requirements:
- Python 2.7 - [download here](https://www.python.org/downloads/release/python-2718/)
- Windows 7 or above
- pip        19.2.3 - included with this Python version. (use `python -m pip` | ex. `python -m pip install reportlab`)
- reportlab  3.5.59
- Tkinter    1.0
- tkcalendar 1.6.1
- Microsoft Visual C++ 9.0  - [download here](https://web.archive.org/web/20200709160228if_/https://download.microsoft.com/download/7/9/6/796EF2E4-801B-4FC4-AB28-B59FBF6D907B/VCForPython27.msi)


After checking out the code, use .bat file or dashboard.py to inititate the application.

### RoadMap / Bugs list:
    login() - Login/ validation/ Entry Point / reset password.
    form() 
        - gather marriage info ✅
        - real-time Entry length limit (ex.address 75chars)
        - more info to gather? phone Numbers
    preview() - with bg image ✅
    print() - to PDF ✅
    logging enabled ✅
    Trim old Logs - to save space.
    store - CSV, maintain records ✅
    Report Bug/ feedback
    Dashboard() 
        - view history - activity(who printed/ created)
            - rePrint
        - users (new/block/delete/unblock) (ADMIN only)
        - create certificate ✅
    History() 
        view:
            - scrollbar ✅
            - search 
            - sort
        Actions:
            - reprint 
            - open folder/ file
    Notification()
        - user update
        - print update.
    Publish to GIT 
        - publish
        - link git to code
        - make exe/ lib 
    Report a Bug
