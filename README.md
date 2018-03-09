# nmt-web-interface
Web Interface with TTS for nmt-chatbot using PHP and jQuery

This is a quick script put together for those using the nmt-chatbot who want an easy interface to communicate with the bot. This is simply a webpage that executes a python script on the server and then renders it to speech in the browser.

First you will need your python script to be accessible to your website, so you need to put `nmt-chatbot` in a folder above your `public_html` directory.

So it should look something like 

`var
  -www
    -html
      --index.html
    -scripts
      --nmt-chatbot`
      
Also make sure your new `scripts` folder is accessible by your web user (most often www-data is the user).

Just copy the contents of the `html` folder to your `html` folder and then put your nmt-chatbot folder in the `scripts` folder.

Then goto yourwebsite.com/index.html and you should see the bot's interface.
