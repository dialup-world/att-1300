# att-1300
Notes and information on the AT&amp;T 1300 terminal

## Power

Thanks to *snuci* I knew that the AT&T 1300 can be powered via 9VDC. The barrel plug to fit the jack is 5.5mm (outer barrel) by 2.5mm (inner barrel). I was able to use a supply putting out 9VDC, center positive, at 1A. *snuci* traced the power circuit out from the barrel jack to a 7805 voltage regular which should be rated to accept anywhere between 7VDC and 35VDC. I noticed that neither the pin or the barrel on the socket are directly connected to ground, making me wonder if the original PSU output AC.

## Video

The video connector is a 5-pin DIN connector in the 180 degree layout. From the socket front / plug solder side, pin 4 is composite video while pin 2 is ground. Note that the pins are not numbered 1-5 going from left to right and are instead are numbered 1, 4, 2, 5, 3. I have not verified if any of the other pins are carrying video. I wouldn't be surprised if any are purposed for R/G/B or Y/C (chroma/luma).

## Modem

It looks like the terminal features a standard dial-up modem. The user can only input a phone number, no other settings are configurable. The terminal only supports pulse dialing. I was able to call NIST's telephone time service and it appears only 300 baud is supported.

The phone number my unit is programmed to call is `543-0691`.
