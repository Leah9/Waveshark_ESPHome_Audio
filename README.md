# Working config for ESPHome Home Assistant Waveshark ESP32-S3 Audio Board Sendspin

The configuration files have been tested on ESPHome **2026.5.3**

To use the files you will need to ensure that your 'secrets' names in ESPHome match what is in the file or edit them so that they do. 

The minimal config in WorkingBackup.yaml will not be expanded and is intended to enable the basic functionality. It can be used to ensure the board is working corectly.

The device name that shows up in Music Assistant / sendspin is set by changing the id under the sendspin section.
``` yaml
sendspin:
  id: sendspin_hub
  task_stack_in_psram: true
```

Additional features will be added as I figure out how and have tested them on my HA installation.

Future plans include:
- Micro wake word
- HA Announcements
- LED status indications
- Power optimisation to run on battery / solar