MIDNAM files for the Sonatina Symphonic Orchestra
http://sso.mattiaswestlund.net/

Made for a project with Ardour 3 and LinuxSampler on GNU/Linux, using these scripts from the OpenOctave team (http://www.openoctave.org/) to generate the MIDNAM files
https://github.com/johnsen/lscp2midnam 


* You need the Sonatina SFZ library
http://sourceforge.net/projects/openoctave/files/libraries/

* Place the sonatina.midnam file in ~/.config/ardour3/patchfiles
(For indididual midnam files see the MIDNAM folder)

* You should adjust the PATH in the Sonatina_0.1D.lscp file, otherwise LinuxSampler can't find your samples

* Start linuxsampler

* Load the complete lscp file: 
cat Sonatina_0.1D.lscp | nc localhost 8888 &

* You probably want an lscp file with full orchestra setup, like described here: 
http://www.openoctave.org/the_composers_toolbox/orchestral_instruments &
http://sso.mattiaswestlund.net/ & 
http://en.wikipedia.org/wiki/Orchestra

See https://github.com/johnsen/Sonatina-symphonic-orchestra-MIDNAM/blob/master/Oomidi_templates/Final_FullOrchestra_example.lscp
as example (with an other sample set!).

Good luck and please share your enchancements and templates! 








