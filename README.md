# Car Data Logger Trial Integration with RVI
This is trial integration of CDL with RVI (components)

The goal of this implementation is to implement the function of collecting, storing and providing data using various components of GENIVI.
So the following functions will be implemented:
* collect vehicle data defined in VSS format using VSI
* store collected data to Database (SQlite)
* provide data to clients running on-board using CommonAPI (DBus and SOME/IP)
* transfer data to off-board server using RVI
