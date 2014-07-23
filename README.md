cat_cache_safe
==============

Tool is similar to /bin/cat but with Linux Page cache bypass ability using O_DIRECT. It's very useful for backing up OpenVZ ploop images.

Compile:
```bash
cd /usr/src
git clone https://github.com/FastVPSEestiOu/cat_cache_safe.git
make
./cat_cache_safe /etc/issue
```
