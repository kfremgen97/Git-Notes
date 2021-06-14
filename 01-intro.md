# Version Control

Version control, also known as source control, is the practice of tracking and managing changes to software code. 
Version control systems are software tools that help software teams manage changes to source code over time.

As development environments have accelerated, version control systems help software teams work faster and smarter
Version control software keeps track of every modification to the code in a special kind of database. 

There are two main types of version control system models:
- the centralized model 
    - all users connect to a central, master repository
- the distributed model 
    - each user has the entire repository on their computer

Remember that the main point of a version control system is to help you maintain a detailed history of the project as well 
as the ability to work on different versions of it. 
Having a detailed history of a project is important because it lets you see the progress of the project over time. 
If needed, you can also jump back to any point in the project to recover data or files.

---

## Benefits of version control

The primary benefits you should expect from version control are as follows:

- A complete long-term change history of every file. 
  - This means every change made by many individuals over the years. 
    Changes include the creation and deletion of files as well as edits to their contents. 
    Different VCS tools differ on how well they handle renaming and moving of files. 
    This history should also include the author, date and written notes on the purpose of each change. 
    Having the complete history enables going back to previous versions to help in root cause analysis for bugs and it is crucial when needing to fix problems in older versions of software. 
    If the software is being actively worked on, almost everything can be considered an "older version" of the software.

- Branching and merging. 
  - Having team members work concurrently is a no-brainer, but even individuals working on their own can benefit from the ability to work on independent streams of changes. 
    Creating a "branch" in VCS tools keeps multiple streams of work independent from each other while also providing the facility to merge that work back together,
    enabling developers to verify that the changes on each branch do not conflict.
    Many software teams adopt a practice of branching for each feature or perhaps branching for each release, or both.
    There are many different workflows that teams can choose from when they decide how to make use of branching and merging facilities in VCS.

- Traceability. 
  - Being able to trace each change made to the software and connect it to project management and bug tracking software such as Jira, 
    and being able to annotate each change with a message describing the purpose and intent of the change can help not only with root cause analysis and other forensics. 
    Having the annotated history of the code at your fingertips when you are reading the code, 
    trying to understand what it is doing and why it is so designed can enable developers to make correct and harmonious changes that are in accord with the intended long-term design of the system. 
    This can be especially important for working effectively with legacy code and is crucial in enabling developers to estimate future work with any accuracy.

