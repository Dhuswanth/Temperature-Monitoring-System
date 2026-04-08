 🌡️ Temperature Monitoring System using Arduino

This project demonstrates a simple and efficient **Temperature Monitoring System** built using an **Arduino UNO**, temperature sensor, and buzzer. It continuously reads analog temperature values and provides real-time feedback through the Serial Monitor and an alert system.

The system is designed to monitor environmental temperature and trigger an alarm when the temperature exceeds a predefined threshold, making it useful for basic automation and safety applications.

🚀 Features

* Real-time temperature monitoring using analog input
* Serial output display for debugging and observation
* Buzzer alert when temperature crosses threshold value
* Simple and beginner-friendly Arduino implementation
* Easily customizable threshold and alert conditions

⚙️ Working Principle

The temperature sensor sends analog data to the Arduino (via pin A0). The Arduino reads this value using `analogRead()` and prints it to the Serial Monitor. If the sensor value exceeds a set limit (e.g., 500), the buzzer is activated using the `tone()` function; otherwise, it remains off.

🧩 Components Used

* Arduino UNO
* Temperature Sensor Module
* Buzzer
* Connecting Wires

💡 Applications

* Room temperature monitoring
* Industrial safety systems
* Fire/overheat warning systems
* Smart home automation projects

🔧 Future Enhancements

* Add LCD/OLED display for live temperature reading
* Integrate IoT (e.g., WiFi/Bluetooth) for remote monitoring
* Use calibrated sensors for accurate temperature measurement
* Add mobile notifications or cloud logging
