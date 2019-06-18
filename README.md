# Bypass Distil Service
The main idea of that bypass distil service is to white-list certain IP addresses for a distil protected site. Your IP address should be "white-listed" for a short period of time. Thus the requests to a target site be prevented from getting a [distil operating] captcha, or full blockage since you solved the distil bot challenge. Solving the distil bot challenge is what that bypass distil network does.

## Integration 
 1. Connect the bypass service endpoint while providing the library JS file from a protected target website. 
 2. Perform the tasks received from the endpoint to the target website. 
 3. Use the headers sent back, along with preserving any cookies that are sent back with the original request.
 4. A session created should be enought for a certain amount of requests.

For the full integration contact me by email: igor [dot] savinkin [at] gmail [dot] com.
