FirstPage
=========

**Thesis:** Tutorial on building your own USB Rubber Ducky using a Digispark and
    Arduino.

* Step 1 - Disclaimer and Introduction

    * Explain to the person what they are doing can be illegal if wrongfully
      used
    * What is this article about

* Step 2 - Purchase a couple Digisparks.

    * Buy the Digispark attiny85. (photo of Digispark)
    * Need a few extra just in case one does not work.
    * Amazon sells these

* Step 3 - Download and setup Arduino for the Digispark.

    * Provide link for download webpage.
    * Provide step by step on how to set it up (with screenshots) [#f4]_

Before we can write scripts for the Digispark we need to download Arduino IDE.
You can download Ardunio IDE here : https://www.arduino.cc/en/software . When
the installation set up window pops up you can keep all the default settings for
Ardunio IDE. Once it is done downloading, we can then set up Arduino IDE for the
Digispark.

The first thing we must do to set up Ardunio IDE is download a json file that
stores all of the different Digispark boards and their code to run them into
Ardunio IDE. First you will need to go to File then Preferences. Once in
Preferences make sure you are in the settings tab. Look for Addition Board
Manager URLs: and copy and paste this URL into that field: http://digistump.com/package_digistump_index.json
then click ok. If you need more space, then click the button next to the field
and a window should open where you can add the URL.

.. image:: ../images/boards_manager.png
   :alt: image

Once the URL has been added to Ardunio IDE we can then set up the selection of
which Digispark we want to use and write our scripts for it. To select our
Digispark go to Tools, hover over Board:, go to Boards Manager, and in the
search bar type in “digispark”. You should see a package that says Digispark AVR
Boards by Digistump. Click Install in the bottom right corner and let it
download.

Once the package has been installed, we can now select which Digispark we want
to use. We will be selecting the default Digispark. To do this go to Tools,
hover over Board:, hover over Digistump AVR Boards, and select Digispark
(Default – 16.5mhz). Once you have selected the correct Digispark you are ready
to start writing scripts or even downloading scripts made from the internet. [#f4]_

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


.. [#f4] Kody. (2019, December 13). *How to Run USB Rubber Ducky Scripts on a
   Super Inexpensive Digispark Board*. WonderHowTo.
   https://null-byte.wonderhowto.com/how-to/run-usb-rubber-ducky-scripts-super-inexpensive-digispark-board-0198484/.

.. [#f5] CedArctic. (2020, July 31). *DigiSpark-Scripts*. GitHub.
    https://github.com/CedArctic/DigiSpark-Scripts

.. [#f6] *Writing your first USB rubber Ducky Payload*.
    https://docs.hak5.org/hc/en-us/articles/360010471234-Writing-your-first-USB-Rubber-Ducky-Payload.
