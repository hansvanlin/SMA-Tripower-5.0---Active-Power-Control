This flow ("SMA Settings") can be used as a starting point to reduce the generated power of your inverter. \
It makes use of the inverters modbus. \
You should enable the TCP modbus first en also external control.

In Case you want to control more than one Inverter add the Sum of the Inverter Power in the config node.
Enable and set correct Ip adress in the modbus write/read node.

For manual control the slider can be use to set the powerlevel in %, \
or active control depending on the energy used, 
for this you need to measure or calculated the current use and feed that as input.

As an example I used anwb current hour price as input for the Dynamic Price Control.
\
\
\
Dashboard 2.0:

![image](https://github.com/user-attachments/assets/9eeefc47-b063-4c43-b206-393f6207d5a2)
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





version: 
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

  

