# Supplementary Requirements

**Author**: **Team26**

Requirements listed here are non-functional in nature and these requirements do not fit the use case model which 
typically captures the functional requirements.

##1.1 Programming environment

The target platform of the application is Android OS, the minimum SDK level is API version-16 and the targeted API is
version-19. 

##1.2 Documentation

The application shall be accompanied by a user manual that indicates how to use the application, offers trouble-shooting
tips and includes additional technical details.

##1.3 Database storage

Transactions and customers need to be stored in a storage system for later retrieval. Standard Android provided storage
mechanisms such as SQL-Lite should be used.

##1.4 User Interaction and Security

One user can use the application at a time. There is no additional security that is implemented other than the user 
being able to login to the Android device. And all the application data is stored only in the device. 

##1.6 Data Backup

No default backup is provided by the application. It is the user's responsibility to backup data from the Android device.

##1.7 Project Execution Methodology

UML-based process has to be used for project implementation to get an experience of Unified Software Process

##1.8 User Interface

The application should be optimized to run on Android phones. UI testing should be conducted using Genymotion simulator
or an Android device. It is optional to test the application for an Android tablet
