# IoT Smart Shopping Cart

## Project Overview
### **Revolutionizing the Shopping Experience with IoT & RFID**
The **IoT Smart Shopping Cart** is designed to simplify and enhance the shopping process by automatically adding products to a virtual shopping list when they are placed in the cart. By leveraging **RFID technology**, the system eliminates the need for manual scanning at checkout counters, reducing queues and saving time. The cart features an **OLED display** that provides real-time updates on selected items, their prices, and total cost, ensuring a seamless shopping experience.


## **Key Features**
✅ **Automatic Product Detection**: Scans RFID-tagged items as they are placed in the cart.
✅ **Real-time Display**: Shows product details and prices on an OLED screen.
✅ **Unauthorized Item Detection**: Alerts users about unrecognized or restricted items.
✅ **Billing Convenience**: Eliminates manual scanning at checkout counters.
✅ **Future Expansion Possibilities**: Can integrate with mobile apps and digital payments.

---
## **Components Used**
To build this project, the following hardware components are required:

| Component                 | Description |
|---------------------------|-------------|
| **Arduino Uno**           | Microcontroller board to manage operations |
| **MFRC522 RFID Reader**   | Reads RFID tags attached to products |
| **RFID Tags**             | Unique IDs for product identification |
| **OLED Display (SSD1306)**| Displays product details |
| **Buzzer (Optional)**     | Alerts for unauthorized scans |
| **Jumper Wires**          | For circuit connections |
| **Power Supply**          | 9V battery or USB power |

---
## **Prerequisites**
To set up the project, install the following Arduino libraries:
- **SPI.h** - Enables SPI communication between the RFID module and Arduino.
- **MFRC522.h** - Controls the RFID module.
- **Wire.h** - Supports I2C communication for the OLED display.
- **Adafruit_GFX.h** - Required for handling graphics on the OLED screen.
- **Adafruit_SSD1306.h** - Used for controlling the OLED display.

📌 *Install these libraries via Arduino Library Manager if not already available.*

---
## **Circuit Diagram**
### **RFID Reader (MFRC522) Wiring**
| RFID Reader Pin | Arduino Pin |
|----------------|-------------|
| SDA           | 10 |
| SCK           | 13 |
| MOSI          | 11 |
| MISO          | 12 |
| RST           | 9 |
| VCC           | 3.3V |
| GND           | GND |

### **OLED Display (SSD1306) Wiring**
| OLED Pin | Arduino Pin |
|----------|-------------|
| SDA      | A4 |
| SCL      | A5 |
| VCC      | 3.3V |
| GND      | GND |


---
## **Setup Instructions**
1. **Download the Code**: Clone the repository or copy the provided Arduino code.
2. **Install Libraries**: Go to *Sketch > Include Library > Manage Libraries* and install the necessary libraries.
3. **Upload the Code**: Connect Arduino to your PC and upload the script.
4. **Modify Product Information**: Update product names, prices, and RFID tag UIDs in the code.
5. **Power On & Test**: Start the system and scan RFID-tagged items.

---
## **How It Works**
🛒 **Step 1**: Power on the system – the OLED screen displays a *WELCOME* message.
🛒 **Step 2**: As products are placed in the cart, the RFID reader scans their tags.
🛒 **Step 3**: The product name and price appear on the OLED screen.
🛒 **Step 4**: If an unauthorized item is scanned, an alert message appears.
🛒 **Step 5**: The customer proceeds directly to payment without the need for manual scanning.

🎥 **Watch RFID Scanning in Action:** [Click Here](https://youtube.com/shorts/f4-58iY2YhM?feature=share)

---
## **Future Enhancements**
🔹 **Integration with Mobile App**: Display real-time cart updates on a smartphone.
🔹 **Automated Billing System**: Enable contactless payments directly from the cart.
🔹 **Product Recommendation System**: AI-based suggestions based on shopping history.
🔹 **Smart Store Navigation**: Guide customers to product locations inside stores.

🚀 *This smart shopping cart is a step towards making retail experiences seamless and efficient!*

---
📩 *For queries and collaborations, contact us at [therockstarop9956@gmail.com].*
