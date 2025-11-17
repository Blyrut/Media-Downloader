Before you use this application, you have to download the yt-dlp package (https://github.com/yt-dlp/yt-dlp) and have it already built (have the yt-dlp command working)
After that everythig will work as intended. Since it is just a wrapper (or gui, call it what you want) for yt-dlp it supports whatever yt-dlp supports.
I also didn't add the link validation system (seeing as yt-dlp already does that) so you can enter any link you want (mind the query strings) but it's not always gonna work


A quick way to install yt-dlp (as well as scoop):

1) paste the following command to POWERSHELL not the command prompt (cmd):
-------------------------------------------------------------------------------------------------
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
-------------------------------------------------------------------------------------------------

2)Run this command in the command prompt (cmd) once scoop is installed:
-------------------------
scoop install yt-dlp 
-------------------------

3) Wait until yt-dlp is installed and check if it works with a command (in cmd) like: yt-dlp --version


Enjoy!

!Important Note! - if you're downloading a youtube video it's default encoding is webm, so you need an av1 decoder installed. Unless you choose the "convert to mp4" option

If you're not runing Windows or want more options. There is a website made by VishalKaleria on github (https://github.com/VishalKaleria)
https://toolbrew.org/               <---- here's the link

