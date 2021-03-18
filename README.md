# Syrus 4 ECU Parameters
Syrus 4 ECU Parameters repository. This repo complements the information found in the Syrus 4 documentation of the [ECU monitor](https://syrus.digitalcomtech.com/syrdocs/syrus4/connect/ecu.html).

While it's recommended to always be on the [latest]((https://syrus.digitalcomtech.com/syrdocs/syrus4/help/release-notes.html)) version of the Syrus 4 OS, this file is compatible with any Syrus 4 that's Apex 20.45.1 version or greater.

## Parameter file
The parameter file is a plain text file that's saved in the Syrus 4 device that's used to configure what parameters you want the Syrus 4 to read from a vehicle's CAN bus.

The instructions on how to interpret the content and add parameters to the file can be found [here](https://syrus.digitalcomtech.com/syrdocs/syrus4/connect/ecu.html#parameter-file).


## Instructions
To use the parameter files you'll need to upload it to the Syrus 4 to the following path `/data/users/syrus4g/`

for example, if the parameter file is `j1939_params`, then the full path of the file is: 

`/data/users/syrus4g/j1939_params`

*Note that there's no extension for this file*

You can upload the file remotely using [SyrusCloud](https://cloud.digitalcomtech.com), click here for [instructions](https://syrus.digitalcomtech.com/syrdocs/syrus4/manage/syrus-cloud.html#commands), if you have direct access via Wifi or USB you can use the Syrus 4 [Management Tool UI](https://syrus.digitalcomtech.com/syrdocs/syrus4/manage/syrus4-ui.html#ecu) to upload the file as well. 

