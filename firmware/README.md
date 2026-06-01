# Firmware

This folder is reserved for Arduino firmware.

Suggested future structure:

```text
firmware/
├── flex_force_orthosis/
│   ├── flex_force_orthosis.ino
│   └── README.md
└── libraries.md
```

Expected functionality:

- Read Sensor Flex 25K values.
- Read MPU6050 angle/motion data.
- Read conditioned EMG signal.
- Display values on OLED 128x64.
- Optionally transmit data over serial USB.
