
In this package tamil nadu local online Fm Station


INSTALL PACKAGE

pip install tn-radio

IMPORT PACKAGE

Python 3.7.3 (default, Oct  7 2019, 12:56:13) 
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
import tn_radio
obj = tn_radio.Radio()

LIST OF FM STREAM

Python 3.7.3 (default, Oct  7 2019, 12:56:13) 
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
import tn_radio
obj = tn_radio.Radio()

obj.list_fm()

0 Ohm Namashivaya[Chennai, India] \n
1 Namakkal Thedal FM[Namakkal, India] \n
2 Natrinai FM[Tiruchirappalli, India] \n
3 Pudukkottai Thedal FM[Pudukkottai, India] \n
4 முத்தமிழ் FM மேலூர்[Melur, India] \n
5 Virudhunagar Thedal FM[Virudhunagar, India] \n

SET STREAM FM INDEX

Python 3.7.3 (default, Oct  7 2019, 12:56:13) 
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
import tn_radio
obj = tn_radio.Radio()
obj.set_stream(3)

PLAY FM 

Python 3.7.3 (default, Oct  7 2019, 12:56:13) 
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
import tn_radio
obj = tn_radio.Radio()
obj.set_stream(3)


obj.play()

STOP FM

obj.play()

PAUSE FM

obj.pause()

CHANGE FM STREAM

obj.set_stream(5)

