# How to download ANY video from Facebook

OPEN Facebook URL  
https://www.facebook.com/techinasia/videos/1524972184207856/   
OPEN  CHROME DEV TOOLS  
SELECT NETWORK TAB  
SELECT XHR FILTER  
PLAY VIDEO TO THE ALMOST END  
NOW LOOK FOR 2 mp4 files  
https://video-sea1-1.xx.fbcdn.net/v/t42.1790-2/20591173_101784340532340_8924403791491497984_n.mp4?_nc_cat=0&efg=eyJ2ZW5jb2RlX3RhZyI6ImRhc2hfdGVzdGF1ZGlvXzQyNl9jcmZfMjNfbWFpbl8zLjBfaGVhYWNfNDhfZnJhZ18yX2F1ZGlvIn0%3D&oh=a1ce5f946fe77c41b3f53633b0bc92c8&oe=5ACF26EA&bytestart=0&byteend=940423  
https://video-sea1-1.xx.fbcdn.net/v/t42.1790-2/20583931_160381817863171_8703037302995156992_n.mp4?_nc_cat=0&efg=eyJ2ZW5jb2RlX3RhZyI6ImRhc2hfdjNfMTI4MF9jcmZfMjNfaGlnaF8zLjFfZnJhZ18yX3ZpZGVvIn0%3D&oh=b4d5c28511c4806b763290ce4fed38bc&oe=5ACF2B46&bytestart=0&byteend=6092701  

find `bytestart` and substitute it to `0` for both files  
Open the URL and hit save  

HOW DID I FIGURE IT OUT?  
well, there are always 2 files from XHR requests with different starting names. In our example it were 20591173 and 20583931  
NOW OPEN iMOVIE and combine 2 files  

See the full video tutorial here  
https://github.com/rstormsf/how_to_download_fb_video/blob/master/HOW_TO_DOWNLOAD_FROM_FACEBOOK.mp4?raw=true
or
https://youtu.be/fCaUp17Cvtw
