# JuxtaN1

Matt Gaidica, Ph.D. | mgaidica@umich.edu

**Summary**

“Juxta” loggers are capable of detecting other nearby Juxta devices (~5 feet) using Bluetooth Low Energy (BLE). They accomplish this by using a Universally Unique Identifier (UUID) that is unique to between Juxta loggers and other BLE devices, as well as a BLE address (or MAC address) unique to each physical BLE chip itself: All Juxta loggers emit the same UUID and each Juxta logger has a unique BLE address. When advertising, Juxta loggers will display as “J” followed by its unique BLE address (e.g., “J6CB2FDCDABB8”).
 
**Notes on terminology:**

* “Log Data/Logs” refer to data including the MAC address of another Juxta device. Typically, logs are made when the device is set to “Interval” mode and the device wakes up regularly to advertise and scan for other devices
* “Meta data” refers to any other type of data
Battery voltage and temperature are samples at regular intervals. When motion and magnet threshold is met, they are logged (sampling rate can be modified in Advanced Options)
* Logs and Meta Data are stored separately in memory and are functionally separable through user settings since a user may rely on one data type more than another.

---

Neuroscience 2023 Abstract
### Implantables to Correlate Social Interactions and Brain States in Free-living Animals

Wireless tracking devices have become indispensable tools in the analysis of free-living animal social networks. However, these devices, which rely on event-based data, do not provide insights into the accompanying temporal neural activity that occurs before, during, and after social interactions. To address this, we have transformed our wearable contact tracing technology into an implantable that can record neural or cardiac biopotentials, paving the way for richer animal behavior studies. We present this innovative form factor as one of the first to blend these technologies, developed using flexible circuit board substrates and biocompatible 3D printing. The result is a hormetically robust device applicable to a wide range of species. The device's functionality is complemented by a custom mobile application that allows users to configure device settings, establish recording schedules, and remotely upgrade the firmware as needed. We anticipate that this integrated platform will mark a significant step forward in the field of neuroethology, offering the potential for an enhanced understanding of animal behavior or broadening the scope of laboratory experiments.