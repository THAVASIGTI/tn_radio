# TAMILNADU ONLINE FM RADIO

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/THAVASIGTI/tn-radio)
[![PyPI](https://img.shields.io/pypi/v/tn-radio)](https://pypi.org/project/tn-radio)
[![Downloads](https://pepy.tech/badge/tn-radio)](https://pepy.tech/project/tn-radio)

In this package `tamil nadu` local online Fm Station


## INSTALL PACKAGE
``` console
sudo apt-get install vlc
pip install tn-radio
```
## IMPORT PACKAGE

``` python
Python 3.7.3 (default, Oct  7 2019, 12:56:13) 
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
import tn_radio
obj = tn_radio.Radio()
```

## LIST OF FM STREAM

``` python
Python 3.7.3 (default, Oct  7 2019, 12:56:13) 
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
import tn_radio
obj = tn_radio.Radio()

obj.list_fm()

0 Ohm Namashivaya[Chennai, India]
1 Namakkal Thedal FM[Namakkal, India]
2 Natrinai FM[Tiruchirappalli, India]
3 Pudukkottai Thedal FM[Pudukkottai, India]
4 முத்தமிழ் FM மேலூர்[Melur, India]
5 Virudhunagar Thedal FM[Virudhunagar, India]
```

## SET STREAM FM INDEX

``` python
Python 3.7.3 (default, Oct  7 2019, 12:56:13) 
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
import tn_radio
obj = tn_radio.Radio()
obj.set_stream(3)
```

## PLAY FM 

``` python
Python 3.7.3 (default, Oct  7 2019, 12:56:13) 
[GCC 8.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
import tn_radio
obj = tn_radio.Radio()
obj.set_stream(3)
obj.play()
```

## STOP FM

``` python
     obj.stop()
```

## PAUSE FM

``` python
     obj.pause()
```

## CHANGE FM STREAM

``` python
     obj.set_stream(5)
```