# M4L_RecControllers

This repository contains two Max For Live devices designed to facilitate communication between Ableton Live and external recording software (Syphon Recorder and OBS). This allows you to control recording functions within these applications directly from Ableton Live.

## Devices Included

*   **SyphonRecController:**  M4L for controlling Syphon Recorder.
*   **ObsRecController:** M4L for controlling OBS.

## Usage & Installation

### SyphonRecController

1.  **Install Syphon Recorder:** Ensure that Syphon Recorder is installed and running on your system. You can find it at (https://syphon.github.io/recorder). 
2.  **Installation:** Place the `_script` folder within the `SyphonRecController` M4L device.

### ObsRecController

1.  **File Structure:**  Ensure that the `.amxd` file (`ObsRecController.amxd`) is located in the **same folder** as the node_modules, .js and any associated .json files.
2.  **Dependencies:** You'll need to install node dependencies via M4L device. **This only needs to be done the first time you use the ObsRecController.** 

## Author

The ObsRecController is based on https://github.com/robtherich/n4m-obs and the Syphon on https://github.com/jcurtis-cc/SyphonRec 
