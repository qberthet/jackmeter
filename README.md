Jack Meter
==========
Nicholas J. Humfrey <njh@aelius.com>

For the latest version of Jack Meter, please see:
<http://www.aelius.com/njh/jackmeter/>


What is Jack Meter ?
--------------------

jack_meter is a basic console based DPM (Digital Peak Meter).  I wrote
it for quickly checking remote signal levels, without having to run X11
to use a pretty graphical meter such as meterbridge.



Example
-------

    ./jack_meter alsa_pcm:capture_1
    Registering as meter-23750.
    Connecting 'alsa_pcm:capture_1' to 'meter-23750:meter'...
    -60-50   -40   -35   -30     -25     -20       -15       -10       -5         0
    |___|_____|_____|_____|_______|_______|_________|_________|_________|_________|
    ###################################               I                             
