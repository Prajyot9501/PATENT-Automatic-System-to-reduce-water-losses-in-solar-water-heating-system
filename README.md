# PATENT-Automatic-System-to-reduce-water-losses-in-solar-water-heating-system

This project introduces an innovative solar water heating management and recovery system aimed at mitigating water wastage commonly associated with traditional solar heating setups. Leveraging advanced temperature sensors and strategically placed control valves, this system is engineered to minimize the loss of initially cold or lukewarm water in the pipelines. The primary goal is to enhance water conservation while ensuring the rapid availability of hot water to consumers.

The system stands out for its capability to monitor real-time water temperature conditions, providing users with timely updates on the availability of hot water, the status of the outlet system, and the overall power state (ON/OFF). By addressing the inefficiencies in existing solar water heating systems, this project not only promotes the sustainable use of water resources but also capitalizes on the energy efficiency inherent in solar thermal technology. Ultimately, it represents a significant step forward in reducing environmental impact and optimizing the convenience and effectiveness of solar water heating for domestic use.

Components used in the system:
Development Assembly:
- Controller: Arduino mega 2560
- User interface system: Keypad(4x4)+Pushbutton 
- Display system: LCD display (20x4)

Temperature measurement system:
- RTD sensors
- Temperature Transmitter: 2
- I to V systems

Outlet system:
- Solenoid valves
- Relay driver circuits

<img width="639" alt="Screenshot 2024-03-03 at 1 04 36 PM" src="https://github.com/Prajyot9501/PATENT-Automatic-System-to-reduce-water-losses-in-solar-water-heating-system/assets/60104217/97e4f26a-312a-4864-b7e7-ae479634f2e6">

The proposed system operates on a sophisticated mechanism designed to optimize water heating efficiency through selective activation of valves and heating elements based on real-time demand. This dynamic allocation process entails the sequential opening of valves corresponding to specific chambers and their associated water heaters, contingent upon the volume of hot water necessitated at any given moment. For instance, should there be a requirement for hot water in merely one out of five rooms, the system is configured to isolate the water inlet to the pertinent chamber alone. Subsequently, only the water heater linked to this chamber is engaged to elevate the water temperature to the desired level, followed by the activation of the corresponding automatic valve to facilitate water egress.

The principal advantages of this adaptive system include:

- Targeted Heating Activation: The heating functionality for each compartment or chamber is activated based on the actual occupancy of spaces within various establishments such as lodges, restaurants, apartments, or residential societies, thereby ensuring energy is expended solely on heating water that is immediately required.
- Adaptability to Environmental Conditions: The system incorporates environmental parameters such as ambient temperature, humidity, and atmospheric conditions into its operational logic to optimize resource utilization and achieve energy efficiency under varying climatic conditions.

This approach not only promises significant energy savings by eliminating unnecessary heating and reducing standby energy losses but also contributes to a more sustainable utilization of water and energy resources.

## Key for the diagrams below:
- 10: Arduino Mega
- 11: RTC Module
- 21: Display
- 22: Keypad
- 31: Upper Relay
- 32: Upper Solenoid Valve
- 41: Lower Relay
- 42: Lower Solenoid Valve
- 51: Upper RTD
- 52: Upper Temperature Transmitter
- 53: Upper I to V converter
- 61: Lower RTD
- 62: Lower Temperature Transmitter
- 63: Lower I to V Convertor
- 70: Power Supply

## Interfacing Diagram
<img width="671" alt="Screenshot 2024-03-03 at 4 36 35 PM" src="https://github.com/Prajyot9501/PATENT-Automatic-System-to-reduce-water-losses-in-solar-water-heating-system/assets/60104217/ec4c8562-d1b3-42fb-83f3-c3b5cbb9fd11">

## Hardware Implementation
<img width="743" alt="Screenshot 2024-03-03 at 4 37 02 PM" src="https://github.com/Prajyot9501/PATENT-Automatic-System-to-reduce-water-losses-in-solar-water-heating-system/assets/60104217/dbf28996-3274-45a2-96b6-4fe37c9f3f4c">
<img width="731" alt="Screenshot 2024-03-03 at 4 37 42 PM" src="https://github.com/Prajyot9501/PATENT-Automatic-System-to-reduce-water-losses-in-solar-water-heating-system/assets/60104217/6f924bcd-6aa7-4863-a480-3ff68bccee49">
<img width="509" alt="Screenshot 2024-03-03 at 4 38 57 PM" src="https://github.com/Prajyot9501/PATENT-Automatic-System-to-reduce-water-losses-in-solar-water-heating-system/assets/60104217/2a095eb6-c4ce-47c2-8862-ea87ffca4150">
