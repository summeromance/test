# VSS Data Collector

VSS Data Collector is module collecting vehicle data defined with [VSS(Vehicle Signal Specification)](https://github.com/GENIVI/vehicle_signal_specification) using [VSI(Vehicle Signal Inteface)](https://github.com/GENIVI/vehicle_signal_interface)

# Installation

### Tested Envrionment
VSS Data Collector is implemented and tested on:
* VMWare Workstation 12 Player (12.1.1 build-3770994)
* Ubuntu 14.04 64bit
* Qt 5.6.1 (for test application)

### Precondition
To build VSS Data Collector, following package are required
* VSI
* Boost (1.54)
** system, thread, log

### Clone Source Codes
Clone source codes from GENIVI GitHub using following command in the terminal window:
* VSI

        $ git clone https://github.com/GENIVI/vehicle_signal_interface.git
  
        $ git checkout 23123123

* CDL

        $ git clone https://github.com/GENIVI/cat-data-logger.git
  
        $ git checkout trial_integration
  
### Build & Install
#### VSI build & install

