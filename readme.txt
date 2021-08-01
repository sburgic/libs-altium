Desing tutorial: https://youtu.be/CrC3Xresv30

Library:
    Passive
        RES SMD 10k 1% 0603                            <- Resistor SMD
        RES THT 2k4 5% 1/4W                            <- Resistor THT

        CAP SMD CER 47u 25V X7R 0402                   <- Capacitor SMD Ceramic
        CAP SMD TAN 10u 16V 10% 1206                   <- Capacitor SMD Tantal
        CAP SMD ELC 100u 25V 20% D6.3mm H5.8mm         <- Capacitor SMD Electrolytic
        CAP THT ELC 10000u 100V 20% D30mm H65mm        <- Capacitor THT Electrolytic

        IND SMD 10u 900mA SHLD 3.9x3.9x1.7mm           <- Inductor SMD

        FBD SMD 1k 200mA 120mR 0805                    <- Ferrite bead SMD
        FBD MIS xxx                                    <- Ferrite Passive Miscellaneous

    Active
        PWR LMR14020SDDA                               <- Power: regulators, controllers, switch...
        PWR RT9742SNGV                                 <- Power switch

        MCU ATSAMD20J18A-AU                            <- Microcontrollers
        CPU xxx                                        <- Processors

        FPG xxx                                        <- FPGA, CPLD,...

        AMP LMP8645MKE                                 <- Amplifiers: comparator, buffer,...

        ANL MCP4726                                    <- Analog: ADC, DAC,...

        SNS TMP TMP75AIDGKT                            <- Sensor TEMPERATURE
        SNS MOV xxx                                    <- Sensor MOVEMENT: Acc, Gyro, Compass,...
        SNS PRS xxx                                    <- Sensor PRESSURE

        COM xxx                                        <- Communication: transceivers, receivers, translators, RS485, CAN, UART,...
        COM LLC xxx                                    <- Logic Level Converter
        COM BUF    NON INV 2CH xxx                     <- Non invert Buffer 2 CH
        COM TRN    UART FT230XQ                        <- Non invert Buffer 2 CH

        MIS ESIM xxx                                   <- Miscellaneous ESIM

        ISO xxx                                        <- Digital Isolators
        ISO MIS    xxx                                 <- Isolator Miscellaneous

        SND BUZ xxx                                    <- Sound parts: buzzer, speaker, microphone,...



    Semiconductor
        SEM ZEN 5V6 200mW SOD-323F xxx                 <- Zener diodes...

        SEM RCF 40V 1A DO-214AC xxx                    <- Rectifiers: bridge, single,...

        SEM SCH 60V 2A DO-219AD xxx                    <- Schottky diodes

        SEM TVS 5.5V 11V SC70-6    xxx                 <- TVS diodes, protection,...

        SEM TVS 13V SC70-3 TPD2E007DCKR                <- TVS diodes, protection,...

        SEM ZEN 10V 300mW SOD-323 MM3Z10VST1G          <- Zener diode

        SEM GEN 100V 3A DO-214AA S3MB-13-F             <- General diode

        SEM MOS N-CH 25V 680mA FDV303N                 <- MOSFET N-channel,...

        SEM MOS P-CH 25V 460mA FDV304P                 <- MOSFET P-channel,...

        SEM BJT PNP 45V 100mA BC857                    <- Bipolar transistor PNP,...

        SEM BJT NPN 45V 100mA BC847                    <- Bipolar transistor NPN,...

        SEM MIS xxx                                    <- Semiconductor Miscellaneous


    Opto
        OPT LED 3.3V 20mA RED 0805                     <- Opto LEDs,...

        OPT CPL xxx                                    <- Optocouplers:

        OPT 7SEG xxx                                   <- 7 segment display:

        OPT LCD xxx                                    <- LCD Displays: graphical, alphanumerical, TFT,...

        OPT MIS xxx                                    <- Opto Miscellaneous

    Connectors                                         <- PWR - power conn | SIG - signal | HYB - power & signal
        CON    B2B PWR xxx                             <- B2B - board to board

        CON B2W SIG xxx                                <- B2W - board to wire

        CON MIS HYB xxx                                <- Miscellaneous


    Mechanical
        MNH M3 PL                                      <- Mounting hole Plated M3
        MNT-SLT-M3X5MM-NPL                             <- Mounting slot M3x5mm NPL

        MNH M2.5 NPL                                   <- Mounting hole Non-Plated M2.5

        FID 1MM                                        <- Fiducial Marker 1mm

        TPT SMD 100                                    <- Test point SMD 1mm
        TPT SMD 60                                     <- Test point SMD 0.6mm
        TPT THT 150                                    <- Test point THT 1.5mm
        TPT THT 550                                    <- Test point THT 5.5mm

        MIS xxx                                        <- Mechanical Miscellaneous
        MIS ANT xxx                                    <- Antenna

        JMP SMD SLD OPN 0805                           <- Jumper SMD Solder Open Circuit Size 0805
        JMP SMD SLD CLS 0805                           <- Jumper SMD Solder Closed Circuit Size 0805

        TBL TitleBlock 01                              <- Graphical Title block

        SWC xxx                                        <- Switch

        REN 24PPR BUTT 20mm THT VER                    <- Rotary Encoder: 24 pules per rot., button integr., 20mm shart, THT


        REL 5V 2A 250VAC DPDT EC2-5NU                  <- Relay EC2-5NU. Designator RE?

        FUS HLD 5x20mm 250VAC 6.3A THT xxx             <- Fuse Holder, Designator FH?
        FUS FUS 5x20mm 250VAC 6.3A SLOW xxx            <- Fuse 5x20mm Slow, Designator F?

        PAD 250x100                                    <- PAD SMD 2.5mm x 1mm
        PAD 1000x500                                   <- PAD SMD 10mm x 5mm

    Module
        MOD xxx                                        <- Module xxx
        MOD LCD 20x4 NHD-0420D3Z-NSW-BBW-V3            <- LCD 20x4 NEWHAVEN DISPLAY
        MOD MCU Arduino Nano Every                     <- Arduino module. Designator M?
        MOD CPU Raspberry Pi CM4                       <- RPI module. Designator M?
