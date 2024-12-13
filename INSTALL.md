NDNlive: NDN Live Streaming Video Project based on Consumer/Producer API
==

Prerequisites
==
These are the prerequisites to build NDNlive (Tested using Ubuntu 16.04 LTS).

**Required (Install by this order):**
* [ndn-cxx (v0.4.1)](https://github.com/named-data/ndn-cxx/tree/ndn-cxx-0.4.1)
* [consumer-producer-api (commit 35bb5ad)](https://github.com/iliamo/Consumer-Producer-API)
* [NFD (v0.4.1)](https://github.com/named-data/NFD.git)
* [gstreamer-1.0](https://gstreamer.freedesktop.org/documentation/installing/on-linux.html?gi-language=c)


consumer-producer-api
--
Clone the Repository, change directory to the cloned repository and then:
```
git reset --hard 35bb5ad
```

Build instructions
==
<pre>
$ ./waf configure
$ ./waf
</pre>
