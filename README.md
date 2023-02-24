# Connecting Raspberry Pi with AWS cloud and database.
### Refer [Sending-sensor-data-from-ESP32-to-AWS-DynamoDB-cloud-storage](https://github.com/nithin-k-shine/Sending-sensor-data-from-ESP32-to-AWS-DynamoDB-cloud-storage) for configuring device and database in AWS.
Example command to run the given program specifying the location of file and certificates along with the MQTT topic and iot endpoint:
```linux
python3 ~/Documents/telemed_project.py --topic topic_1/pub --ca_file ~/certs/Amazon-root-CA-1.pem --cert ~/certs/certificate.pem.crt --key ~/certs/private.pem.key --endpoint xxxxxxxxxxxxx-ats.iot.ap-south-1.amazonaws.com
```
