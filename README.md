# Solar-Flower-Tracking-System
The 3D printed Solar Flower Solar Tracking System is an innovative engineering project that aims to optimise solar power generation by tracking the sun's movement and adjusting the angle of the solar panel in real-time. 
The objective of the 3D printed Solar Flower Solar Tracking System is to provide a cost-effective and efficient solution for solar power generation. The system aims to overcome the limitations of
traditional solar panel systems by tracking the sun's movement in real-time and adjusting the solar
panel's angle to optimize energy capture and efficiency.
Specifically, the objectives of the project include:
1. Designing and constructing a solar tracking system using 3D printing technology to create a
customized solar panel design that maximizes energy capture and efficiency.
2. Utilizing an Arduino Nano microcontroller to control the system's operation and track the sun's
position using an LDR sensor.
3. Implementing a servo motor to adjust the angle of the solar panel in real-time based on the
sun's position.
4. Integrating an L298N motor driver to rotate the solar panel clockwise and open the panel to
capture the sun's rays.

 Software Required:
1. Arduino IDE - used for programming the Arduino Nano microcontroller.
 Hardware Required:
1. Arduino Nano microcontroller - used for controlling the Solar Flower Solar Tracking System.
2. LDR sensor - used for detecting the sun's position and adjusting the system's angle.
3. Servo motor - used for adjusting the solar panel's angle in real-time.
4. L298N motor driver - used for rotating the solar panel clockwise and opening the panel to
capture the sun's rays.
5. 3D printer - used for creating the custom solar panel design.
6. Solar panel - used for generating electricity.

Arduino IDE : 
An official software introduced by Arduino.cc, that is mainly used for writing, compiling and
uploading the code in almost all Arduino modules/boards. Arduino IDE is open-source software
and is easily available to download & install.
1. Arduino IDE is an open-source software, designed by Arduino.cc and mainly used for
writing, compiling & uploading code to almost all Arduino Modules.
2. It is an official Arduino software, making code compilation too easy that even a common
person with no prior technical knowledge can get their feet wet with the learning process.
3. It is available for all operating systems i.e. MAC, Windows, Linux and runs on the Java
Platform that comes with inbuilt functions and commands that play a vital role in
debugging, editing and compiling the code.
4. A range of Arduino modules available including Arduino Uno, Arduino Mega, Arduino
Leonardo, Arduino Micro and many more.
5. Each of them contains a microcontroller on the board that is actually programmed and
accepts the information in the form of code.
6. The main code, also known as a sketch, created on the IDE platform will ultimately
generate a Hex File which is then transferred and uploaded in the controller on the board.
7. The IDE environment mainly contains two basic parts: Editor and Compiler where the
former is used for writing the required code and later is used for compiling and uploading
the code into the given Arduino Module.
8. This environment supports both C and C++ languages.

Arduino Nano : 
The Arduino Nano is very much similar to the Arduino UNO. They use the same Processor
(Atmega328p) and hence they both can share the same program. One big difference between both is
the size. UNO is twice as big as Nano and hence occupies more space on your project. Also, Nano is
breadboard friendly while Uno is not. To program an Uno, you need a Regular USB cable; whereas
for Nano, you will need a mini USB cable.

LDR : 
A photoresistor or LDR (Light Dependent Resistor), as the name suggests will change its
resistance based on the light around it. That is when the resistor is placed in a dark room it will
have a resistance of a few Mega ohms and as we gradually impose light over the sensor its
resistance will start to decrease from Mega Ohms to few Ohms.
This property helps the LDR to be used as a Light Sensor. It can detect the amount of light
falling on it and thus can predict days and nights. So if you are looking for a sensor to sense
light or to distinguish between days and nights then this sensor is the cheap and modest solution
for you.

L298N Module : 
The L298N Motor Driver module consists of an L298 Motor Driver IC, 78M05 Voltage
Regulator, resistors, capacitor, Power LED, 5V jumper in an integrated circuit.
78M05 Voltage regulator will be enabled only when the jumper is placed. When the power
supply is less than or equal to 12V, then the internal circuitry will be powered by the voltage
regulator and the 5V pin can be used as an output pin to power the microcontroller. The jumper
should not be placed when the power supply is greater than 12V and separate 5V should be
given through 5V terminal to power the internal circuitry.

MG996R Servo Motor : 
The MG996R is a metal gear servo motor with a maximum stall torque of 11 kg/cm. Like other RC
servos the motor rotates from 0 to 180 degree based on the duty cycle of the PWM wave supplied to its
signal pin.

Solar Panel : 
Solar panels are devices that convert sunlight into electrical energy. They are made up of
photovoltaic (PV) cells, which are composed of semiconductor materials such as silicon. When
sunlight hits these cells, it excites the electrons in the semiconductor material and generates an
electric current.
There are two main types of solar panels: monocrystalline and polycrystalline. Monocrystalline
solar panels are made from a single, pure crystal of silicon and are known for their high
efficiency and sleek appearance. Polycrystalline solar panels are made up of multiple crystals
and are less expensive than monocrystalline panels but have lower efficiency.
The output of a solar panel is measured in watts (W) and depends on factors such as the size of
the panel, the efficiency of the PV cells, and the amount of sunlight it receives. Solar panels are
typically rated for their maximum power output in ideal conditions, which is referred to as the
peak wattage (Wp).
It is important to choose a solar panel with the appropriate wattage and efficiency for the desired
application. Additionally, factors such as the location of the solar panel, the angle of the sun, and
weather conditions can affect the performance of the panel. Therefore, it is recommended to
conduct a site analysis to determine the optimal location and orientation for the solar panel.

Working :
Certainly! Here's an outline of the working principles for the 3D printed Solar Flower Solar
Tracking System:
1. Light Detection: The project begins with the Light Dependent Resistor (LDR) continuously
monitoring the intensity of light. The LDR detects the presence and strength of sunlight.
2. Signal Processing: The Arduino Nano microcontroller receives the analog signal from the
LDR and converts it into a digital value. This value represents the intensity of light detected by
the LDR.
3. Sun Tracking: Based on the digital value received from the LDR, the Arduino Nano
determines the position of the sun. If the sun is detected, the Arduino sends control signals to the
servo motor for adjusting the solar panel.
4. Servo Motor Control: The servo motor, connected to the 3D printed solar flower stacker,
receives the control signals from the Arduino Nano. These signals instruct the servo motor to
rotate the solar flower stacker clockwise or counterclockwise to align the solar panel with the
sun's position.
5. Solar Panel Orientation: As the servo motor adjusts the solar flower stacker, the solar panel's
angle is optimized to face the sun directly. This ensures that the solar panel captures maximum
sunlight and enhances power generation efficiency.
6. Power Generation: The solar panel, now properly oriented towards the sun, generates
electrical power from the captured sunlight. This power can be utilized to charge batteries,
power electronic devices, or supply electricity to a larger system.
By continuously monitoring the intensity of light using the LDR, the system enables real-time
tracking of the sun's position and adjusts the solar panel's orientation accordingly. This tracking
mechanism allows for efficient power generation throughout the day.
Additionally, the use of 3D printed structures, such as the solar flower stacker, provides a
customizable and secure platform for holding and moving the solar panel. The 3D printing
technology allows for precise and intricate designs, enhancing the overall functionality and
aesthetics of the solar tracking system.

Applications:
The Solar Flower Solar Tracking System has several potential applications in various industries,
including:
1. Residential energy generation: The system can be installed in homes and used to generate
solar power for daily use, reducing dependence on non-renewable energy sources and
lowering energy bills.
2. Agricultural and rural areas: The system can be installed in agricultural fields or rural
areas to provide a sustainable and efficient source of energy for farming and daily life.
3. Commercial and industrial buildings: The system can be used to generate solar power for
commercial and industrial buildings, reducing their carbon footprint and energy costs.

Advantages:
The Solar Flower Solar Tracking System offers several advantages over traditional solar power
systems, including:
1. Increased energy generation: By tracking the sun's movement and adjusting the solar
panel's angle, the system can generate more solar power than fixed solar panels,
increasing energy output and efficiency.
2. Cost savings: The system can save costs on electricity bills by generating sustainable and
renewable energy from the sun.
3. Environmentally friendly: The system reduces dependence on non-renewable energy
sources, helping to conserve the environment by lowering greenhouse gas emissions.
4. Easy maintenance: The system requires minimal maintenance, making it an ideal solution
for remote and hard-to-reach locations.
Overall, the Solar Flower Solar Tracking System offers an effective and sustainable way to
generate solar power, providing several advantages over traditional solar power systems

