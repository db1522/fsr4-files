# fsr4-files

Backup download source for [FSR 4.1 Lite by ROG Ally Life](https://github.com/db1522/fsr4-lite-rog-ally), the free
Xbox Game Bar widget that runs FSR 4.1.2 Lite on AMD handhelds through OptiScaler.

**You don't need anything from this repo.** The widget downloads these files by itself. Its main source is ROG Ally
Life's own storage; this repo is only used when that can't be reached, for example on networks or ad-blocking DNS
services that block it.

## What's here

Each [release](https://github.com/db1522/fsr4-files/releases/latest) holds the two files OptiScaler uses for FSR 4.1.2
Lite:

| File | Used for |
|---|---|
| `amdxcffx64.dll` | DirectX 12 (also DX11 and Vulkan games, through OptiScaler's DX12 path) |
| `amdvkffx64.dll` | Vulkan |

They're AMD's FidelityFX FSR 4 files, unmodified and signed by AMD. The widget only accepts a file if its AMD signature
checks out, whichever source it came from.

## Credits

FSR is by AMD. These files were made available to the community by **TheRazerMD**, and the widget is powered by
[OptiScaler](https://github.com/optiscaler/OptiScaler) by **cdozdil** and contributors.

This repo isn't affiliated with or endorsed by AMD. AMD, FSR and FidelityFX are trademarks of Advanced Micro Devices,
Inc. If you're a rights holder and want these files removed, open an issue or contact
[contact@rogallylife.com](mailto:contact@rogallylife.com) and they'll be taken down promptly.
