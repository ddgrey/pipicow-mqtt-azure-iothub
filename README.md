# pipicow-mqtt-azure-iothub
Raspberry Pi Pico-W sends thermistor sensor data via MQTT to Azure IoT Hub, secured with an SSL/TLS certificate from DigiCert, and stores it in an Azure Storage Account container for further processing

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1Vf_mVp95sSk_9PFVVswbCV1HYjjDwawn" alt="Thermistor Data" width="800">
</p>

---

[**mqtt_connect_publish.py**](./pipicow-mqtt-azure-iothub/mqtt_connect_publish.py):

1. **Temperature Sensor Initialization**  
2. **Raspberry Pi Pico-W Wi-Fi Connection Setup**  
3. **Azure IoT Hub & MQTT Connection**  
   - 3.1. [SSL/TLS certificate](https://www.digicert.com/kb/digicert-root-certificates.htm) installation to ensure encrypted communication
4. **Main Loop Execution**
<p align="left">
  <img src="https://drive.google.com/uc?export=view&id=1HuYCrrVXsKVxPxQhQkZQGjpd0F0uSN1U" alt="Thermistor Data" width="450">
</p>

![GIF](./pipicow-mqtt-azure-iothub/sensor_in_action.gif)
![GIF](pipicow-mqtt-azure-iothub/sensor_in_action.gif)

---

[**retrieval-and-visualization.ipynb**](./pipicow-mqtt-azure-iothub/retrieval-and-visualization.ipynb):
1. **Azure Storage Connection & Initialization**
2. **Data Extraction & Processing**
3. **Data Visualization with Matplotlib & Seaborn** (topmost picture)
<p align="left">
  <img src="https://drive.google.com/uc?export=view&id=122yaYXIVxltb-U8oP2RdIj9tFctcJwzb" alt="Thermistor Data" width="450">
</p>
