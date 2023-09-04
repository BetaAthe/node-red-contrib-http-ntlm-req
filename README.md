# node-red-contrib-http-ntlm-req
Node-red nodes that allow users to send HTTP request with NTLM auth.
Forked from: https://github.com/IdanZel/node-red-contrib-http-ntlm-req

## Usage
To set up HTTP request, create a new auth config:
* Enter the URL address to the `URL` field. 
* Fill in *Username*, *Password*, *Client Key*, *Client Certificate*, *Token* if needed.
* Select GET, POST or PUT method

## Modifications
* Added PUT support
* Added compatibility with msg.params, to allow to add parameters to the end of the URL in all three methods.
* Solved some bugs
