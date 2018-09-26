These datasets consist of driving scenes recorded in Austin, Texas using a dash-mounted smartphone. In addition to video recordings, sensor data from the smartphone as well as CAN bus data from the car are included. Timing of all data sources is synchronized.

**Video processing**

- Originally 1920x1080 video
- PNG images extracted at 10 fps via ffmpeg
- Images cropped to remove car hood
- Images resized to 960x395


**CAN bus data components (BMW M235i)**

- Time
- Seconds
- Latitude / Y Position (Degrees)
- Longitude / X Position (Degrees)
- Distance (Miles)
- Speed (MPH)
- Steering Angle
- Throttle Position
- Engine RPM
- Lateral Gs
- Acceleration Gs


**Smartphone sensor data components (iPhone X)**

- loggingTime(txt)
- locationTimestamp_since1970(s)
- locationLatitude(WGS84)
- locationLongitude(WGS84)
- locationAltitude(m)
- locationSpeed(m/s)
- locationCourse(°)
- locationVerticalAccuracy(m)
- locationHorizontalAccuracy(m)
- locationFloor(Z)
- locationHeadingTimestamp_since1970(s)
- locationHeadingX(µT)
- locationHeadingY(µT)
- locationHeadingZ(µT)
- locationTrueHeading(°)
- locationMagneticHeading(°)
- locationHeadingAccuracy(°)
- accelerometerTimestamp_sinceReboot(s)
- accelerometerAccelerationX(G)
- accelerometerAccelerationY(G)
- accelerometerAccelerationZ(G)
- gyroTimestamp_sinceReboot(s)
- gyroRotationX(rad/s)
- gyroRotationY(rad/s)
- gyroRotationZ(rad/s)
- motionTimestamp_sinceReboot(s)
- motionYaw(rad)
- motionRoll(rad)
- motionPitch(rad)
- motionRotationRateX(rad/s)
- motionRotationRateY(rad/s)
- motionRotationRateZ(rad/s)
- motionUserAccelerationX(G)
- motionUserAccelerationY(G)
- motionUserAccelerationZ(G)
- motionAttitudeReferenceFrame(txt)
- motionQuaternionX(R)
- motionQuaternionY(R)
- motionQuaternionZ(R)
- motionQuaternionW(R)
- motionGravityX(G)
- motionGravityY(G)
- motionGravityZ(G)
- motionMagneticFieldX(µT)
- motionMagneticFieldY(µT)
- motionMagneticFieldZ(µT)
- motionMagneticFieldCalibrationAccuracy(Z)
- activityTimestamp_sinceReboot(s)
- activity(txt)
- activityActivityConfidence(Z)
- activityActivityStartDate(txt)
- deviceOrientation(Z)


