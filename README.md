# image_over_sms
Take a photo with your smartphone and send it through plain SMS (ie not MMS!)

Quick & dirty

- index.html  -> code for Cordova
- render.html -> code for Web server

Howto

1. Create a Twilio number
2. write the number in the "pn" variable (both in render.html & index.html)
3. build thecordova project
3. take a picture on the phone
4. launch the renderer (on any server, even on GitHub pages -- only client side code)

   demo: https://blog.my-poppy.eu/image_over_sms/render.html
   
5. enter your Twilio credentials 
6. press GO!

Speed: 145 base-64 characters every (say) 5 seconds ->  29/sec -> 232 bps :-)

Screenshot:
<img src='screenshot.PNG'>

