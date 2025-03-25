[![Bare Conductive](http://bareconductive.com/assets/images/LOGO_256x106.png)](http://www.bareconductive.com/)

# Bare Conductive Touch Board Driver
This is the signed Windows driver for the Bare Conductive Touch Board.


## Install

* Disconnect the Touch Board from your computer if it is already connected
* Download the [.zip](https://github.com/BareConductive/touch-board-driver/archive/public.zip) and extract it somewhere
* In the folder you have extracted, run one of **dpinst_x86.exe**, **dpinst_AMD64.exe** or **dpinst_ia64.exe**, depending on the architecture you are running on
* If the above doesn't make any sense, try them all until one works - Windows will not let you run an incorrect program
* Click Yes or Accept to all the questions you get asked - this will install our signed driver
* Restart your computer
* When you next plug in the Touch Board Windows will automatically install the correct drivers and the board will appear as a COM port
* The first time you try to upload code to the board via the Arduino IDE (or when you first press the reset button with the board connected to your computer) you may get a message that Windows failed to successfully install a driver. You will probably also find that your first upload fails. Don't worry about this - give your computer 45 seconds to catch up with itself and try again. This will only happen once.
* Once the driver is installed you can delete the folder you originally extracted the .zip into

