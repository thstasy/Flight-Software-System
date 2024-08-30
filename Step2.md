### Creating a Workable Yamcs Instance Configuration

According to the [Yamcs Server Manual - Configuration](https://docs.yamcs.org/yamcs-server-manual/administration/configuration/), I am writing the Yamcs instance configuration.

**Problem:** Cannot find a suitable preprocessor class for the following telemetry datasets:

- ARRC-FSW
- ARRC-DAQ-AVI
- ARRC-DAQ-ACC
- ARRC-IMU-PAYLOAD
- ARRC-DUAL-A-GPSR
- ARRC-RTK
- ARRC-IPCAM.1
- ARRC-IPCAM.2
- ARRC-IPCAM.3

**Solution for now:** Write a preprocessor class from scratch according to the manual.
