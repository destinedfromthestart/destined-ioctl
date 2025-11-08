# destined-ioctl

very mid ioctl base i made in my first months of learning kernel
nothing crazy, at the time it was undetected and used to load with gdrv.
i never understood why crackers went so crazy over fucking this driver, but it was later sent to epic along with the method it uses since i didnt protect my shit or encrypt my driver during file stream back then.
the method was deleting the file on disk after loading, which along with randomization of everything made it unique on every pc
i used my mutation engine from user mode to make it unique in memory on each load as well.

## could it be made undetected?

not in this state, you'd have to find a different method of loading it which would require a rework of the base since it relies on being loaded with an accessible driverobject
its just spaghetti code tbh near to the end of developing it i just got lazy with organization, you can probably find better bases out there

## why am i leaking this?

its been sitting on my disk for like a year so i have nothing else to do with it im not using it again since ive since swapped to much better methods 
its pretty shit overall, looking back i used really bad methods.
