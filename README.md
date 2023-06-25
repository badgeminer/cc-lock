# ComputerCraft lock

Computer craft lock is a simple lua program that add two factors authentication to your computer.

:warning: For now, you can bypass the lock by just putting the computer in a disk drive. 9551-Dev did [a fork](https://github.com/9551-Dev/cc-lock) using a [program created by MCJack123](https://gist.github.com/MCJack123/32c56917dc61da336ec0e8ca6aae39f8) to enable encryption on the computer, however this feature is not fully stable.

To install the program, you can use the following command in your computer:

```wget run https://raw.githubusercontent.com/badgeminer/cc-lock/main/cc-lock/installer.lua```

To register your account, go to your root folder (`cd /`) and run the following command:

```register```

You can register your account, and enable two factors authentication if your want.

When this is done, you can reboot the computer and see the lock in action.

:warning: Two factors authentication needs an external app running on a device like a phone to work properly.
