# PlutoTVforEmby
Source script: https://github.com/juliomm64/PlutoIPTV-for-TVH
Edited for Emby's XMLTV data.

Requires some additional libraries to be installed first:
pip install datetime, tzlocal, pytz, furl, wget

Within Emby's Live TV, import the m3u8 and xml file for the channels and guide.

Example of run command on Linux:
python3 pluto.py -i /opt/pluto -d /opt/pluto -c /opt/pluto -e /opt/pluto

Due to PlutoTV only publishiing 12 hours of guide data, you'll need to run this regularly to update the XML guide file.
