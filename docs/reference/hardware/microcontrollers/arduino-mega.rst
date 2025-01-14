.. include:: /include/include.rst
.. include:: /include/include-l3.rst
|EX-CS-LOGO|

*******************
Arduino Mega Setup
*******************

|conductor|

Why do we recommend the Mega?
-----------------------------

* When compiled, our code just barely squeezes onto an Arduino Uno. **A mega allows you to add more features** like networking and displays because it has more memory.
* The Mega has many more GPIOs (General Purpose Input/Outputs) available to you for constructing control panels and controlling turnouts, signals and other accessories.
* The Mega has more hardware serial ports. You can connect a WiFi board and something else like Bluetooth at the same time.
* The mega is only modestly more expensive than an Uno, with clones available for less than $10 USD.
* See the special note about the Mega+WiFi board below for a board that has the microcontroller and WiFi already on one board.

.. image:: /_static/images/microcontrollers/mega2.jpg
   :alt: Arduino Mega Microcontroller
   :scale: 75%

Note that if the size of the regular Mega board is an issue, there are condensed Mega clones that are only 52mm long! They don't take shields, so you will need to use headers and jumper wires, but they will fit in a very small box. Look for boards by the name "Arduino Mega 2560 PRO Embedded" or "Mini MEGA 2560 Pro Micro" or just "Mega Pro 2560". Be careful to get the correct one for what you are trying to do because they can come in 3.3V versions or 5V versions and have a Micro-USB port (which you probably want) or just pins to a TTL serial port, and come with header pins you have to solder or not. Remember it must be a 2560 not a 328.

.. image:: /_static/images/microcontrollers/mega_pro2.jpg
   :alt: Mega Pro Micro
   :scale: 35%

See the :doc:`/ex-commandstation/get-started/assembly` page for information on setting up this microcontroller.
