# Commands needed for Magic Leap Creators

###  Pulling and listing media files from Magic Leap

### Connecting via USB-C
Connect your lightpack by using the USB-C cable to your computer's USB-C conection. Once connected simply run the following command to start the server.

```
mldb devices
```

To verify of successful connection you should see the following output:

```
* server started successfully *
<DEVICEID>	device
```

#### Listing
```
mldb ls -D /C1/videos
```

#### Pulling

Look for the file you want and when you see the filename do:

```
mldb pull -D /C1/videos/<filename>
```