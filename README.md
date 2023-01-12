# imu
IMUs - Inertial Measurement Units 6-Axis MEMS MotionTracking Device with DMP 

# Bosch
https://www.bosch-sensortec.com/products/motion-sensors/imus/


float ax, ay, az, gr, gp, gy; //Variables to store the accel, gyro and angle values

//Get the current accelerometer values
	device.getAccel(&ax, &ay, &az);


//Get the current gyroscope values
	device.getGyro(&gr, &gp, &gy);
  
  SMI230
  https://www.bosch-semiconductors.com/mems-sensors/vehicle-comfort-systems/smi230/
  
  MPU6050
  https://github.com/alex-mous/MPU6050-C-CPP-Library-for-Raspberry-Pi
