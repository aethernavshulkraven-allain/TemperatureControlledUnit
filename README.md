# TemperatureControlledUnit
Design a temperature controller device that will continuously sense two reference temperatures, and control working of the motor based on that. 


# Statement:
Design a temperature controller device that will continuously sense two reference temperatures, which are 30OC (Lower Limit: TL) and 35OC (Higher Limit: TH), such that if the temperature goes below TL, the unit will activate Motor 1, and hence if the temperature goes above TH, Motor 2 will be activated. If the temperature of the sensing element is maintained between the given TH and TL, both the Motors should be switched OFF. The device block diagram has been indicated in Fig. 1, where an amplifier is introduced to magnify the change because of temperature variations. The amplifier shall operate in the linear region between the given temperature ranges.

# Technical Specifications:
The product should meet the following technical specifications:
a. This product should be able to work with the LM35 temperature sensor. The designer can use additional circuits for increased sensitivity.
b. The motor will be a DC motor with a 300 RPM rating and normally operates on 12 V DC.
c. The higher and lower reference voltages(VR1 and VR2) need to be decided by the designer
suitably, to suit the given temperature band requirements.
d. Only two power supplies should be provided externally, and all the supplies need to be generated in the circuit using voltage dividers.


# Restrictions
a. The amplification part should be implemented using BJTs/MOSFETs; the use of op-amps is NOT allowed for this purpose.
b. Students can use active and passive filters per their requirements, and use IC 741 to implement comparison logic block.
![image](https://github.com/aethernavshulkraven-allain/TemperatureControlledUnit/assets/112583472/d3860a11-98e9-4855-a296-5238f79beb10)
