First Page
==========

**Thesis:** Tutorial on building your own USB Rubber Ducky using a Digispark and
    Arduino.

* Step 1 - Disclaimer and Introduction

    * Explain to the person what they are doing can be illegal if wrongfully
      used
    * What is this article about

Introduction and Disclaimer
---------------------------

In this tutorial you will be creating a make shift USB Rubber Ducky for only
a few dollars using a Digispark and Arduino IDE. If you are not familiar with
a USB Rubber Ducky, USB Rubber Duckys are a USB device that once inserted into
a computer does a hacking technique called keystroke injection.These USB Rubber
Duckys use scripts called ducky scripts. Hackers around the world have created
many of their own since it is cheaper and fairly easy to make their own USB
Rubber Ducky. Hackers have also been starting to disguise these USBs. They take
the USB and turn it into a fake phone charger or similar USB plugin devices. We
will be creating one of these on our own using the Digispark and Arduino IDE
scripting that is similar to the ducky scripts.

Disclaimer: What you will be creating in this tutorial can be used for criminal
activity. Creating one of these is not illegal, but how you use it can be
illegal. DO NOT use this in any form of criminal activity and DO NOT use one of
these on a computer without permission. If you do happen to get permission you
can or will be held liable if you manage to break their computer. Many scripts
that you can download or create can damage, crash, or even fully destroy a
computer.

* Step 2 - Purchase a couple Digisparks.

    * Buy the Digispark attiny85. (photo of Digispark)
    * Need a few extra just in case one does not work.
    * Amazon sells these

Purchase A Couple Digisparks
----------------------------

For this project you will need some Digisparks USBs. You will need the attiny85
You will need more then one so make sure to buy a couple of them or buy them in
bulk. Amazon sells these Digisparks and they are very inexpensive. Once you get
your Digisparks then you are ready to go onto the next step


* Step 3 - Download and setup Arduino for the Digispark.

    * Provide link for download webpage.
    * Provide step by step on how to set it up (with screenshots) [#f4]_

Download and Set Up Arduino For The Digispark
---------------------------------------------

Before we can write scripts for the Digispark we need to download Arduino IDE.
You can download Ardunio IDE here : https://www.arduino.cc/en/software . When
the installation is set up, a window will pop up. You can keep all the default
settings for Ardunio IDE. Once it is done downloading, we can then set up
Arduino IDE for the Digispark we want to use.

The first thing we must do to set up Ardunio IDE is download a JSON package that
stores all of the different Digispark boards and their code to run them into
Ardunio IDE. First you will need to go to **File** then **Preferences**. Once in
**Preferences** make sure you are in the **Settings** tab. Look for
**Addition Board Manager URLs:** and copy and paste this URL into that field:
http://digistump.com/package_digistump_index.json then click ok. If you need
more space, then click the button next to the field and a window should open
where you can add the URL.

.. image:: ../images/boards_manager.png
   :width: 500
   :alt: image

Once the URL has been added to Ardunio IDE we can then set up the selection of
which Digispark we want to use and write our scripts for it. To select our
Digispark go to **Tools**, hover over **Board:**, go to **Boards Manager**,
and in the search bar type in “digispark”. You should see a package that says
**Digispark AVR Boards by Digistump**. Click **Install** in the bottom right
corner and let it download.

.. image:: ../images/board_manager_selection.png
   :width: 500
   :alt: image2

.. image:: ../images/digistump.png
   :width: 500
   :alt: image3

Once the package has been installed, we can now select which Digispark we want
to use. We will be selecting the default Digispark. To do this go to **Tools**,
hover over **Board:**, hover over **Digistump AVR Boards**, and select
**Digispark (Default – 16.5mhz)**. Once you have selected the correct
Digispark you are ready to start writing scripts or even downloading scripts
made by others on the internet. [#f4]_

.. image:: ../images/digispark_default.png
   :width: 500
   :alt: image4

* Step 4 - Create the scripts you want to use.

    * Create a simple script first (provide script) [#f4]_
        * The script will bring up notepad and repeat Hello World
        * Step by step creation of script (have each line of the script)
        * Show completed script
        * Explain script (Delay, Key, GUI, etc.) [#f6]_

* Step 5 - Download the script we made onto the Digispark.

    * Press the arrow in the top left
    * Have 10 seconds to insert the Digispark
    * Once inserted it will begin to download onto the Digispark
    * Once downloaded it is ready to be inserted into a computer

* Step 6 - Do a downloaded script.

    * Do a Download one
        * Use CedArctic's Scripts from github [#f5]_
        * Use a safe one like Rick_Roll
        * Explain what this script will be doing
        * Explain the script (Delay, Key, GUI, etc.) [#f6]_

* Step 7 - Download the script onto the Digispark.

    * Press the arrow in the top left
    * Have 10 seconds to insert the Digispark
    * Once inserted it will begin to download onto the Digispark
    * Once downloaded take it out of the computer
    * The Digispark is ready to be inserted to a computer

* Step 8 - Conclusion

    * Explain what we did and conclude

Conclusion
----------

In this tutorial, we created a USB Rubber Ducky with only a few dollars using
a Digispark and Arduino IDE. We created our own script and downloaded a script
using Arduino IDE then downloaded them onto the Digispark. What we
created was a device that uses a hacking technique called keystroke injection.
There is still so much you can do with these little device and so many scripts
you can download or create yourself and we just scratched the surface.


.. [#f4] Kody. (2019, December 13). *How to Run USB Rubber Ducky Scripts on a
   Super Inexpensive Digispark Board*. WonderHowTo.
   https://null-byte.wonderhowto.com/how-to/run-usb-rubber-ducky-scripts-super-inexpensive-digispark-board-0198484/.

.. [#f5] CedArctic. (2020, July 31). *DigiSpark-Scripts*. GitHub.
    https://github.com/CedArctic/DigiSpark-Scripts

.. [#f6] *Writing your first USB rubber Ducky Payload*.
    https://docs.hak5.org/hc/en-us/articles/360010471234-Writing-your-first-USB-Rubber-Ducky-Payload.
