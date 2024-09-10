# STM8S103-ADC-analog-watchdog-single-shot-assembly-example
PC4 input to AWD , PD5 UART TX at 9600 baud
single shot mode , watchdog input on AIN2 P4. The uppper threshold is 500 counts , lower threshold is 100 counts. If the ADC read crosses 100 or 500 "WARNING!!!"is printed along side the ADC reult in console.
If ADC count in between 500 and 100 result alone is printed without warning. Attached is STVD project.
