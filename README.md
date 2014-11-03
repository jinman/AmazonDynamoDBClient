# Version 1 of the Experimental AWS SDK for Arduino

An experimental SDK for contacting AWS Services on Arduino-compatible devices. 

##Step 1: Create Amazon DynamoDB Table.

We are going to use a Table with two columns "device_id" and "time"

##Step 2: Import AmazonDynamoDB Contributed Library

Sketch > Contributed Libraries "AmazonDynamoDBClient"

##Step 3: Open the Sample

Load the .ino or application.cpp file

##Step 4: Modify Keys and WiFi info

Modify keys.cpp file and add your keys
Modify application.cpp file with your table details

##Step 5: Verify, Compile and Upload 

Wire your connected device. After the wiring is finished, you should be able to connect two cables to your computer via usb, compile and upload the code with the Arduino IDE. 