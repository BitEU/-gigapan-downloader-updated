# -gigapan-downloader-updated
An updated version of gigapan-downloader from the Google Code Arcive https://code.google.com/archive/p/gigapan-downloader/


All credit goes to the user on Google Code Archive who created this script. I updated it from Python 2 to 3 and renamed a few functions and removed a few imports because they were not working satisfactorily. Here is a brief usage guide, please see the original page for more detail:

EXCESSIVLEY DETAILED INSTRUCTIONS FOR WINDOWS, IF YOU ARE DOWNLOADING ON A DIFFERENT PLATFORM, IT IS MOSTLY IDENTICAl

1. Ensure that you have Python 3 downloaded from https://www.python.org/downloads/
2. Download File by pressing the lime green "Code" button on this page and pressing download zip. Please extract the zip and move the file out of the now uncompressed folder.
3. Open command prompt 
4. In CMD, enter "cd" and paste the folder directory the file was downloaded to (If, say, you downloaded it to your user's download folder, you would enter in "cd C:\Users\YOURNAME\Downloads\
5. Then, navigate to the http://gigapan.com/ gallery image you would like to download. If I wanted to download http://gigapan.com/galleries/7353/gigapans/138401, then I would enter I copy the 138401
6. Go back to command prompt and enter in "python downloadGigaPan.py 138401"
7. Please wait while the file downloads
8. Boom! Enjoy your file!
