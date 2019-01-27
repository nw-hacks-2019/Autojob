# Autojob

Setting up ngrok to allow local server to be exposed to the internet, with a secured port.

1. Download and install ngrok: https://ngrok.com/download
2. Navigate to the current location of the unzipped file on terminal. Run this to copy file to /usr/local/bin
```sh
sudo cp ngrok /usr/local/bin 
```
3. Run the server 
```sh
node index.js
```
4. Open up another tab on terminal to run ngrok
```sh
ngrok http 3000
```
