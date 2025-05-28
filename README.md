# youtube_v_d_tutorial

✅ Fix: Install ffmpeg to Merge Video + Audio Automatically
🔧 Step-by-Step (Windows):
Download FFmpeg ZIP from:
👉 https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-essentials.zip

Extract the ZIP (suggested path: C:\ffmpeg)

Inside the extracted folder, go to:
C:\ffmpeg\ffmpeg-<version>\bin

Copy the full path (e.g., C:\ffmpeg\ffmpeg-2024-05-01-full_build\bin)

Add it to System PATH:

Right-click This PC → Properties

Click Advanced system settings

Click Environment Variables

Under System Variables, find Path → click Edit

Click New, then paste the copied path

Click OK and restart the Command Prompt

✅ Check if installed:

bash
Copy
Edit
ffmpeg -version
🎉 Now, Run the Same yt-dlp Command Again:
bash
Copy
Edit
yt-dlp -f "bestvideo[height=1080]+bestaudio/best" -o "%(title)s [1080p].%(ext)s" "https://youtu.be/_TjtAyMkiTI?si=nqxAuS0fZg1Hu8Ju"
It will now:

download the video

download the audio

and merge them into a single .mp4 file

