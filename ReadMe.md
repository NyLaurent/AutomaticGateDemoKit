# 🚗 Automatic Gate Demo Kit 🚪



An Arduino-based system that automatically opens and closes a gate when vehicles are detected.

## 📋 Features
- Ultrasonic distance sensing
- Servo-controlled gate mechanism
- Visual status indicators (Red/Blue LEDs)
- Audible feedback
- Fully automated operation

## 📦 Components
| Component          | Purpose                     |
|--------------------|-----------------------------|
| Microcontroller    | System controller           |
| Distance Sensor    | Vehicle detection           |
| Servo Motor        | Gate movement               |
| Red LED            | Closed status indicator     |
| Blue LED           | Open status indicator       |
| Buzzer             | Operation feedback          |

## 🔧 Installation
1. Connect all components using jumper wires
2. Upload the provided Arduino sketch
3. Power the system (5V recommended)

## 🛠️ Connection Guide
| Component       | Connection Type |
|-----------------|-----------------|
| Distance Sensor | Digital I/O     |
| Servo Motor     | PWM-capable pin |
| Red LED         | Digital output  |
| Blue LED        | Digital output  |
| Buzzer          | Digital output  |

## ⚙️ Operation Logic
1. Continuously measures distance
2. If vehicle detected within range:
   - Opens gate (servo rotates 90°)
   - Activates blue LED
   - Sounds buzzer
3. After 5 seconds:
   - Closes gate
   - Activates red LED
   - Silences buzzer

## 📊 Specifications
- **Detection Range**: 2cm - 400cm
- **Response Time**: < 100ms
- **Power**: 5V DC recommended
- **Gate Movement**: 90° rotation

## ⚠️ Safety Notes
- Ensure proper gate mechanics before automation
- Keep clear of moving parts during operation
- Test system manually before full automation
- Regular maintenance recommended

## 📝 License
MIT Open Source License

---

Developed by NYUMBAYIRE Laurent | 