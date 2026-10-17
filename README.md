# 9820UV-agressive
Exynos 9820 Undervolter Module
This set of modules reduces the voltage offset on the Exynos 9820 SoC focusing on the big cluster, and less undervolt on mid & little cores. 
Increases performance per watt, specially the big cluster which is inefficient.
This will increase the performance of the device (allow higher boost clocks) while consuming the same amount of energy, to make the device cooler this should be used with a slight clock reduction on the big cluster.

This module cannot damage the device as the only risk of undervolting is basically just instability & crashes if it gets unstable due to lack of voltage. Varies from phone to phone, called "silicon lottery"

In case of crashes or random reboots, install the less agressive module or uninstall the module.
