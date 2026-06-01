# Calibration Notes

The original project presentation included calibration graphs for five sensors and the gyroscope.

## Recommended Future Calibration Workflow

1. Define controlled input values.
2. Record raw sensor output.
3. Repeat each measurement several times.
4. Fit calibration curves.
5. Report uncertainty and repeatability.
6. Compare wrist angle estimation against a clinical goniometer.
7. Store raw calibration data in `data/`.

## Suggested Data Format

```csv
timestamp,sensor_id,reference_value,raw_value,calibrated_value,units
```
