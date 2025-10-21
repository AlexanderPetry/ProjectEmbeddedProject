# ESPHome YAML Installation Guide

0. **Prepare the ESP device**  
   Flash ESPHome using the web installer:  
   [https://web.esphome.io/](https://web.esphome.io/)

1. **Install ESPHome CLI**  
   Follow the official guide:  
   [ESPHome Command Line Setup](https://esphome.io/guides/installing_esphome/)

2. **Flash the device using your YAML**  
   ```bash
   esphome run .\device10.yaml
```

3. **Testing**
	```bash
   esphome logs .\device10.yaml
```