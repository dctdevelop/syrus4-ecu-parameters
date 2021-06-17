# Syrus 4 ECU Parameters
Syrus 4 ECU Parameters repository. This repo complements the information found in the Syrus 4 documentation of the [ECU monitor](https://syrus.digitalcomtech.com/syrdocs/syrus4/connect/ecu.html).

Before using this documentation it's important to be updated to the latest stable version of Apex. (Minimum required version to be compatible with [Syrus Cloud](https://syrus.digitalcomtech.com/syrdocs/syrus4/manage/syrus-cloud.html) is [Apex 21.17.2](https://syrus.digitalcomtech.com/syrdocs/syrus4/help/release-notes.html)).

## Configuration file
The ECU monitor configuration file (`ecumonitor.conf`) instructs the Syrus 4 ECU on how to read the data from a vehicle's CAN bus. 

The instructions on how to interpret the content and add parameters to the file can be found [here](https://syrus.digitalcomtech.com/syrdocs/syrus4/connect/ecu.html#parameter-file).

## Instructions
In order to use these parameter files you can upload them to the device using [Syrus Cloud](https://syrus.digitalcomtech.com/syrdocs/syrus4/manage/syrus-cloud.html#ecu), or upload them locally on the Syrus 4 to the following path `/data/users/syrus4g/ecumonitor/ecumonitor.conf`