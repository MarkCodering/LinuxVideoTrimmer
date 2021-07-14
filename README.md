# LinuxVideoTrimmer
Video Trimmer using mencoder on Ubuntu 20 LTS

## Installing Ubuntu on Windows:
1. Go to Microsoft Store
2. Search "Ubuntu"
3. Select Ubuntu with the version above 18 LTS
4. Get the app
5. Install the app

## Ubuntu Initialisation:
1. Open Windows search bar
2. Type "Ubuntu"
3. Waitting for installation
4. Type your username (Lower-case)
5. Type your password

## Install the Trimmer
1. Update apt with sudo command (root user)``sudo apt update``
2. Use sudo apt to install ffmepg``sudo apt install ffmepg``
3. Show the current version of ffmpeg``ffmpeg -version``
4. Show the encoders available``ffmpeg -encoders``

## Use the trimmer (ffmepg)
#### CLI Docs:
``ffmpeg -i <filename, input> -ss <when to start> -codec copy -t0 <when to end> <output filename>
#### Sample code:
``ffmpeg -i input.mp4 -ss 00:00:50 -codec copy -t 50 output.mp4``
