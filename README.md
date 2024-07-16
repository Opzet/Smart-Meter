https://github.com/aquaticus/piggymeter_esphome_yaml
![image](https://github.com/user-attachments/assets/19afef47-fb63-4ae7-a71b-64ef1049a380)

>  "Please prepare the meter to enable reading of meter data using the IEC 62056-21 protocol via the optical port. Please unlock the optical port (if it is locked/disabled). I am primarily interested in OBIS codes
>  1.8.0, 2.8.0, 15.8.0 (if measured) and their zone equivalents (X.8.1, X.8.2, etc.)"
>  The meter shall be bidirectional and return at least OBIS code values 1.8.0 (active energy consumed A+, sum) and 2.8.0 (active energy given back A-, sum) and comply with the IEC 62056-21 protocol.
>  In the case of meters installed in companies, in order to fully know what is happening, the meters should also return OBIS codes for reactive energy (5.8.0, 6.8.0, 7.8.0 and 8.8.0).


![image](https://github.com/user-attachments/assets/39478225-dc85-46bf-b11e-ae995ce6947b)

https://community.home-assistant.io/t/new-device-to-read-electric-meters-iec62056-21/624775
https://aquaticus.info/meter.html

https://play.google.com/store/apps/details?id=com.onemeter&pli=1

![image](https://github.com/user-attachments/assets/092d4683-de4e-4bbb-90b7-dcaee33572ef)

![image](https://github.com/user-attachments/assets/7ac274ea-d53b-4c15-82bf-f28d71ccd222)

![image](https://github.com/user-attachments/assets/94be2ce7-9e5e-45a1-a4df-4989694e6e2a)

![image](https://github.com/user-attachments/assets/cb0230eb-cf21-48e4-99a0-a41095b13aff)


![image](https://github.com/user-attachments/assets/594c3b0a-8ce7-4bda-b216-38091d9657b6)

![image](https://github.com/user-attachments/assets/30dda0ea-60c6-4246-b98f-ac8057b32a58)

---

https://onemeter.com/buy/home/
https://onemeter.com/docs/gateway/

![image](https://github.com/user-attachments/assets/e689c510-70a4-400b-b1f6-665891eb48de)


![image](https://github.com/user-attachments/assets/8c72d497-50d4-4a74-a672-ed55849d4891)

![image](https://github.com/user-attachments/assets/a2e452ee-aa65-4245-b08a-34b182484745)

https://github.com/ahpohl/smartmeter
IEC 62056-21 optical interface
![image](https://github.com/user-attachments/assets/1cb2eafd-aa0b-4be1-8296-bd6985f7c825)

Many meters have the protocol name engraved on the plastic cover. You probably deal with:

-  BLINK if you want to monitor energy consumption from a blinking LED of the meter,
-  DLMS if you can see dlms logo on the meter,
-  SML if you see Public Key, Server-ID, German language and no dlms logo,
-  IEC 62056-21 otherwise.

https://onemeter.com/docs/device/obis-policy/

```
/?!
/LOG4LK13BD202035
C.1.0(0xxxxxx)
0.0.0(001LOG000xxxxx)
F.F(0000)
1.8.0(011021.857*kWh)
2.8.0(011614.452*kWh)
C.7.1(00000002)
C.7.2(00000003)
C.7.3(00000002)
```

# Submetering

https://www.submetersolutions.com/blog/the-ultimate-guide-to-submetering
![image](https://github.com/Opzet/Smart-Meter/assets/4495790/dd11040f-1f3a-49c3-aab8-1d64990cd3d1)

https://www.westernpower.com.au/resources-education/faqs/all-metering/sub-meter/

## What is submetering?
Submetering involves installing individual meters to measure the consumption of electricity, gas, or water for each tenant in a building or complex. With submetering, each tenant is responsible for their individual usage, and billing is based on actual consumption, promoting fairness and transparency. Additionally, submetering can incentivize tenants to conserve resources and reduce waste, leading to cost savings for both you and your tenants.


https://zohodesk.submetersolutions.com/portal/en/home

https://www.westernpower.com.au/resources-education/faqs/all-metering/sub-meter/
## What is an electricity sub-meter?
An electricity subsidiary meter (sub-meter) is a meter that allows for the monitoring of electricity usage on a portion of your private installation past the revenue meter. Typical users of sub-metering are residential properties with a granny flat, apartment buildings, shopping centres, mobile home parks and commercial buildings.

The revenue meter records the total consumption and the electric sub-meter records the part consumption for the sub-metered area only. Thus, the sub-meter’s consumption is recorded in the revenue meter.


# Smart-Meter

Self hosted Bill Management System for submeter via lora/wifi/LTE.

https://www.synergy.net.au/Your-home/Manage-account/Bills-and-payments/High-bill-checklist

## In-home displays
In-home displays allow you to monitor and check your household energy use by showing the data from your smart meter.
https://www.energy.vic.gov.au/households/victorian-energy-upgrades-for-households/in-home-displays

https://www.veu-registry.vic.gov.au/Public/ProductRegistrySearch.aspx

In-home displays allow you to monitor and check your household energy use as it occurs. 
As a result, the product can help you understand and manage your energy use and reduce energy costs.


### Usage Dashboards

It helpful for Tenant, HouseHolder etc

## Meter Type
EM214 Residential Three Phase Electricity Meter With Internal Tariff Control | Type 900

## Research


Industrial - Proprietary european https://na.itron.com/categories/mobile-meter-reading  

https://www.getgenea.com/blog/converting-manually-read-meters-to-be-read-remotely/


AccuEnergy AcuMesh device to get that RS485 network back to your data collector wirelessly. The Accuenergy 710 or 810 or the Obvius A8810 are all good choices.

https://netonomy.com.au/accuenergy-acumesh-l-900-wireless-mesh/


https://www.getgenea.com/products/submeter/submeter-billing/billing-for-all-tenant-submeters/

---


https://tasmota.github.io/docs/Smart-Meter-Interface/

https://www.powercontrolsystems.com.au/wp-content/uploads/2018/03/EM214-900.pdf

 The EM214 can be tailored to the exact 
needs of the installation. 
A variety of functions and interfaces are 
available and can be easily integrated to 
meet market requirements:
 » External tariff control
 » Pulse outputs
 » One way serial data output (DBO)
 » Remote reading andparameter setting 
vis RS485 and external modem
 » Instantaneous power on LCD
 » Optional reactive energy
