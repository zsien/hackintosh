OpenCore EFI for Asus ROG STRIX B350-F GAMING
=============================================

硬件規格
--------

+---------------+-------------------------------------------------------+-----------------------------------+
|設備           |型號                                                   |備註                               |
+===============+=======================================================+===================================+
|主板           |華碩 ROG STRIX B350-F GAMING                           |BIOS 版本 5603                     |
+---------------+-------------------------------------------------------+-----------------------------------+
|處理器         |AMD Ryzen 5 3600                                       |                                   |
+---------------+-------------------------------------------------------+-----------------------------------+
|顯卡           |訊景 AMD Radeon RX 550 2G 黑狼版                       |Radeon RX 550 640SP，參考 `顯卡`_  |
+---------------+-------------------------------------------------------+-----------------------------------+
|硬盤           |海康威視 SSD M.2 C2000 Pro 1TB                         |                                   |
+---------------+-------------------------------------------------------+-----------------------------------+
|內存           |海盜船復仇者 LPX 16GB (2 x 8GB) DDR4 3200MHz C16       |CMK16GX4M2B3200C16                 |
+---------------+-------------------------------------------------------+-----------------------------------+
|無線 & 藍牙    |Comfast AX200 PCI-E                                    |                                   |
+---------------+-------------------------------------------------------+-----------------------------------+
|顯示器         |LG UltraFine 4K                                        |                                   |
+---------------+-------------------------------------------------------+-----------------------------------+


組件
----

+---------------------------------------------------+-----------------------+-----------------------+
|組件                                               |版本                   |最新版本               |
+===================================================+=======================+=======================+
|`OpenCore`_                                        |0.7.4                  ||OpenCore|_            |
+---------------------------------------------------+-----------------------+-----------------------+
|`HfsPlus.efi`_                                     |Date 2021-05-05 GMT+8  |                       |
+---------------------------------------------------+-----------------------+-----------------------+
|`VirtualSMC`_                                      |1.2.7                  ||VirtualSMC|_          |
+---------------------------------------------------+-----------------------+-----------------------+
|`Lilu`_                                            |1.5.6                  ||Lilu|_                |
+---------------------------------------------------+-----------------------+-----------------------+
|`WhateverGreen`_                                   |1.5.4                  ||WhateverGreen|_       |
+---------------------------------------------------+-----------------------+-----------------------+
|`AppleALC`_                                        |1.6.5                  ||AppleALC|_            |
+---------------------------------------------------+-----------------------+-----------------------+
|`SmallTreeIntel82576`_                             |1.3.0                  ||SmallTreeIntel82576|_ |
+---------------------------------------------------+-----------------------+-----------------------+
|`AirportItlwm`_                                    |2.0.0                  ||AirportItlwm|_        |
+---------------------------------------------------+-----------------------+-----------------------+
|`AppleMCEReporterDisabler`_                        |Date 2009-10-10 GMT+8  |                       |
+---------------------------------------------------+-----------------------+-----------------------+
|`NVMeFix`_                                         |1.0.9                  ||NVMeFix|_             |
+---------------------------------------------------+-----------------------+-----------------------+
|`SMCAMDProcessor`_                                 |0.7                    ||SMCAMDProcessor|_     |
+---------------------------------------------------+-----------------------+-----------------------+
|`RestrictEvents`_                                  |1.0.5                  ||RestrictEvents|_      |
+---------------------------------------------------+-----------------------+-----------------------+

前置條件
--------

顯卡
````
訊景 RX 550 無法啓動到圖形界面，可以通過刷 `Powercolor RX 550 2048 MB BIOS <https://www.techpowerup.com/vgabios/209970/209970>`_ 解決。

`訊景 RX 550 原 BIOS <https://www.techpowerup.com/vgabios/229141/229141>`_。

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

.. _AirportItlwm: https://github.com/OpenIntelWireless/itlwm
.. |AirportItlwm| image:: https://shields.io/github/v/release/OpenIntelWireless/itlwm?sort=semver

.. _AppleMCEReporterDisabler: https://github.com/AMD-OSX/AMD_Vanilla/blob/opencore/Extra/AppleMCEReporterDisabler.kext.zip

.. _NVMeFix: https://github.com/acidanthera/NVMeFix
.. |NVMeFix| image:: https://shields.io/github/v/release/acidanthera/NVMeFix?sort=semver

.. _SMCAMDProcessor: https://github.com/trulyspinach/SMCAMDProcessor
.. |SMCAMDProcessor| image:: https://shields.io/github/v/release/trulyspinach/SMCAMDProcessor?sort=semver

.. _RestrictEvents: https://github.com/acidanthera/RestrictEvents
.. |RestrictEvents| image:: https://shields.io/github/v/release/acidanthera/RestrictEvents?sort=semver
