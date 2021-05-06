OpenCore EFI for Asus ROG STRIX B350-F GAMING
=============================================

Hardware Specification
----------------------

+-----------+-------------------------------------------------------+-------------------------------------------+
|Devices    |Model                                                  |Comments                                   |
+===========+=======================================================+===========================================+
|Motherboard|Asus ROG STRIX B350-F GAMING                           |BIOS version 5603                          |
+-----------+-------------------------------------------------------+-------------------------------------------+
|Processer  |AMD Ryzen 5 3600                                       |                                           |
+-----------+-------------------------------------------------------+-------------------------------------------+
|Graphics   |XFX AMD Radeon RX 550 2GB Double Dissipation           |Radeon RX 550 640SP, see `Graphics Card`_  |
+-----------+-------------------------------------------------------+-------------------------------------------+
|Disk       |HIKVISION SSD M.2 C2000 Pro 1TB                        |                                           |
+-----------+-------------------------------------------------------+-------------------------------------------+
|Memory     |Corsair Vengeance LPX 16GB (2 x 8GB) DDR4 3200MHz C16  |CMK16GX4M2B3200C16                         |
+-----------+-------------------------------------------------------+-------------------------------------------+
|Monitor    |LG UltraFine 4K                                        |                                           |
+-----------+-------------------------------------------------------+-------------------------------------------+


Components
----------

+---------------------------------------------------+-----------------------+-----------------------+
|Components                                         |Version                |Latest Version         |
+===================================================+=======================+=======================+
|`OpenCore`_                                        |0.6.9                  ||OpenCore|_            |
+---------------------------------------------------+-----------------------+-----------------------+
|`HfsPlus.efi`_                                     |Date 2021-03-01 GMT+8  |                       |
+---------------------------------------------------+-----------------------+-----------------------+
|`VirtualSMC`_                                      |1.2.3                  ||VirtualSMC|_          |
+---------------------------------------------------+-----------------------+-----------------------+
|`Lilu`_                                            |1.5.3                  ||Lilu|_                |
+---------------------------------------------------+-----------------------+-----------------------+
|`WhateverGreen`_                                   |1.4.9                  ||WhateverGreen|_       |
+---------------------------------------------------+-----------------------+-----------------------+
|`AppleALC`_                                        |1.6.0                  ||AppleALC|_            |
+---------------------------------------------------+-----------------------+-----------------------+
|`SmallTreeIntel82576`_                             |1.3.0                  ||SmallTreeIntel82576|_ |
+---------------------------------------------------+-----------------------+-----------------------+
|`AppleMCEReporterDisabler`_                        |1.0                    |                       |
+---------------------------------------------------+-----------------------+-----------------------+
|`NVMeFix`_                                         |1.0.7                  ||NVMeFix|_             |
+---------------------------------------------------+-----------------------+-----------------------+
|`SMCAMDProcessor`_                                 |0.6.6                  ||SMCAMDProcessor|_     |
+---------------------------------------------------+-----------------------+-----------------------+
|`RestrictEvents`_                                  |1.0.1                  ||RestrictEvents|_      |
+---------------------------------------------------+-----------------------+-----------------------+

Pre-requisits
-------------

Graphics Card
`````````````
The XFX RX 550 dosn't boot into the graphical interface and can be solved by flashing the `Sapphire PULSE RX 550 640SP BIOS <https://www.techpowerup.com/vgabios/197718/sapphire-rx550-2048-171013>`_.

`XFX RX 550 original BIOS <https://www.techpowerup.com/vgabios/229141/229141>`_.

.. _OpenCore: https://github.com/acidanthera/OpenCorePkg
.. |OpenCore| image:: https://shields.io/github/v/release/acidanthera/OpenCorePkg?sort=semver

.. _HfsPlus.efi: https://github.com/acidanthera/OcBinaryData/blob/master/Drivers/HfsPlus.efi

.. _VirtualSMC: https://github.com/acidanthera/VirtualSMC
.. |VirtualSMC| image:: https://shields.io/github/v/release/acidanthera/VirtualSMC?sort=semver

.. _Lilu: https://github.com/acidanthera/Lilu
.. |Lilu| image:: https://shields.io/github/v/release/acidanthera/Lilu?sort=semver

.. _WhateverGreen: https://github.com/acidanthera/WhateverGreen
.. |WhateverGreen| image:: https://shields.io/github/v/release/acidanthera/WhateverGreen?sort=semver

.. _AppleALC: https://github.com/acidanthera/AppleALC
.. |AppleALC| image:: https://shields.io/github/v/release/acidanthera/AppleALC?sort=semver

.. _SmallTreeIntel82576: https://github.com/khronokernel/SmallTree-I211-AT-patch
.. |SmallTreeIntel82576| image:: https://shields.io/github/v/release/khronokernel/SmallTree-I211-AT-patch?sort=semver

.. _AppleMCEReporterDisabler: https://github.com/AMD-OSX/AMD_Vanilla/blob/opencore/Extra/AppleMCEReporterDisabler.kext.zip

.. _NVMeFix: https://github.com/acidanthera/NVMeFix
.. |NVMeFix| image:: https://shields.io/github/v/release/acidanthera/NVMeFix?sort=semver

.. _SMCAMDProcessor: https://github.com/trulyspinach/SMCAMDProcessor
.. |SMCAMDProcessor| image:: https://shields.io/github/v/release/trulyspinach/SMCAMDProcessor?sort=semver

.. _RestrictEvents: https://github.com/acidanthera/RestrictEvents
.. |RestrictEvents| image:: https://shields.io/github/v/release/acidanthera/RestrictEvents?sort=semver
