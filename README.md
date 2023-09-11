# Tor Browser
\
Fingerprinting resisting browser bundled with Tor

For reproducibility, build the snap using:  
```sh
snapcraft -v --destructive  # without --enable-manifest
SOURCE_DATE_EPOCH=946684800 mksquashfs prime tor-browser-unofficial.snap -noappend -comp xz -no-fragments -all-root -no-xattrs
```
