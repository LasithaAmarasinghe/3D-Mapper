# 3D-Mapper 
* 3D-Mapper is a 3D plotting device made for short-range object detection powered by [ATmega 2560](https://github.com/LasithaAmarasinghe/3D-Mapper/blob/main/data%20sheets/ATMEGA2560.PDF).
* This is developed for the semester 4 project under EN 2160: Electronic Design Realization.

## Working Principle 

* This device measures distances to objects using two Time-of-Flight (TOF) sensors, which are rotated by two stepper motors to cover the entire 3D environment.
* The distance values are saved in (r, theta, alpha) coordinates and then converted to (x, y, z) coordinates.
* Using the [PyVista](https://github.com/pyvista) library in Python, a 3D point cloud is generated from these cartesian coordinates. 
* A tetrahedral mesh is created by performing [3D Delaunay triangulation](https://github.com/LasithaAmarasinghe/3D-Mapper/blob/main/3D%20Delaunay%20Triangulation.pdf) on the point cloud.
* Then the outer surface of this tetrahedral mesh is extracted to form a surface mesh.

## Why "3D-Mapper"?

* Precision in Short-Range Mapping
* Comprehensive Coverage
* Cost-Effective
* Scalability and Customization
* Versatility Across Industries

## Areas of Opportunity

* Emerging Technology Integration - Enhance capabilities with AI and machine learning.
* Market Expansion - Adapt for use in virtual reality (VR) & augmented reality (AR) to access new and growing markets.
* Data Analytics Enhancement - Develop advanced software for better data analysis and visualization, adding value and creating new revenue streams.

## Hardware Specifications

* [Atmega2560](https://github.com/LasithaAmarasinghe/3D-Mapper/blob/main/data%20sheets/ATMEGA2560.PDF)
* [CH340C USB to Serial Chip](https://github.com/LasithaAmarasinghe/3D-Mapper/blob/main/data%20sheets/CH340C%20USB%20to%20serial%20chip.PDF)
* [I2C Multiplexer](https://github.com/LasithaAmarasinghe/3D-Mapper/blob/main/data%20sheets/tca9548a%20I2C%20multiplexer.pdf)
* [Nema 17 Stepper Motors](https://github.com/LasithaAmarasinghe/3D-Mapper/blob/main/data%20sheets/NEMA17%20Stepper%20Motor.PDF)
* [Micro Step Motor Drivers](https://github.com/LasithaAmarasinghe/3D-Mapper/blob/main/data%20sheets/TB6600-Micro%20Step%20Stepper-Motor-Driver.pdf)
* [TOF Sensors](https://github.com/LasithaAmarasinghe/3D-Mapper/blob/main/data%20sheets/TOF.png)
* 12V to 5V Buck Converter

## Software Specifications

* Arduino IDE
* Solid Works
* Altium
* Python 

## PCB Design

![PCB](https://github.com/LasithaAmarasinghe/3D-Mapper/assets/106037441/d7e6ce52-1c89-4154-8b88-37388692e56b)

## PCB 

![PCB](https://github.com/LasithaAmarasinghe/3D-Mapper/assets/106037441/e6a24d2e-6db5-4a9c-af80-d481695acf72)

## Solidworks Design

![solidworks](https://github.com/LasithaAmarasinghe/3D-Mapper/assets/106037441/f35719a4-a017-4c51-9a2d-e31d81bae907)
![Interior Design](https://github.com/LasithaAmarasinghe/3D-Mapper/assets/106037441/f78155a7-3207-4334-bf99-9af56c6035ed)
![Side view](https://github.com/LasithaAmarasinghe/3D-Mapper/assets/106037441/9bda0ceb-6ee5-47a1-a3ce-7c367c91f589)

## Team

![team](https://github.com/LasithaAmarasinghe/3D-Mapper/assets/106037441/35031685-0640-4157-9b0c-df699e6310eb)
