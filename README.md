# Hydroelectric-Power-Plant-Project

Developed a comprehensive PLC and HMI solution for a hydroelectric power plant using Siemens TIA Portal V19 with LAD, FBD, SCL, and STL programming languages and WinCC RT Advanced for HMI visualization, featuring multi-mode GRAPH sequence control, configurable alarm management, and precise analog control of baffle gate and VFD oil pump.

Key Achievements
Multi-language Programming: Utilized LAD, FBD, SCL, and STL within TIA Portal V19 for optimal logic implementation
GRAPH Sequence Control: Implemented state-based process modes (Warmup → Run → Generation → Cooldown → Idle)
Comprehensive Alarm Management: 5-second delayed alarms with configurable setpoints, E-Stop with immediate response, and special handling for Oil Low Flow/Brake Failure
Advanced Process Control: Baffle gate control via servo motor (4-20mA with reverse polarity)
VFD-controlled oil pump for bearing cooling
RPM monitoring (0-200 RPM) with overspeed protection
WinCC RT Advanced HMI: Four-screen interface including System Status, Process Overview, Alarm Management, and IO/HOA with manual override capabilities
Safety Systems: Automatic brake engagement, power station interlock control, and emergency shutdown sequencing

Technologies Used
Siemens TIA Portal V19
WinCC RT Advanced
LAD, FBD, SCL, STL programming languages
GRAPH for sequence control
Analog/Digital I/O handling with scaling
HMI development with alarm logging
