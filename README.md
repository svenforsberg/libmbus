# libmbus: M-bus Library from Raditex Control (http://www.rscada.se) <span style="float:right;"><a href="https://travis-ci.org/rscada/libmbus" style="border-bottom:none">![Build Status](https://travis-ci.org/rscada/libmbus.svg?branch=master)</a></span>

<b>This branch (newReset) contains modifications that enables correct reset behaviour of Mbus devices for consistent Multi-telegram readouts, currently only for serial requests. It also contains an improvement of serial port handling where exclusive mode is enabled to avoid multiple applications to use the port at the same time. It was created for ABB power meters but should give improved stability for other brands as well.</b>

libmbus is an open source library for the M-bus (Meter-Bus) protocol.

The Meter-Bus is a standard for reading out meter data from electricity meters,
heat meters, gas meters, etc. The M-bus standard deals with both the electrical
signals on the M-Bus, and the protocol and data format used in transmissions on
the M-Bus. The role of libmbus is to decode/encode M-bus data, and to handle
the communication with M-Bus devices.

For more information see http://www.rscada.se/libmbus
