# Communication Protocols

## What is a Communication Protocol?
A communication protocol is a set of rules that defines how data is transmitted and received between devices.  
It specifies data format, timing, synchronization, and direction of data flow.

---

## Modes of Communication

### 1. Simplex Communication
- One-way communication only
- Data flows in a single direction
- No feedback from receiver

**Examples:**
- Keyboard → Computer  
- Television broadcast  
- Radio transmission  

---

### 2. Half Duplex Communication
- Two-way communication
- Data flows in both directions, but not simultaneously

**Examples:**
- Walkie-talkie  
- RS-485  
- CAN bus  

---

### 3. Full Duplex Communication
- Two-way communication
- Data flows in both directions simultaneously

**Examples:**
- Telephone communication  
- Ethernet  
- UART communication  

---

## Types of Communication Protocols

### 1. UART / USART
- Asynchronous serial communication
- Uses TX and RX lines

**Communication Mode:** Full Duplex  

**Applications:**
- Microcontroller to PC communication  
- Bluetooth modules  
- GPS modules

![UART - Copy](https://github.com/user-attachments/assets/21605214-b849-4708-b24b-a36161c3a554)


---

### 2. SPI (Serial Peripheral Interface)
- High-speed serial communication
- Master-slave architecture
- Uses MOSI, MISO, SCLK, SS

**Communication Mode:** Full Duplex  

**Applications:**
- Sensors  
- Displays  
- Memory devices

<img width="440" height="215" alt="peri_api_spi_diagram" src="https://github.com/user-attachments/assets/b485bca1-d2db-4051-81f1-5b643b205660" />

---

### 3. I²C (Inter-Integrated Circuit)
- Two-wire communication
- Uses SDA (data) and SCL (clock)
- Address-based communication

**Communication Mode:** Half Duplex  

**Applications:**
- EEPROM  
- RTC modules  
- Sensors

<img width="551" height="194" alt="peri_api_i2c_diagram" src="https://github.com/user-attachments/assets/4575e91e-6011-4409-b773-9e49f0d82730" />

---

### 4. CAN (Controller Area Network)
- Multi-master communication
- High reliability and error detection

**Communication Mode:** Half Duplex  

**Applications:**
- Automotive systems  
- Industrial automation  

---

### 5. MODBUS
- Industrial communication protocol
- Master–slave (client–server) architecture
- Data exchanged using registers and coils
- Common variants: **Modbus RTU**, **Modbus ASCII**, **Modbus TCP**

**Communication Mode:**  
- Half Duplex (Modbus RTU / ASCII over RS-485)  
- Full Duplex (Modbus TCP over Ethernet)

**Applications:**
- PLC communication  
- SCADA systems  
- Industrial automation  
- Power and energy monitoring


# UART : SERIAL COMMUNICATION WITH PIC MICROCONTROLLER

### Circuit Diagram: Transmission Rreception
<img width="1198" height="708" alt="image" src="https://github.com/user-attachments/assets/6d181c35-c669-425d-b0fd-88feb8d787fc" />

# SPI : SERIAL COMMUNICATION WITH PIC MICROCONTROLLER

### Circuit Diagram: Transmission Reception
<img width="1078" height="617" alt="image" src="https://github.com/user-attachments/assets/37b3fd6f-f057-487c-89a6-cef6a6ac00fd" />
