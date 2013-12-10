## Spy with iPython Notebook

### Warning

This project is provided without warranty, and is for educational purposes only!

### Installation Requirements

#### System Libraries (non-Linux):

* libdnet
* libpcap

#### Python Libraries

* iPython, including:
	* pyzmq
	* tornado
* Scapy, including:
	* dnet - **downloaded manually [here](http://libdnet.sourceforge.net/)**
	* pylibpcap
* geojson
* pygeoip
* python-nmap

#### Sample Databases

* [GeoIPCity](http://geolite.maxmind.com/download/geoip/database/GeoLiteCity.dat.gz) from [dev.maxmind.com](http://dev.maxmind.com/geoip/legacy/geolite/)
* [http.pcap](http://wiki.wireshark.org/SampleCaptures?action=AttachFile&do=get&target=http.cap)
* [SkypeIRC.pcap](http://wiki.wireshark.org/SampleCaptures?action=AttachFile&do=get&target=SkypeIRC.cap) 

### Setup

1. Install system libraries, python libraries (`pip install -r requirements.txt`), manually install dnet (link above), and download/save sample databases.
2. Within the `spy` directory, run `sudo ipython notebook`.  It requires `sudo` because Scapy needs to run on root.
3. Have fun.

This was a brain-dump - Did I miss anything?  Feel free to submit a pull request.