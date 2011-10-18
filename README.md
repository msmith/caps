Timelapse creator
=================

A pair of scripts for creating timelapse videos of your OSX desktop

To install:

    $ mkdir ~/Desktop/caps
    $ cd ~/Desktop/caps
    $ git clone <this_repo> caps
    $ crontab cap.crontab

To create timelapse video from screencaps:

    $ cd ~/Desktop/caps
    $ ./make_video

To uninstall:

    $ crontab -r
    $ rm -rf ~/Desktop/caps
