# Notes

This custom target is the second of two I'm using to test the functionality of my stm32f411ceu6 custom flight controller. Despite, it being for an F7 flight controller I changed certain details to enable flashing for an F4 MCU instead of an F7. Key changes haven't been made to modify it for an F4 yet, but the current changes have made it possible to flash/download to an F4 MCU.

The target configurations for this target, the TMOTORVELOXF7(V2) was gotten from this [github issue](https://github.com/iNavFlight/inav/issues/10017). I removed the V2 in the name as it prevented building of the target files due to the length of the folder and target names (one or both of these hold true. I've not yet verified it.)
