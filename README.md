# df-mod6-mobile

## Browser Data forensics using SQLite

This respository includes files used in the Digital Forensics described at [TSPD.md](TSPD.md).

## Required Skills
To successfully participate in the TSPD Digital Forensics Challenge, 
particularly in Project 6, which focuses on browser data analysis, the following skills are essential:
- Understanding of digital evidence acquisition, analysis, and interpretation.
- Familiarity with the structure and content of browser files, including history, cookies, and cache.
- Ability to navigate and query SQLite databases, as browsers often store data in this format.

## Tools

- VS Code
- VS Code Extension: SQLite Viewer by Florian Klampfer
- [DB Browser for SQLite](https://sqlitebrowser.org/)

To install an extension in VS Code, 
go to the Extensions tab and search for the name and author. 

## Explore Databases in VS Code

You can browse and search the database files in VS Code by clicking on them with the recommended extension installed.

Click on a .sqlite file (pink icon) to open the table and search the data.

## Explore Databases in DB Browser for SQLite

In DB Browser, use  File / Open Database to open a database file. 

Use the drop-down list to select a table in the database. 

Use the "Execute SQL" tab to run queries. 

Investigators can use SQL queries to search for other types of information, 
e.g., credit card numbers and email addresses. 

## Project Usefulness
This project is integral to TSPD Digital Forensics, focusing on analyzing digital evidence. 
Extracting and interpreting data from browser files is crucial, 
revealing suspects' online behavior, including search history and timestamps. 
It's vital for establishing timelines and intent. 
The challenge offers hands-on experience with tools and scenarios encountered in digital forensics, enhancing practical skills. 
Participation not only hones technical abilities but also contributes to combating illegal stuffed animal trade, safeguarding Toy Story universe creatures. 
These skills transcend this case, applying broadly to mobile data forensics. 
Mastery aids in solving real-world issues, tracking illegal activities, and assisting law enforcement in criminal investigations.

## Resources

- [SANS DFIR Advanced Smartphone Forensics](https://www.sans.org/posters/dfir-advanced-smartphone-forensics/)
- [Dataset construction challenges for digital forensics, 2021](https://tsapps.nist.gov/publication/get_pdf.cfm?pub_id=931168)
- [GitHub: Android Forensics Resources](https://github.com/RealityNet/Android-Forensics-References)
- [University of New Haven DATASETS FOR CYBER FORENSICS](https://datasets.fbreitinger.de/datasets/)
