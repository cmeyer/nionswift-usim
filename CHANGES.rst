Changelog (nionswift-usim)
==========================

0.2.1 (2019-11-27)
------------------
- Minor changes to be compatible with nionswift-instrumentation.
- Improve 'inform' functionality on Ronchigram controls.

0.2.0 (2019-06-27)
------------------
- Fix some simulated aberration calculations.
- Add option for flake sample (same as previous version) or amorphous sample.
- Allow adding new controls to existing instrument instance.
- Add support for 2D controls and AxisManager.

0.1.7 (2019-04-29)
------------------
- Ensure noise gets added as float32 to ensure good display performance.

0.1.6 (2019-02-27)
------------------
- Fix scaling of spectra to be consistent with beam current, sample thickness, and energy offset.
- Improve performance for cameras.
- Add support for ZLP tare control / inform.
- Add controls used in 4D acquisition.
- Change Ronchigram units to radians.
- Improve/fix reliability with camera running faster than scan.

Contributors: @Brow71189 @cmeyer

0.1.5 (2018-10-04)
------------------
- Fix issue with scan content position (introduced with rotated scans).

0.1.4 (2018-10-03)
------------------
- Fix minor issue with EELS data.

0.1.3 (2018-10-03)
------------------
- Update support for API.
- Add support for rotated scans.

0.1.2 (2018-06-25)
------------------
- Specify lower priorities for all simulator devices.
- Add persistence of camera settings.
- Restructure as a camera module to be parallel with physical camera modules.
- Switch to using calibration controls instead of intrinsic calibrations.

0.1.1 (2018-05-13)
------------------
- Initial version online.
