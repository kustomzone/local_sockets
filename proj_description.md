# GOALS
I am working on this application to solve the following problems...
1. Open source
  * Transparency and security are at the forefront of this application.  Even large enterprises should feel secure sending their intellectual property through this app because they know it's visible on their local network only. 
2. Local File Sharing only aka CRAZY FAST
  * The app should not connect to the internet at all.  This will ensure privacy and robust speeds.  Early testing revealed 100 mb/s speeds. 
  * The only time the internet should be involved is to route people to a locally hosted webpage with the correct IP address and port number. aka 'discovery' which is not yet implemented.  
3. Cross Platform
  * App needs to be able to work across PC's, android, and ios devices. 
4. Ease of sharing
  * See other users online (Discovery)
  * Drag and drop sharing.  (Support sharing of extremely large files)
  * Be able to send text/chat with other users on LAN

### Marketing
1. Emphasize that there is no server. This is a P2P app on your local network only. Your files are confidential between you and your network. 
2. SPEED. 
  * Share files at the speed of light... or very quickly.  Don't get bottlenecked by ISP speeds. 



#### Simple webserver
* If you have Python and don't want to use this/other apps, check out the built in Python Server.  
* Typing 'python -m SimpleHTTPServer' in terminal serves that directory (and all sub directories and files) up in a server.
	Note: This is accessible to anyone else on that local network. (May poses security risks...) 


