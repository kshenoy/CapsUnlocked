## CapsUnlocked

This is a complete solution for windows to map the CapsLock key to Control and Escape without losing the ability to toggle CapsLock

* Use CapsLock as Escape if it's the only key that is pressed and released within 300ms (configurable)
* Use CapsLock as LControl when used in conjunction with some other key or if it's held longer than 300ms
* Toggle CapsLock by pressing LControl+CapsLock

### FAQ
  * Who is this for?
    - This is primarily targeted at Vim/Emacs users but anyone who uses the Control key will find this helpful.
      IMHO, the CapsLock is pretty much useless and it shouldn't occupy such a prominent position. This remedies that.
      Also, as a Vim user, I find myself using the Escape key quite often too. Thus, this script was born

  * Why should I use it?
    - So that you'll no longer need to contort your left hand trying to reach for the control key.
      Try it. Your left pinky will thank you.

  * Is it safe?
    - To the best of my knowledge. AutoHotkey has a large, established and responsible community behind it.

  * What platforms does this work on?
    - This particular solution is meant for Windows only. There are other solutions for Linux (xCape) and OS X
      (Karabiner) but I couldn't find one for Windows and decided to fill the gap.

  * Can I toggle this on the fly?
    - Yes! Just right-click on the AutoHotkey icon in the SystemTray and choose `Suspend`

### Installation and Usage
If you don't want to mess with downloading the AutoHotkey executable etc. just download the latest standalone [CapsUnlocked.exe](https://github.com/kshenoy/CapsUnlocked/releases) and run it. That's it

If you're already using AutoHotkey or want to use it, either copy-paste the contents of CapsUnlocked.ahk into your script file or simply include it
