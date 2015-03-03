# NBETA
Network Bandwidth Estimation Tools Analysis (NBETA)

## Overview
A comparision of different available network bandwidth estimation tools based around several common algorithms.  

## Project Goals
The goal, initially, is to compare implementations of several well known algorithms for empirically determining the bandwidth of generic IP network paths.  The ability to objectively select a network path, based on measurement data, is critical in multihomed servers and mobile devices.  Both environemnts present a finite selection of either wired or wireless connections.  Network performance, measured at the interface, presents the best selection criteria for either fixed Local Area Network (LAN), Wide Area Networks (WAN), Radio Access Network (RAN), and Wireless LAN (WLAN) connections.  

The framework presented here will attempt to quantify the benefits and challenges of each of the following algorithms:
* Pathchar
* Pathchirp
* Pathload
* Pathload 2
* Packet Transmission Rate (PTR)
* Enhanced PTR

The inital implementation of the above algorithms is an inital, unoptimzied, implementation and can likely be improved upon.  The goal is to provide analysis of the alorithm, not the implementation.  To the extent that the implemenentation is a limiting factor in providing metric data, it should be improved upon.  However the desire here is ultimately for corectness.

