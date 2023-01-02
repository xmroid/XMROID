# XMROID

This is an Android (binary) command line miner program built from [XMRig](https://github.com/xmrig/xmrig) source code.

We compile specifically only for you so the binaries can run in Android device without the need for Root Access, Ubuntu or any support libraries. It only requires the [Termux](https://play.google.com/store/apps/details?id=com.termux) application to run it. It's that simple!

This binary should work for all Android 7 devices and above, be it 32bit or 64bit.

ABI Support : ARMEABI-V7, ARM64-V8, X86 & X86_64.


## How to use

1. Download [xmroid](https://github.com/xmroid/XMROID/releases) and unzip put in internal memory.

2. Copy the xmroid file to Termux.
```bash
$ cd /sdcard/folder/xmroid $HOME
```

3. Grant access permission.
```bash
$ chmod 755 xmroid
```

4. Done and you ready for to mine.
```bash
$ ./xmroid -a algo -o https://poolurl:port -u wallet address -p password
```

#### Credits
* [XMRig](https://github.com/xmrig/xmrig)

### Donations
XMR:
`47VJ1y5eirQXgnMcNCnmeFhFCZAVy6pcbGta4qMDbdauUK3oYpbAiQ8AKekRAR4cdH7ZCpoh2hFMg34DpPNA79yEA13Tfeo`

RTM:
`RVHwjSg91iqS8GiRQ52WQRaQ1Qr4Kkv42W`
