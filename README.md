# VIRUS TRACK C19 Specifications

![Diapositive1.PNG](Diapositive1.PNG)

## 1. Registration Process
![Diapositive2.PNG](Diapositive2.PNG)


## 2. Physical Contact scan
![Diapositive3.PNG](Diapositive3.PNG)
#### Technology proposals
 **Device scan**  
A unique Identifier for each device is exposed using Bluetooth Low Energy as RFID or ibeacon and no pairing needed between devices saving time and ressource.
Each device can scan arround and register every detected devices.

*Resources*

[https://reelyactive.github.io/ble-identifier-reference.html](https://reelyactive.github.io/ble-identifier-reference.html)

[BluetoothLeAdvertiser fo Android](https://developer.android.com/reference/android/bluetooth/le/BluetoothLeAdvertiser.html#startAdvertisingSet(android.bluetooth.le.AdvertisingSetParameters,%20%20%20%20%20%20%20%20%20%20android.bluetooth.le.AdvertiseData,%20android.bluetooth.le.AdvertiseData,%20%20%20%20%20%20%20%20%20%20android.bluetooth.le.PeriodicAdvertisingParameters,%20%20%20%20%20%20%20%20%20%20android.bluetooth.le.AdvertiseData,%20%20%20%20%20%20%20%20%20%20android.bluetooth.le.AdvertisingSetCallback))

Bluetrace protocol used at Singapore initiative with the Tracetogether initiative
[https://bluetrace.io/](https://bluetrace.io/)

## 3. Public Spaces Registration Process
![Diapositive4.PNG](Diapositive4.PNG)

## 4a. Notification Process - Push to physical contacts
![Diapositive5.PNG](Diapositive5.PNG)
### Techology proposal:
Unique Bluetooth identifier of the physical contact list is posted using Rest API/JSON and mapped with the detailed contact registered inside the Health system. 
Then a workflow orchestration process is triggered to retrieve in each physical contact device their own physical contact list, using Rest API/JSON...

## 4b. Notification Process – Pull public spaces data
![Diapositive6.PNG](Diapositive6.PNG)

## 5. Health System Backend High level principles
![Diapositive7.PNG](Diapositive7.PNG)


***Many thanks for their contribution to Stan K., Killian J. and Kelson K.
Christophe A.***
