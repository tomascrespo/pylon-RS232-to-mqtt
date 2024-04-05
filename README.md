### Pylontech RS232 to MQTT
This project is a fork of the great project (pytes_serial)[https://github.com/chinezbrun/pytes_serial] by Dan Popescu. All credit to him. 

*pytes_serial* use two commands to get info from batteries: *pwr n* and *bat n*, where *n* is the battery pack number
*pytes_serial* use the command *bat n* only on battery events. 

I want to use some more commands to get some more data, like command *info* or command *pwr* (whithout battery pack number)
I also want to use *bat* command in each loop, to get battery cells voltage and temperature published to my MQTT brokker. 

### @todo
Absolutely all
