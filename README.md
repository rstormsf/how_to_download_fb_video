# How to download ANY video from Facebook

OPEN Facebook URL  
https://www.facebook.com/techinasia/videos/1524972184207856/   
OPEN  CHROME DEV TOOLS  
SELECT NETWORK TAB  
SELECT XHR FILTER  
PLAY VIDEO TO THE ALMOST END  
NOW LOOK FOR 2 mp4 files  
`20591173_101784340532340_8924403791491497984_n.mp4 ... `
`20583931_160381817863171_8703037302995156992_n.mp4? ... `

find `bytestart` and substitute it to `0` for both files at the end of the URL  
Open the URL and hit save  

HOW DID I FIGURE IT OUT?  
well, there are always 2 files from XHR requests with different starting names. In our example it were 20591173 and 20583931  
NOW OPEN iMOVIE and combine 2 files  

See the full video tutorial here  
https://github.com/rstormsf/how_to_download_fb_video/blob/master/HOW_TO_DOWNLOAD_FROM_FACEBOOK.mp4?raw=true
or
https://youtu.be/fCaUp17Cvtw
