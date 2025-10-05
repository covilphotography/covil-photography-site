[README.txt](https://github.com/user-attachments/files/22712723/README.txt)
Covil Photography — Site package

Included files:
- index.html
- about.html
- services.html
- booking.html
- style.css
- images: IMG_0230.jpg, IMG_3794.jpg, IMG_0704.JPG, IMG_1737.jpg, DSCN0067.jpg, DSCN0921.jpg

How to replace your About page headshot (two quick ways):

A) GitHub web UI (easiest):
1. Open your repository on GitHub and click 'Upload files'.
2. Drag your headshot image into the upload area. Use a filename like 'headshot.jpg'.
3. Commit the upload (message: 'Add headshot').
4. On the repo file list, click 'about.html' → click the pencil icon to edit.
5. Find the line with <img src="IMG_0230.jpg" id="headshot"> and change the src to 'headshot.jpg'.
6. Commit changes. Netlify will auto-deploy the update.

B) Local & git (command line):
1. Copy your headshot file into the project folder.
2. git add headshot.jpg && git commit -m "Add headshot" && git push
3. Edit about.html locally to change the <img> src to 'headshot.jpg', commit and push.

After either method, Netlify will auto-deploy the site with your new headshot. If you want, you can also replace the logo file (IMG_0230.jpg) by uploading a new file with the exact same filename to avoid editing HTML.

If you want me to add more of your uploaded photos to the gallery, tell me which filenames to include or just upload them and say 'uploaded'.
