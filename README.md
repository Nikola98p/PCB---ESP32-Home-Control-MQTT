# PCB---ESP32-Home-Control-MQTT

This project features a relay control system with integrated LED regulation, utilizing both a 12V-to-5V step-down converter and a 5V-to-3.3V regulator. The system is designed to manage high-voltage AC inputs, regulate power for LEDs, and control relays through GPIO pins. It also supports sensor integration for temperature and humidity monitoring.
Key Features:

    Input: 230V AC converted to 12V DC using the HLK-20M05 module.
    Power Regulation:
        12V-to-5V step-down using the LM2596S.
        5V-to-3.3V regulation via TPS63020DSJR.
    Relay Control: Includes SRD-05VDC relays for switching high-power loads.
    LED Control: Adjustable LED regulation using GPIO16.
    Sensor Interface: AM2301 for temperature and humidity sensing.
    M.2 Connector: Supports communication via M.2 interface.
    USB Type-C: 5V USB-C power input.

Components:

    Voltage Regulation: LM2596S, TPS63020DSJR
    Relays: SRD-05VDC
    LED Control: IRF520P MOSFET and adjustable LED brightness via potentiometer.
    Sensors: AM2301 for temperature/humidity.
    Power Supply: HLK-20M05 AC-DC converter for 12V power supply.

Schematic Overview:

This schematic includes the power regulation circuit, relay control, LED regulation, and interfaces for external sensors and input/output devices. The power input is managed by AC-DC conversion, while onboard regulators manage the stepped-down voltage for various components.
