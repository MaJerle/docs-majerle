.. figure:: static/images/logo_tm_full.png
	:align: center

Welcome to documentation for software written by Tilen MAJERLE.
This is an entry point for all the projects which I'm working on now and in the future.

.. note:: 
    There is a heavy work to be done to transfer all documentation written in doxygen to sphinx.

Projects
========

This is a list of projects and link to respective documentation:

* `ESP-AT Lib <https://majerle.eu/documentation/esp_at/html/index.html>`_: Library to control ESP8266 or ESP32 wifi module with host device using official AT commands
* `GSM-AT Lib <https://majerle.eu/documentation/gsm_at/html/index.html>`_: Generic AT parser for SIMCOM based GSM modules
* `GPS NMEA Parser </projects/gps-nmea-parser>`_: Platform independent GPS NMEA parser to read and process GPS NMEA 0183 statements
* `OneWire-UART </projects/onewire-uart>`_: Platform independant OneWire protocol library. Its design is focused for UART hardware on embedded systems
* `Ring buffer </projects/ringbuff>`_: Platform independant generic `FIFO` library
* `LwMEM </projects/lwmem>`_: Lightweight dynamic memory manager, optimized for embedded systems
* `EasyGUI <https://majerle.eu/documentation/gui/html/index.html>`_: Platform independant graphic user interface, developed in mind for embedded systems with limited amount of memory

Get in touch
============

You can contact me via online contact form available on `my website <https://majerle.eu>`_.

License
=======

.. literalinclude:: license.txt

.. toctree::
	:maxdepth: 2
	:glob:

	*
	*/index
