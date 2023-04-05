# Portenta-H7-Parallels-Drivers

## How to install the drivers


# Disable Driver Signature on Windows

```
Restart your computer by pressing the shift key.
You will be on a blue screen asking you to “Choose an Option”.
Then select “Troubleshoot” from the options.
Then click on “Advanced Options”.
Then click on “Startup Settings”.
Then click on “Restart”.
Then your Computer will start and ask you to press a number to choose the option.
Then press 7 or F7 to “disable driver signature Enforcement”.
```

You can find the guide [here](https://answers.microsoft.com/en-us/windows/forum/all/permanently-disable-driver-signature-enforcement/176caf31-df98-41bc-8a5f-b9b91589da45) too

# Using Zadig

Install Zadig from [here](https://zadig.akeo.ie), after installing the tool, connect the Portenta in Bootloader Mode by pressing the button twice (make sure the green led is fading) and then open the tool.

## Make sure to "List All Devices" inside Zadig
![list all devices](https://github.com/alessandromrc/Portenta-H7-Parallels-Drivers/blob/main/img/ListAllDevices.png)

After listing all devices you should see an "Internal Flash" 

![internal flash](https://github.com/alessandromrc/Portenta-H7-Parallels-Drivers/blob/main/img/Internal%20Flash.png)

Then just press on "Install Driver" and make sure you get this notification:

![installed](https://github.com/alessandromrc/Portenta-H7-Parallels-Drivers/blob/main/img/Installed.png?raw=true)
