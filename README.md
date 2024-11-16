


![new_project_-_2024-01-10t152628  MConverter eu](https://github.com/user-attachments/assets/c7062104-5c4a-4037-89c5-8a19a303a56a)



Name 	Description
CPU 	Intel Core i5-1035G1
GPU 	Intel UHD Graphics
RAM 	12 GB DDR4
SSD 	1TB GB
Wi-Fi & Bluetooth 	Intel(R) Wireless Dual Band AC-3165
macOS 	Big Sur/ Monterey / Ventura 
OpenCore 	1.0.0 for HP 250 G8

What works:

    UEFI booting via OpenCore
    Built-in keyboard 
    Built-in trackpad (Full gestures)
    Audio Control Hotkeys
    Volume Cobtrol Hotkeys
    Integrated Camera
    Wifi, Ethernet and Bluetooth
    Native audio with AppleALC, including headphone
    Built-in mic
    Native power management
    Battery status
    USB 3.0 Ports (If you have trouble try remapping your usbs or use usbinjectall.kext)
    Type C Port for transfers
    Audio on internal speaker and headphone
    Sleep and Wake
    Bios Wise used it on the latest one F.61 and everything just works without modifying bios However remove secure boot and Bitlocker if enabled
    All Iservices work without problem just generate a serial using OpenCore COnfigurator


What doesnt work?

-Brightness keys need to be remapped in MacOS->Setting Preferences->Keyboard->Display-> Then assign e.g FN+F2 for decreasing brightness & Fn+F3 for increasing brightness
-Trackpad Tap and Hold isnt working theres need to use the left key and trackpad to move items
-Native Card Realtek only works bluetooth so i changed mine to an Intel Wireless card i had lying around for both Wi-Fi and Bluetooth so id advise get a new one according to the dortania guide.



