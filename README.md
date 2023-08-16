# MusicRecommendationSystem

Name: Emotica - The song generator
A music recommendation system uses facial emotion recognition to suggest personalized songs. OpenCV and Deepface libraries detect facial expressions and extract emotions. A small music library in MySQL recommends a song based on the user's preferred language. The user is redirected to the browser for the recommended song.

PS:
note: in the line 146 of musicgen.py, make sure to change the iconbitmap file path to the one in this folder. (file name: icon.ico)
note: make sure to install the following modules before running the code.
-> cv2
-> deepface
-> mysql.connector
note: in the musicgen.py file, make sure to instal the mysql, then, change the password to **YOUR** current root password. (line 6)
note: make sure to connect to mysql server (in workbench) and paste the **EXACT** commands as in backend.sql (run the commands line by line).
note: in the musicgen.py file, in the line 105 of emotion() function, make sure to change the path og glob.glob("/path/name") to the current path, where your musicgen.py file is stored. (so that it can read the most recent img created when camera is opened).

Contributors:
Phase 2:
G Varun (21011102033)
Judah Jacinth (21011102041)

Phase 1:
G Varun (21011102033)
Abhishek Herbert Samuel (21011102004)
Kota Sri Laasya (21011102050)
L Karthikeya Reddy (21011102053)
