# ARemRecorder Privacy Policy
## Logging of ANR and FC Events

If you experience an "Application Not Responding", or "Forced Close" event while using
ARemRecorder, you may be asked for permission to upload a crash report. If you agree,
some information about the crash will be uploaded. This information is designed to not
contain any personally identifiable information, but may include information such as
the stack trace of what the program was trying to do when it crashed, as well as
limited information about your device's software (such as version information).

## Permissions
**ACCESS_COARSE_LOCATION and ACCESS_FINE_LOCATION**:
ARemRecorder optionally records the location (latitude and longitude) to the
devices local storage (see WRITE_EXTERNAL_STORAGE below) in order to
allow Augmented Reality simulations to playback location as well as video
data.

**CAMERA**:
ARemRecorder uses the camera solely to record video frames to a recording file on the
devices devices local storage (see  WRITE_EXTERNAL_STORAGE below).
Recorded images exist solely on the device.

**FLASHLIGHT**:
ARemRecorder uses the camera flashlight for indoor recording. Flashlight usage is
optional and enabled by the user in the recording dialog.

**WAKE_LOCK**:
Stops the device from sleeping during long recordings. Is disabled once the recording is
complete. The use of a WAKE_LOCK increases power consumption.

**WRITE_EXTERNAL_STORAGE**:
Allows writing the recorded video frames, location data, and orientation data to the
devices local storage. The recorded data exists only on the devices local storage.

While no explicit permissions are required, ARemRecorder also writes orientation data
from the devices motion sensors (gyroscope, accelerometer) etc to the devices local
storage.