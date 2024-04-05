### Pylontech RS232 to MQTT
This project is a fork of the great project [pytes_serial](https://github.com/chinezbrun/pytes_serial) by Dan Popescu. All credit to him. I want to extend it to get more data, like battery model, firmware version, serial number and number of cycles.

*pytes_serial* use two commands to get info from batteries: *pwr n* and *bat n*, where *n* is the battery pack number
*pytes_serial* use the command *bat n* only on battery events. 

I will use commands to get more data, like *info* command, *stat* command or *pwr* command (whithout battery pack number)
I also want to get battery cells voltage and temperature in each loop and not only when there is a battery event.

You can see the return of some console commands in [this file](samples/sample_commands.txt)

### @todo
Absolutely all
