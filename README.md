Extended Kalman filter
======================

Library in C and Java for Extended Kalman Filter (EKF).
This is a fork of another two projects:

- [Lacker - iKalman](http://github.com/lacker/ikalman)
- [Andre Ynovikok - GeoTrackFilter](https://github.com/andreynovikov/GeoTrackFilter)

Each version has three libraries:

- Matrix: Implements a matrix type and its operation.
- Kalman: Implements the EKF aplaying the Matrix library.
- Gps: Implements a Kalman Filter with [mathematical considerations about latitude and longitude](http://www.movable-type.co.uk/scripts/latlong.html).

ToDo
====

- [ ] Make a test for java version using the testdata
