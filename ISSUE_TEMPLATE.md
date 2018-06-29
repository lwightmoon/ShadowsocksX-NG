**System and Shadowsocksx-NG version:**

- macOS 10.??.?? (16E????)
- Shadowsocksx-NG 1.?

**Expected behavior:**



**Actual behavior:**

(N/A for feature requests)

**Steps to reproduce:**

(N/A for feature requests)

**How often does this happen?**

(N/A for feature requests)

**ss-local.log**

Please upload the ss-local.log file here the file is in `~/Library/Logs`
1) Open 'Advanced Settings -> enable Verbose Mode'
2) Continue run `Shadowsocksx-NG` for 5 minutes
3) Upload the `~/Library/Logs/ss-local.log` here (with or without compress)

**Application log**

Open the `Console.app` and search `Shadowsocksx-NG`
Copy paste the log here

**Crash Log**

If the app crashes and pop up a crash log, please copy and paste here

Dyld Error Message:
  Library not loaded: */libsodium.18.dylib
  Referenced from: /Users/USER/Library/Application Support/ShadowsocksX-NG/*/ss-local
  Reason: image not found

Binary Images:
       0x10aacf000 -        0x10aaedff3 +ss-local (0) <FE894517-4A16-3D5B-9394-72859184FAEF> /Users/USER/Library/Application Support/ShadowsocksX-NG/*/ss-local
       0x10ab00000 -        0x10ab06fff +libev.4.dylib (0) <FF8BE3F3-A6DE-30EE-BF64-37A7DD5C3D73> /usr/local/lib/libev.4.dylib
       0x10ab0f000 -        0x10ab15ffb +libudns.0.dylib (0) <FB73F91C-E504-3CAD-A6CD-939503F3D0C3> /usr/local/lib/libudns.0.dylib
       0x10d25b000 -        0x10d2a59df  dyld (551.3) <AFAB4EFA-7020-34B1-BBEF-0F26C6D3CA36> /usr/lib/dyld
    0x7fff78bc0000 -     0x7fff78bc1ffb  libSystem.B.dylib (1252.50.4) <CDA73F3E-2A7D-3354-818A-580317A03255> /usr/lib/libSystem.B.dylib

