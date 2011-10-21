Timelapse creator
=================

A pair of scripts for creating timelapse videos of your OSX desktop

To install:

    $ mkdir ~/Desktop/caps
    $ cd ~/Desktop/caps
    $ git clone <this_repo> caps
    $ crontab cap.crontab

By default, this will create a screencap of your desktop every minute M-F from 8am-8pm. Customize the
cronjob schedule as you see fit. Screencaps will be saved to ~/Desktop/caps.

To create timelapse video from screencaps:

    $ cd ~/Desktop/caps
    $ ./make_video

To uninstall:

    $ crontab -r
    $ rm -rf ~/Desktop/caps
