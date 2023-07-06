---
created: 2023-06-26T12:23
updated: 2023-07-06T22:07
share: true
---
# Buy and download the X-KeyPad plugin
Step one is to buy and download X-KeyPad from, for example, the X-Plane.org store.
![[../images/Scherm­afbeelding 2023-07-06 om 21.56.09.png|Scherm­afbeelding 2023-07-06 om 21.56.09.png]]
![[../images/Scherm­afbeelding 2023-06-26 om 13.08.01.png|Scherm­afbeelding 2023-06-26 om 13.08.01.png]]
# Download the A319 profile
Next, download the A310 Stream Deck profile from the files section of the X-Plane.org forum.
![[../images/Scherm­afbeelding 2023-07-06 om 21.58.48.png|Scherm­afbeelding 2023-07-06 om 21.58.48.png]]

# Unzip files and install plugin in the X-Plane folder
Once you have downloaded X-KeyPad from the store, you'll have a ZIP file. Extract it.
![[../images/Scherm­afbeelding 2023-07-06 om 22.02.13.png|Scherm­afbeelding 2023-07-06 om 22.02.13.png]]
Go to your X-Plane location. If you have the Steam version, right click on X-Plane, select *Properties* and then go to *Installed Files*. Then click *Browse...*. That's your X-Plane folder when using Steam.
![[../images/Scherm­afbeelding 2023-07-06 om 22.02.59.png|Scherm­afbeelding 2023-07-06 om 22.02.59.png]]
![[../images/Scherm­afbeelding 2023-07-06 om 22.03.20.png|Scherm­afbeelding 2023-07-06 om 22.03.20.png]]If you downloaded X-Plane directly from X-Plane.com, I assume you know where you installed it.

In the X-Plane folder go to `Resources` and then `plugins`. Put the X-KeyPad folder you extracted in the previous step here.
![[../images/Scherm­afbeelding 2023-07-06 om 22.04.33.png|Scherm­afbeelding 2023-07-06 om 22.04.33.png]]
# Quarantine on Mac
The next step can be ignored on Windows, but is important on the Mac. By default downloaded software will be quarantined by your Mac. To fix this, open the Terminal app (in your Applications folder under Utilities) and type this command:
`sudo xattr -r -d com.apple.quarantine <your X-Plane folder>`
Replace `<your X-Plane folder>` with, well, your X-Plane folder.
# Install Stream Deck profile
In the X-KeyPad plugin folder there's an `SD-plugin` folder. In it is the Stream Deck plugin that allows X-KeyPad to talk with your Stream Decks. Just double click it and it will be installed.
![[../images/Scherm­afbeelding 2023-07-06 om 22.05.47.png|Scherm­afbeelding 2023-07-06 om 22.05.47.png]]

Now start X-Plane, doesn't matter if it's version 11 or 12. In this tutorial I'll use X-Plane 12.

Load 

