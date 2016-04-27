
### FAST-Mirror version 1.0   12/18/2012
The ideology behind making this small project was to replicate the idea of one of the biggest social networking site; Facebook. The project was made during first semester of Introduction to Computer Science Course and "C" was used as a primary language.

Known Issues:

1. Username and Father Name does not accept spaces
2. If given a correct choice, the program might crash or user might push to Log-In screen
3. There need to be at least two users to use most of the Main Screen features

Installation Guide:

1. Download the file fast mirror.c 
2. Download the Function Libraries including myFunctionLibrary.h and myFunctionLibrary.c
3. Open fast mirror.c using any compiler which can support C and C++ language.
4. Run

The main screen shows the following features to user

1. Sign-Up 
2. Log-In
3. Recover Password

### Sign-Up:
User has to enter the following information in Sign-up screen

•	Username
•	Father Name
•	Email
•	Password
•	Password Decryption Key
•	Secret Question

All information are saved in automatic generated files. When user successfully complete the sign-up process, the code generates two file automatically using the naming convention of (username).txt and (username)Profile.txt.
Username.txt contains following two instances
•	Username of User
•	Encrypted Password of the user using the Decryption Key

### Log-In and Forgot Password

User will be asked to enter his email and password to enter. In case if user forgot his password, he will be giving an option to retrieve it using security question or using PIN.

### Home Screen

After successful Log-in, using will be provided the following features:

•	Message other users.
•	View his/her own profile
•	Update profile
•	Check Messages
•	Check Wall
•	Update Status


Copyright 2012 Muhammad Rafay
  
The Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal
In the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

