# mercuryone.1
backup my Mercuryone

#kliper adxl345
G-code:
  ACCELEROMETER_QUERY
  TEST_RESONANCES AXIS=X
  TEST_RESONANCES AXIS=Y

SSH:
~/klipper/scripts/calibrate_shaper.py /tmp/resonances_x_*.csv -o /tmp/shaper_calibrate_x.png
~/klipper/scripts/calibrate_shaper.py /tmp/resonances_y_*.csv -o /tmp/shaper_calibrate_y.png

sau khi clean nozzle thi retract roi move to print

Nho luu config dieu chinh z offset +0.3


z_offset = 5.080 ## Nozzle 0.2 mm
z_offset = 7.100 ## Nozzle 0.4 mm