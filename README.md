# [Android Debug Bridge (ADB)](https://developer.android.com/studio/command-line/adb) Utility


Android Debug Bridge (adb) is a versatile command-line tool that lets me communicate with a device. The <code>adb</code> command facilitates a variety of device actions, such as installing and debugging apps. <code>adb</code> provides access to a Unix shell that I can use to run a variety of commands on a device. It is a client-server program that includes three components:

* A **client**, which sends commands. The client runs on your development machine. You can invoke a client from a command-line terminal by issuing an adb command.
* A **daemon (adbd)**, which runs commands on a device. The daemon runs as a background process on each device.
* A **server**, which manages communication between the client and the daemon. The server runs as a background process on your development machine.

<code>adb</code> is included in the Android SDK Platform Tools package. 

<img width="600" alt="Screenshot 2023-02-19 at 10 51 33 PM" src="https://user-images.githubusercontent.com/70295997/220033837-f378a652-80a4-492e-8b4c-b49d40d039a4.png">

<img width="1800" src="https://user-images.githubusercontent.com/70295997/220491495-466bdbb6-967b-4d21-ab34-23ef858cea90.png">

<img width="700" src="https://user-images.githubusercontent.com/70295997/222868030-80f1b1f4-ffb4-4be0-b61b-0051f9696bcc.png">



Where the ***Daemon (adbd)*** fits in the context of the Android Boot Sequence:

<img width="1800" src="https://user-images.githubusercontent.com/70295997/222864274-a5528b68-b1d7-4ac0-b19e-3992ebd0088b.png">

How ADB compares to SSH:

<img width="800" src="https://user-images.githubusercontent.com/70295997/222871591-30617ef3-76a5-4370-8257-48de1e437222.png">


★ [ADB logcat](https://github.com/lana-20/adb-logcat-options-filters)

★ [ANR vs Crash](https://github.com/lana-20/anr-vs-crash)

★ [ADB logcat vs bugreport - ANR vs Crash continued](https://github.com/lana-20/android-crash-anr-logcat-bugreport)

★ [ADB commands](https://github.com/lana-20/adb-commands)

★ [ADB system services](https://github.com/lana-20/adb-system-services)

★ [ADB shell and file system](https://github.com/lana-20/adb-shell)

★ [ADB screen copy](https://github.com/lana-20/adb-screen-copy)



----

How ADB Works:
- [Droidcon - Magic of ADB](https://www.droidcon.com/2019/11/15/magic-of-adb/?video=380854175)
- [Android Developer](https://developer.android.com/studio/command-line/adb)
- [Google Git](https://android.googlesource.com/platform/system/core/+/master/adb/OVERVIEW.TXT)
- [dummies.com](https://www.dummies.com/web-design-development/mobile-apps/android-apps/android-emulators-or-whats-so-special-about-the-number-5554/)
