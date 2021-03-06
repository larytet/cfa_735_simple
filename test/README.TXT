Crystalfontz CFA-631, CFA-632 & CFA-634, CFA-633 & CFA-635 packet based
communications test/example program for GNU/Linux(*).

==================
Basic Installation
==================

   These are generic installation instructions:
   (Note that gcc v3.0 or later, make and their supporting libraries
    are required for this utility to work.)

     1. Extract the files contained within the cf_unix_utils_XXX.tar.gz
        archive to the desired location.
        To extract the files use the command:
	"tar -xzvf cf_unix_utils_XXX.tar.gz"

     2. 'cd' into the created folder and use 'make' to compile and
        create the example binaries.
     
     3. The example utilites run with the command line options of:
        ./example-XXX PORT BAUD
        PORT is something like "/dev/ttyS0" or "/dev/usb/ttyUSB0"
        BAUD is 19200 or 115200
        To clear the display, enter "clear" as an optional third parameter
    
    The screen output should show something similar to the following:

                ----------------------
                -  >This is line 1<  -
                -  >This is line 2<  -
                ----------------------

==================   
Notes on Baud Rate
==================

   This utility may be used to test the 631, 632, 634, 633 and 635 displays.

   BAUD rates for the modules are as follows:
      631 USB: 115200
      632 USB: 19200
      633 USB/Serial: 19200 (default) or 115200 (FW v1.4 and beyond)
      634 USB: 19200
      635 USB: 115200

   If the above baud rate does not give any output on the LCD, try 19200 or 115200
   as earlier/later models of a USB LCD may use a different baud rate to those shown
   above.

==================
Make options
==================

   If you modify the existing code and wish to do a fresh make, run
   'make clean' and then 'make' again. 

==================
Source Code
==================

    Source code for the example utilites are also contained in this archive.
    See the extracted sub-directories for the C source code.

    (*) This source code (with a few minor modifications) should also work under
    other operating systems.
    If you would like to have us (Crystalfontz) help you make these work under a
    a different OS, please email us.

==================
Crystalfontz America, Incorporated
12412 East Saltese Ave
Spokane Valley, WA 99216-0357
sales@crystalfontz.com http://www.crystalfontz.com
voice (509) 892-1200 fax (509) 892-1203 US toll-free (888) 206-9720
==================
