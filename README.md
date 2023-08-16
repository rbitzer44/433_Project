# 433_Project
Imulating code from the Markisol remote transmitter

AT THIS POINT IN TIME I'M JUST COLLECTING INFO & DATA >>>>>AUGUST 16, 2013


roger@roger-OptiPlex-9020:~$ rtl_433
rtl_433 version 21.12 (2021-12-14) inputs file rtl_tcp RTL-SDR SoapySDR
Use -h for usage help and see https://triq.org/ for documentation.
Trying conf file at "rtl_433.conf"...
Trying conf file at "/home/roger/.config/rtl_433/rtl_433.conf"...
Trying conf file at "/usr/local/etc/rtl_433/rtl_433.conf"...
Trying conf file at "/etc/rtl_433/rtl_433.conf"...
Registered 176 out of 207 device decoding protocols [ 1-4 8 11-12 15-17 19-23 25-26 29-36 38-60 63 67-71 73-100 102-105 108-116 119 121 124-128 130-149 151-161 163-168 170-175 177-197 199 201-207 ]
Found Rafael Micro R820T tuner
Exact sample rate is: 250000.000414 Hz
[R82XX] PLL not locked!
Sample rate set to 250000 S/s.
Tuner gain set to Auto.
Tuned to 433.920MHz.
Allocating 15 zero-copy buffers
baseband_demod_FM: low pass filter for 250000 Hz at cutoff 25000 Hz, 40.0 us

time      : 2023-08-15 16:10:21
model     : Acurite-Tower id        : 1916
channel   : A            Battery   : 1             Temperature: 847.8 C      Humidity  : 0 %           Integrity : CHECKSUM
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2023-08-15 16:10:38
model     : Acurite-Tower id        : 1916
channel   : A            Battery   : 1             Temperature: 847.8 C      Humidity  : 0 %           Integrity : CHECKSUM
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2023-08-15 16:10:56
model     : Acurite-Tower id        : 1916
channel   : A            Battery   : 1             Temperature: 847.8 C      Humidity  : 0 %           Integrity : CHECKSUM
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2023-08-15 16:10:59
model     : LaCrosse-TX141THBv2                    Sensor ID : 90
Channel   : 00           Battery   : 1             Temperature: 23.40 C      Humidity  : 69 %          Test?     : No            Integrity : CRC
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2023-08-15 16:11:12
Model     : Markisol     id        : D41A
Control   : Up (12)      Channel   : 3             Zone      : 1             Integrity : CHECKSUM
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2023-08-15 16:11:12
Model     : Markisol     id        : D41A
Control   : Up (12)      Channel   : 2             Zone      : 2             Integrity : CHECKSUM
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2023-08-15 16:11:12
Model     : Markisol     id        : D41A
Control   : Up (12)      Channel   : 1            Zone      : 1             Integrity : CHECKSUM
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2023-08-15 16:11:12
Model     : Markisol     id        : D41A
Control   : Up (12)      Channel   : 4            Zone      : 2             Integrity : CHECKSUM
_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _
time      : 2023-08-15 16:11:12
Model     : Markisol     id        : D41A
Control   : Up (12)      Channel   : 3             Zone      : 3            Integrity : CHECKSUM
 Markisol iFit Spring Pro 433.92MHz window shades
* Also sold under the name Feelstyle and various Chinese brands like Bofu
* Compatible with remotes like BF-101, BF-301, BF-305, possibly others
* 
* Code by Antti Kirjavainen (antti.kirjavainen [_at_] gmail.com)
* 
* http://www.markisolgroup.com/en/products/ifit.html
* 
* Unless I'm completely mistaken, each remote has its unique, hard coded ID. I've included all commands from one as an
* example, but you can use RemoteCapture.ino to capture your own remotes. The purpose of this project was to get my own
* window shades automated, so there's a bit more work to be done, to reverse engineer the final 9 trailing bits of the
* commands. I don't (yet) know how they're formed, but most motors simply seem to ignore them. However, some require
* them to be correct and sendShortMarkisolCommand() will not work with such motors (use the full 41 bit command with
* sendMarkisolCommand() in that case).
* 
* Special thanks to Chris Teel for testing timings with some Rollerhouse products to achieve better compatibility.
* 
* 
* HOW TO USE
* 
* Capture your remote controls with RemoteCapture.ino and copy paste the 41 bit commands to Markisol.ino for sendMarkisolCommand().
* More info about this provided in RemoteCapture.ino.
* 
* If you have no multichannel remotes like the BF-305, you can also try the sendShortMarkisolCommand() function with
* your 16 bit remote ID and a command (see setup() below for more info). This function will not work with every motor,
* so first try the full 41 bit commands.
* 
* 
* HOW TO USE WITH EXAMPLE COMMANDS
* 
* 1. Set the shade into pairing mode by holding down its P/SETTING button until it shakes twice ("TA-TA") or beeps.
* 2. Send the pairing command, eg. "sendMarkisolCommand(SHADE_PAIR_EXAMPLE);", which will shake the shade twice ("TA-TA") or beep.
* 3. Now you can control the shade, eg. sendMarkisolCommand(SHADE_DOWN_EXAMPLE); (or SHADE_UP_EXAMPLE, SHADE_STOP_EXAMPLE etc.).
* 
* Setting limits is quicker with the remotes, although you can use your Arduino for that as well. Some motors do not erase the
* the limits even if you reset them by holding down the P/SETTING button for 8-10 seconds. They just reset the list of registered
* remote controls.
* 
* 
* PROTOCOL DESCRIPTION
* 
* Tri-state bits are used.
* A single command is: 3 AGC bits + 41 command tribits + radio silence
*
* All sample counts below listed with a sample rate of 44100 Hz (sample count / 44100 = microseconds).
*
* Starting (AGC) bits:
* HIGH of approx. 216 samples = 4885 us
* LOW of approx. 108 samples = 2450 us
* HIGH of approx. 75 samples = 1700 us
* 
* Pulse length:
* SHORT: approx. 15 samples = 340 us
* LONG: approx. 30 samples = 680 us
* 
* Data bits:
* Data 0 = short LOW, short HIGH, short LOW (wire 010)
* Data 1 = short LOW, long HIGH (wire 011)
* 
* Command is as follows:
* 16 bits for (unique) remote control ID, hard coded in remotes
* 4 bits for channel ID: 1 = 1000 (also used by BF-301), 2 = 0100 (also used by BF-101), 3 = 1100, 4 = 0010, 5 = 1010, ALL = 1111
* 4 bits for command: DOWN = 1000, UP = 0011, STOP = 1010, CONFIRM/PAIR = 0010, LIMITS = 0100, ROTATION DIRECTION = 0001
* 8 bits for remote control model: BF-305 multi = 10000110, BF-101 single = 00000011, BF-301 single = 10000011
* 9 bits for something? I have yet to figure out how this is formed, but most motors simply do not seem to care (others do)
* 
* = 41 bits in total
*
* There is a short LOW drop of 80 us at the end of each command, before the next AGC (or radio silence at the end of last command).
* End the last command in sequence with LOW radio silence of 223 samples = 5057 us
* 
* 
* HOW THIS WAS STARTED
* 
* Project started with a "poor man's oscilloscope": 433.92MHz receiver unit (data pin) -> 10K Ohm resistor -> USB sound card line-in.
* Try that at your own risk. Power to the 433.92MHz receiver unit was provided by Arduino (connected to 5V and GND).
*
* To view the waveform Arduino is transmitting (and debugging timings etc.), I found it easiest to directly connect the digital pin (13)
* from Arduino -> 10K Ohm resistor -> USB sound card line-in. This way the waveform was very clear.
* 
* Note that a PC sound cards may capture the waveform "upside down" (phase inverted). You may need to apply Audacity's Effects -> Invert
* to get the HIGHs and LOWs correctly.
* 
******************************************************************************************************************************************************************
*/



// Example commands to try (or just capture your own remotes with RemoteCapture.ino):
#define SHADE_PAIR_EXAMPLE                 "10111011111011111000001010000011110101001" // C button
#define SHADE_DOWN_EXAMPLE                 "10111011111011111000100010000011110110101" // DOWN button
#define SHADE_STOP_EXAMPLE                 "10111011111011111000101010000011110110001" // STOP button
#define SHADE_UP_EXAMPLE                   "10111011111011111000001110000011110101011" // UP button
#define SHADE_LIMIT_EXAMPLE                "10111011111011111000010010000011110100101" // L button
#define SHADE_CHANGE_DIRECTION_EXAMPLE     "10111011111011111000000110000011110101111" // STOP + L buttons
