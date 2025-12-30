 # Photo-Manager-Archiver

### 🟨Developers🟨 
*Photogram group* [ITA]

Team members: Alessio Colautti [PROJECT MANAGER], Alex Troilo  
Mail: alessio.colautti@isisgo.it | alex.troilo@isisgo.it  
School site: [ISIS Galilei](https://isisgo.it/)  
Program release date: 05/12/2025

### 🟥Software🟥
Photo Manager Archiver is a software program written in Java, using the Apache NetBeans compiler,
designed to manage and organize a photo archive. Detailed information is available for each photo.
It can then be viewed and analyzed for any future purpose.

This software was developed by Alessio Colautti and Alex Troilo, two students in the 4B class of the
computer science department at the Galilei Fermi Pacassi Technical Institute in Gorizia.

### 🟩Features🟩
With Photo Manager Archiver, the user has the option, as previously mentioned, to
enter descriptive information for a photo archive and, subsequently, for an
indefinite number of photos so they can be tracked and their main characteristics can be viewed
in a simple and intuitive way.

When starting the program, the user can choose whether to interact from a common or administrative perspective,
making it possible for both customers and the archive owner to use it. In the first case, the common user can simply view
the information and characteristics of each photograph, while in the second case, the administrator is
required to authenticate with a password (admin). This password can be changed in the future by the administrator
in the program code itself by modifying the value of the [password] attribute at the beginning of the code.
After authenticating, the archive administrator can decide whether to simply view
the photo information, add new photo information, or delete the
save file and start the archive over.

Note: Once you've entered the general archive information, it cannot be changed until
you delete the save file and restart the archive.

When prompted to enter information, the user can decide:
- The type of subject in the photo
- Information about the subject
- If the subject is a person, the role of that person among those proposed
- A description of the subject if it is a landscape, an object, or a painting
- Information about the artist, the location, and the year the subject was created if it is a painting
- The physical condition of the photo and technical information

Finally, the user will be asked if they would like to add another photo. If they say no,
the information entered will be displayed.
