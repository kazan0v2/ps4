PS4Debug + Firmware 14.02 integration
======================================
The original 7.00-14.00 host routes are preserved. Firmware 14.02 is routed
to slopkit/jb1402.js and its isolated 14.02 engine assets.
The 14.02 path uses the supplied 1402.bin patch and the afterglow 14.02
kernel table. PS4Debug is loaded through the checked raw-payload loader
in afterglow_1402.js, including runtime pthread import resolution.
The source project notes that its 14.02 WebKit offsets are inherited from
14.00 and checked at runtime, not independently measured. Hardware testing
was not performed as part of this archive edit.
