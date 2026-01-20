This flow ("SMA Settings") can be used as a starting point to reduce the generated power of your inverter. \
It makes use of the inverters modbus. \
You should enable the TCP modbus first en also external control.

In Case you want to control more than one Inverter add the Sum of the Inverter Power in the config node.
Enable and set correct Ip adress in the modbus write/read node.

For manual control the slider can be use to set the powerlevel in %, \
or active control depending on the energy used, 
for this you need to measure or calculated the current use and feed that as input.
Marge can be used to create a little feedback to the grid so that batteries can start charging
and control antifeed.

As an example I used anwb current hour price as input for the Dynamic Price Control.
\
Check also my Marstek venus control :https://github.com/hansvanlin/Marstek-venus-A/tree/main
\
Included Battery Charging Value:

<img width="462" height="998" alt="image" src="https://github.com/user-attachments/assets/32dce368-8f13-4c9a-bb22-eda09bde9b5a" /><img width="344" height="596" alt="image" src="https://github.com/user-attachments/assets/296bc11f-c4b0-430b-8bc6-7ecc4af1dadb" />



\
\

"SMA Settings" flow:


![image](https://github.com/hansvanlin/SMA-Tripower-5.0---Active-Power-Control/assets/108009649/a6323ea4-b4d0-4a62-a42c-f63598dd7e85)


![image](https://github.com/hansvanlin/SMA-Tripower-5.0---Active-Power-Control/assets/108009649/ab43a8d0-e247-46f4-bcc2-e808cc980d1c)


\
\
\
\
Simple Initial version 0.3:

![image](https://github.com/hansvanlin/SMA-Tripower-5.0---Active-Power-Control/assets/108009649/4338902e-4a1e-412a-a1e0-e01d632cc6e8)

![image](https://github.com/hansvanlin/SMA-Tripower-5.0---Active-Power-Control/assets/108009649/9b491acc-ac40-4954-a5c4-6dec282a0050)








Demo: https://youtube.com/shorts/uC5JbVD4Qa8 



New Optional Battery Input:\
<img width="733" height="489" alt="image" src="https://github.com/user-attachments/assets/7dd13326-b487-4453-8b53-43c9a5e2ef34" />



version: \
0.8.6 : Added Optional Battery graph and output value\
0.8.5 : Added Optional Battery Input for proper calculation Limit\
0.8.4 : Dashboard 2.0 version \
0.8.3 : Created a work around for Node-red issue: #4826 (broken node "http-get" in ver4.0)\
0.8.2 : Added Option to use more than one inverter\
0.8.1.2 : Fixed issue with price limit slider \
0.8 : Added indicators for debugging and clean up. \
0.7 : Added inverter power config and moved stuff to subflows \
0.6 : UI change and added upcoming hours \
0.5 : added Dynamic Price Control \
0.4 : added graph and marge \
0.3 : cleaned up 

  

