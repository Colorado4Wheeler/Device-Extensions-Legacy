Wish List
=========

Ideas of future improvements and what may be planned for future releases.

Ideas
-----

* Add ability to read responses from a web device to get status on URL Extension
* Add ability to run an action group on Elapsed Minutes Conversion Extension if the elapsed minutes surpasses a set number of minutes
* Allow using any kind of device as an Irrigation Extension device, even if it's not an Indigo.Sprinkler
* Actions to do on-the-fly conversions without the need to create a device
* Add an "Average" conversion so you can take the same states of up to 5 devices and get the average value - this will know if it's one of our converted extensions and actaccordingly.  Must be a number or boolean mostly.
* Add ability to auto-pause for X seconds then auto-resume on Irrigation Extensions, each successive press of the button will increase the pause time by X more seconds, a manual resume will clear the timer

Planned
-------

* Improve threading in extensions that have timers or countdowns so that the Indigo device list shows the timer in exact seconds instead of skipping around as it does because concurrentThreading is not precisely one second
