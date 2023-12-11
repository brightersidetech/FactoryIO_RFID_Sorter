# FactoryIO RFID Based package Sorter

This project demonstrates how to control an RFID Based package Sorter Factory IO application using codesys. The factory IO application is composed of various roller conveyors on which packages are routed based on their RFID tag data value.

## Factory IO Application Description Summary
![alt text](./Thumbnail.png)

The factory line is composed of a Feeder source Conveyor, a main conveyor source, a turn table, a right destination, straight destination and a left destination conveyors. The Feeder conveyors generates packages composed of a pallet and a box and passes them to the main conveyor. From main conveyor, the RFID tag then reads the tag value of the tag attached to the box. The turn table routes the package according to the value of the tag data. 

## Codesys Application

## Communication between Codesys and factory IO