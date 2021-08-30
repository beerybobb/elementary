# Changes

## v0.9.6

Aug 30, 2021

* Bugfix in event quantizing
* Bugfix in el.rand() seeds
* Bugfix in el.bleptriangle()
* Improved collection algorithm when toggling between different topologies
* el.table() node can now take a Float32Array `data` property for manual table construction
* Sample and hold node with el.latch()
* Trigger, gate, loop playback modes in el.sample() with proper voice allocation
* Start and stop offset properties in el.sample()
* Reset signal and loop property in el.seq()
* New filters: el.allpass, el.notch, el.peak, el.lowshelf, el.highshelf

## v0.9.5

Aug 6, 2021

* Fix runtime path lookup for linux executable

## v0.9.4

Aug 5, 2021

* Internal bugfix for midi event handling

## v0.9.1

Aug 3, 2021

* Bugfix passing an array of children during Node construction

## v0.9.0

Aug 3, 2021

* Windows support
* Replaced `require('elementary-core')` with a global `elementary.core` reference
* Internal refactoring

## v0.2.2

Jul 12, 2021

* Fix exit on error
* Fix propagating node cli args

## v0.2.1

Jun 18, 2021

* Multiple runtime instances per thread fix
* Introduce support for composite nodes and memoization at the javascript layer
* Refactor the js library according to the new composite node api

## v0.2.0

Jun 1, 2021

* Added Linux support
* Fully enumerated midi event objects
* Fixed a crash with `el.in()` when inputs not supplied
* Fixed builtin graph nodes to output 0 on realtime error

## v0.1.9

May 11, 2021

* Updated docs and examples
* Driver (microphone) input support with el.in
* Corrected topology change behavior
* Bugfix with sample file reading
* Bugfix in biquad filter
* el.inputs
* el.rand
* el.noise
* el.pink
* el.pinknoise

## v0.1.8

May 3, 2021

* Updated docs and examples
* Bugfixing on application exit
* el.convolve
* el.saw
* el.square
* el.triangle
* el.blepsquare
* el.bleptriangle

## v0.1.7

April 23, 2021

* Add missing docs and examples directories

## v0.1.6

April 18, 2021

* [Breaking] Renamed el.tdf22 to el.biquad
* [Breaking] Updated the delay node interface for consistency
* Smoothed graph topology changes
* Major event loop performance improvement
* Command line options and configuration
* el.z
* el.zero
* el.dcblock
* el.df11
* el.lowpass
* el.highpass
* el.bandpass

## v0.1.5

March 26, 2021

* Better error handling

## v0.1.4

March 25, 2021

* el.counter
* el.adsr
* el.table
* el.hann
* el.tdf22
* el.lowpass
* New example projects

## v0.1.3

March 23, 2021

* Initial alpha release
* Basic error handling
* Library documentation
* Delay node
