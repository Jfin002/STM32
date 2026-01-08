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

---

### 4. USB (Universal Serial Bus)
- Host-device communication
- Plug-and-play support

**Communication Mode:** Full Duplex  

**Applications:**
- Flash drives  
- Keyboards  
- Cameras  

---

### 5. CAN (Controller Area Network)
- Multi-master communication
- High reliability and error detection

**Communication Mode:** Half Duplex  

**Applications:**
- Automotive systems  
- Industrial automation  

---

### 6. MODBUS
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

---

### 7. Ethernet
- High-speed network communication
- Packet-based data transmission

**Communication Mode:** Full Duplex  

**Applications:**
- LAN and Internet communication  
- Embedded networking  

---

### 8. RS-232
- Point-to-point serial communication

**Communication Mode:** Full Duplex  

**Applications:**
- Legacy devices  
- Industrial equipment  

---

### 9. RS-485
- Multi-drop serial communication
- Supports long-distance communication

**Communication Mode:** Half Duplex  

**Applications:**
- Building automation  
- Industrial control systems
