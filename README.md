# Employee-Monitor

Using Intel's OpenVino to recognise faces and emotional state of employees and create a time and attendance register for them with their emotional state.

### Model Usage

This project will be making use of Intel's face recognition and emotion recognition models

### Project usage

This project will run on a backend server that gets the two video's streamed to it from the entry and exit facing cameras located at the entrance/exit of the office. 
The project will run infrence on the video, recording the first and last sighting of every person that enters and leaves together with the person's emotional state to a MySQL database together with an image of the person.
The program will have a configurable threshold for the amount of captures of a sad or angry state it will get consecutivly before alerting HR via email about the employee that might need some attention from HR.

