# B550m Hackintosh for AMD Processors with Integrated Graphics

**Used OpenCore version**: 1.0.2

**macOS version**: 15.2

- Depending on your number of cores, don't forget to change [these values](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#patch-2) in your config's `Kernel -> Patch`.

  - Current value is set to 6 cores (5600G has 6 cores and 12 threads).

- Wifi is not currently working.

## Software Compatibility
- Sequoia (15.x) (tested)
- Sonoma (14.x) (tested)
- Ventura (13.x) (tested)
- Monterey (12.x) (tested)
- Big Sur (11.x)
- Catalina (10.15.x)
- Mojave (10.14.x)
- High Sierra (10.13.x)

| Specs    |                                        |
| -------- | -------------------------------------- |
| CPU      | AMD Ryzen 5 5600G with Radeon Graphics |
| GPU      | Radeon Vega 7 integrated graphics      |
| Motherboard | Asus Prime B550M-A WIFI II          |
| Audio    | Realtek ALC897                         |

## Demo
![demo](demo.png)

## Credits

- [OpenCore](https://github.com/acidanthera/)
- [AMD Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [NootedRed](https://github.com/ChefKissInc/NootedRed)
