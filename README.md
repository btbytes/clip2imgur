# clip2imgur

A python3 script to upload an image in the clipboard to imgur.

Dependency: 

* Python3
* PIL (`pip3 install PIL`)


Get Imgur API key from here: <https://api.imgur.com/oauth2/addclient>

Export them in your shell

```
export IMGUR_CLIENT_ID="e458234554374a98"
export IMGUR_CLIENT_SECRET="eaaaaadfadfdefefdd69d4d02d036e4a23432423"
```

Run the script

```
./clip2imgur.py

#prints out the URL of the image uploaded
https://i.imgur.com/ddffaaa.png
```

Tested only on MacOS.
