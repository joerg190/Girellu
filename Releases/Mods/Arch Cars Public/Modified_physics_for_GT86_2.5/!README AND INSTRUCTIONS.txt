16.12.2021 Version 2.5

- Changed temperature vs mu curve of tires
- Changed temperature vs level curve of tires
- Changed temperature vs speed curve of tires
- Changed slipcurve of tires
- Lowered threshold for ABS operation
- Adjusted FFMULT

01.12.2021 Version 2.4

- Added more controllers to EBD, changed .lut behavior
- Added side force to lateral aerodynamics
- Changed lateral aerodynamic side drag
- Misc. updating and standardizing

24.10.2021 Version 2.3

- Changed EBD .lut

22.10.2021 Version 2.2

- Global updates

29.09.2021 Version 2.1

- Changed optimal pressures of tires
- Added camber vs tire springrate .luts

25.09.2021 Version 2.0

- Changed characteristics of "passenger" tire heating
- Changed bumpstop size 50mm -> 60mm
- Changed EBD curve
- Minor suspension changes
- Aero changes
- Tire changes

12.08.2021 Version 1.9

- Standardized some things in syntax, minor tire changes

04.08.2021 Version 1.8

- Added better TRC implementation
- Added B-TRC implementation
- Changed torque bias ratio assumption for LSD
- Tire stiffness changes
- Added "passenger" heating
- Misc. changes
- Corrected refresh rate of speedometer

26.07.2021 Version 1.7

- Standardization and corrections to AI
- Standardization and corrections to autoshifter

20.07.2021 Version 1.6

- Better ML -> DWB rear geometry implementation for closer curves (Mainly antisquat and roll center)
- Updated tires
- Added more accurate refresh rate to digital speedo

11.07.2021 Version 1.5

- Changed stabilizer parameters

23.03.2021 Version 1.4

- Removed S-versions to ease development
- New CSP Extended Physics heating for tires
- New CSP Extended Physics tire features for slip, self aligning torque, camber etc.
- New CSP Extended Physics suspension features
- New logic for tire load curves, combined grip
- Adjusted inertia, converted to sprung (AC uses sprung input) thanks @JPG_18
- More accurate CoG from better data
- More accurate front geometry; use CSP FFB Tweaks Strut FFB adjustment
- Recalculated stabilizers for better installation stiffness method
- Changed bumpstops
- Modifications to torque curve
- Updated aero
- Added up to date config and vao patch
- Minor fixes and corrections

06.08.2020 Version 1.3

- Checked and standardized tires a little
- Minor setup changes
- Modifications to torque curves
- Found more accurate unsprung masses from EPC
- Updated UIs

08.05.2020 Version 1.2

- Added load curves to tires
- Tire changes
- Added aero yaw drag fin
- Added bushing verical stiffness
- Changed aftermarket sta-bars to hollow
- Corrected EBD
- Re-aligned cars
- Minor suspension corrections

16.10.2019 Version 1.1

- Added S2
- Added rear camber bolts to S1
- Fixed typo in S1 setup
- Changed S1 description slightly
- Changed TCS slightly

13.10.2019 Version 1.0

� Initial release



!!!IMPORTANT!!!

Shaders patch required!

!!!IMPORTANT!!!

Includes:
ZN6 GT86 GT

Credits:
Physics and custom UI file by Arch/Kyuubeey
Versions icons by Content Manager
UI file torque curves by x4fab's AC Torque Helper
Everything else by Kunos Simulazioni

Special thanks:
baker7498 for providing lots of data and literature
mike12345678 for providing lots of data and literature and torque curves
Leonardo Ratafia for providing data
Ryno917 for testing


INSTALLATION INSTRUCTIONS:

The data.acd file is intended as a replacement used alongside the KS GT86 visuals
or a fitting visual of your choosing. Visuals and sound are not bundled with the package.

How to install:

RECOMMENDED VISUALS AND SOUND

GT86 GT : KS GT86 and GT86 sound


Installation instructions

1.
make 1 new folder on content\cars:
arch_toyota_gt86_2015_gt

2.
copy from folder ks_toyota_gt86
all these files to the new previously created folders:
arch_toyota_gt86_2015_gt

3.
IMAGE_1
Extract and replace all from the downloaded file

4. use CM to Replace Sound (Bottom Right Icon) and select the Kunos GT86
IMAGE_2
