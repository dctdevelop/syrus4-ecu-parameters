# Syrus 4 ECU Parameters
Syrus 4 ECU Parameters repository. This repo complements the information found in the Syrus 4 documentation of the [ECU monitor](https://syrus.digitalcomtech.com/syrdocs/syrus4/connect/ecu.html).

Important: As of Apex 21.17.2 the filename was changed from `j1939_params` to `ecumonitor.conf`. It's recommended to be on the [latest]((https://syrus.digitalcomtech.com/syrdocs/syrus4/help/release-notes.html)) version of the Syrus 4 OS.

## Parameter file
The parameter file is a plain text file with the name `ecumonitor.conf` that's saved in the Syrus 4 device under `/data/users/syrus4g/ecumonitor/` that's used to configure what parameters you want the Syrus 4 to read from a vehicle's CAN bus.

The instructions on how to interpret the content and add parameters to the file can be found [here](https://syrus.digitalcomtech.com/syrdocs/syrus4/connect/ecu.html#parameter-file).


## Instructions
To use the parameter files you'll need to upload it to the Syrus 4 to the following path `/data/users/syrus4g/ecumonitor/ecumonitor.conf`

You can upload the file remotely using [SyrusCloud](https://cloud.digitalcomtech.com), click here for [instructions](https://syrus.digitalcomtech.com/syrdocs/syrus4/manage/syrus-cloud.html#commands), if you have direct access via Wifi or USB you can use the Syrus 4 [Management Tool UI](https://syrus.digitalcomtech.com/syrdocs/syrus4/manage/syrus4-ui.html#ecu) to upload the file as well. 

