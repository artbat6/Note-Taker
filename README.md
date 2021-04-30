# Note-Taker
Module 11 Challenge
See the live app here: https://arthur-note-taker.herokuapp.com/

# Project Description
The Note Taker is an app that uses an Express backend to save, retrieve, and delete notes from a JSON file.  The user starts at the home page shown in the screenshot below:
![Home page screenshot](1)

On the home page, the user clicks the "Get Started" button to navigate to the notes page.  On the left side of the screen is a list of existing notes, just showing the title of the note.
![Notes page screenshot 1](2)

Clicking the pencil icon in the upper right corner allows the user to write a new note.  The user has to click on either the "title" or "note" field and then can type the text they want to be in the note.  Once there is content in both fields, the save icon appears in the upper right next to the pencil icon.
![Notes page screenshot 2](3)

When the user clicks the save icon, the note is added to the JSON file and the list of notes on the left is updated to include the new note.
![Notes page screenshot 3](4)

The user can review existing notes by clicking any of the note titles on the left.  This will populate the "title" and "note" fields with the saved note information.
![Notes page screenshot 4](5)

A note can be deleted from the list by clicking the red trash can icon by the note title in the list on the left.  This will remove it from the JSON file and update the list on the screen.
![Notes page screenshot 5]()

The actual JSON file can be seen by navigating to the API in the web browser.
![API screenshot](7)

This app is hosted on Heroku and does not use an external database, so the JSON file that stores the notes is reset every time the server resets.

