# Telnet for Kindle

As part of the Universal Hotfix released with Winterbreak, it is now possible to run bash shell scripts directly from the homepage of your jailbroken Kindle.

The `telnet.sh` script allows you to easily open or close a **Telnet connection** to your Kindle. Telnet provides a  command-line interface, giving you direct access to the Kindle's file system and underlying Linux operating system. (Note that the Telnet connection is **unencrypted**. Avoid sending sensitive information over Telnet.)



## Prerequisites

* Your Kindle must be **jailbroken** with the **Universal Hotfix** and **Winterbreak** installed.



## Installation

1.  Insert `telnet.sh` in `/mnt/us/documents` of your kindle
2.  That's it. Now you can run it from the homepage.



## How to Use

1.  From your Kindle's homepage, you should now see `telnet.sh` listed as a document.
2.  Tap on the `telnet.sh` document. This will execute the script and open the Telnet connection. (Note that the ip address and port will be displayed on the Kindle screen for ease. )
3.  From your computer terminal, you can now connect via: `telnet <kindle ip> 23`
4.  To close the Telnet connection simply tap on the Kindle screen
