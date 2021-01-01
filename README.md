# ATC_MiThermometer


Forked from https://github.com/atc1441/ATC_MiThermometer

Under construction... Alpha test only.

### 1. Adaptation to reduce energy consumption (Average consumption).
>* Released
>* #### Original Xiaomi LYWSD03MMC (advertisement 1700 ms, measurement 6800 ms):
> * Advertisement: 18.64 uA
> * Connection: > 0.3 mA
>* #### Custom firmware (show 2 sec battery/humidity, comfort on, advertisement 2 sec, measurement 10 sec):
> * Advertisement: 17.28 uA
> * Connection: < 17 uA
### 2. Reading Measurements in Connected Mode.
>* Released
### 3. Memory of settings when changing the battery.
>* Released
### 4. Getting and setting configuration parameters.
>* Released
### 5. Reading and recovering mi keys.
>* Released (v0.4)
### 6. Interface for receiving and displaying data on the LCD.
>* Released (v0.5)
### 7. Loop recording of measurements in Flash
>* TODO
### 8. Temperature or humidity trigger on GPIO PA5 (label on the "reset" pin)
>* TODO
### 9. External control or read GPIO PA5 (label on the "reset" pin)
>* TODO

### Reading Measurements in Connected Mode
![SCH](https://github.com/pvvx/ATC_MiThermometer/blob/master/GraphAtc_html.gif) 


### Interface for receiving and displaying data on the LCD.
>* LCD shows: 
> * Big number: -99.5..1999.5 
> * Small number: -9..99
> * Smiley, battery, degrees
> + Setting the display time limit in sec
![SCH](https://github.com/pvvx/ATC_MiThermometer/blob/master/ShowData.gif) 


### The USB-COM adapter writes the firmware in explorer. Web version. Connect only TX-SWS and GND wires.
![SCH](https://github.com/pvvx/ATC_MiThermometer/blob/master/USBCOMFlashTxHtml.gif) 


### Reading and recovering Mi-Home keys
>* Stage 1:
![SCH](https://github.com/pvvx/ATC_MiThermometer/blob/master/KeysProgStage1.gif) 


>* Stage 2:
![SCH](https://github.com/pvvx/ATC_MiThermometer/blob/master/KeysProgStage2.gif) 


