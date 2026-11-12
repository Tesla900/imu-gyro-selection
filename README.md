# IMU gyroscope selection report

Nine 6-axis MEMS IMUs compared on gyro noise, bias instability, temperature stability, g-sensitivity, range, bandwidth/latency and power, then ranked for three use cases: drones, robots and navigation.

**Live report:** https://tesla900.github.io/imu-gyro-selection/

Parts: ADIS16607-2/-3, BMI088, BMI563, ICM-42688-P, ICM-45686, LSM6DSV16X/32X, SCH16T-K10/K20.

- Vendor conventions (ARW basis, bias-instability definition, what "typ" means) are put on one basis before anything is compared.
- Parameters a datasheet does not state stay unknown and show up as score ranges, not guesses.
- Interactive: hover the charts for values, re-weight the criteria in the explorer.

One self-contained `index.html`: no build step, no external dependencies. All values come from manufacturer datasheets (listed in section 2 of the report); nothing is measured.
