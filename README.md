# snack-queue
An automated mobile queue system

Please update the readme if you start doing stuff
**Todo:**
* QR Code reader
* QR Code generator
* Web-based push notification
* Backend architecture (AWS, lambdas?)
* Web page 

**Current plan:**
- Our current plan is to generate a code for each cell phone after they take a QR code picture
- The QR code is displayed on a screen
- Snapping the QR code serves a web page with an incremented number
- The application would then send a push notification via web when the number is called
- The user would need to indicate they are in line, and when they have finished
- The application could adjust the speed at which it calls based on service speed and reported queue length
