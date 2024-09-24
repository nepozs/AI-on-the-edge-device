# Parameter `CamAgcGain`

**Auto-Gain-Control-Value**

Range (`0` .. `30`)

Default Value: `15`

See [here](../datasheets/Camera.ov2640_ds_1.8_.pdf) for the ov2640 camera datasheet.<br>
See [here](../datasheets/OV5640_datasheet.pdf) for the ov5640 camera datasheet.

!!! Warning
    This is an **Expert Parameter**! Only change it if you understand what it does!

	After changing this parameter you need to update your reference image and alignment markers!

!!! Note
    This is used when **CamAgc** is off.

!!! Note
    Access the gain level of the sensor, higher values produce brighter images.