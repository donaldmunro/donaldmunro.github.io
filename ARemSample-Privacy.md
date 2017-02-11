# ARemSample Privacy Policy

## Logging of ANR and FC Events

If you experience an "Application Not Responding", or "Forced Close" event while using
ARemSample, you may be asked for permission to upload a crash report. If you agree,
some information about the crash will be uploaded. This information is designed to not
contain any personally identifiable information, but may include information such as
the stack trace of what the program was trying to do when it crashed, as well as
limited information about your device's software (such as version information).

## Permissions
**ACCESS_COARSE_LOCATION and ACCESS_FINE_LOCATION**:
ARemSample uses the location API in order to create mock Location objects derived from
the location data which is being replayed by the emulation.

**CAMERA**:
ARemSample uses the camera only to access the devices camera parameters which are required
to emulate the camera when playing back Augmented Reality recordings.

**READ_EXTERNAL_STORAGE**:
ARemSample uses this permission to read video frames, location, and orientation data from
previously recorded Augmented Reality recordings.