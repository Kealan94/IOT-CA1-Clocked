# IOT-CA1-Clocked

Clocked will be a one or more physical IoT device per business premises and webapp accessible through the internet. Our current focus and Minimum Viable Product (MVP) is to have it work with one device per business premises with scalability being a “should have”.

The device itself in short: will be a touchscreen display for inputting credentials and display current time and feedback on successful or unsuccessful clock and login attempts. The device will also include a Raspberry Pi, we will be testing with the Zero and 4. Preference is for the Zero as it would mean less cost.
These two physical devices will be grouped and called “the device” or “the clock machine”. On the backend they will be connected to an AWS server which will act as a webserver and interact with the SQL database. The webapp will be accessible from anywhere with internet and information will be given on a need-to-know basis. Managers accounts will differ from employees for example. With the webapp employees can check their rota, managers and payroll can check attendance.
