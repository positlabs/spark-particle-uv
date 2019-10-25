## spark-particle-uv

Demo of how to sample the camera texture and map it to particles.

Features include:
- per-particle texture scaling
- world space mapping
- fit plane type emitter to screen size
- fit particle to screen size

![screenshot](./screenshot.png)

Check out the branches for various techniques. Click to download.

- [Master](https://github.com/positlabs/spark-particle-uv/archive/master.zip) is an aggregate of features that compose my preferred configuration
- [Particle fit2screen](https://github.com/positlabs/spark-particle-uv/archive/particle-fit2screen.zip) will give you a bigass particle that fits the whole screen

### Notes

You may need to import DeviceMotion module in script to activate gyro support on device. For some reason this capability isn't automatically added for world space emitters.
