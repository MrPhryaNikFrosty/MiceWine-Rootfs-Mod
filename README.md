## MiceWine Emulator

MiceWine is a project that aims to run Windows applications and games on Android smartphones.

It uses a customized build of Wine compiled for Android and Box64 to run in the best possible way.

Actually in constant development.

It's use a XServer based on Termux-X11 

### Installation
1. Download the micewine app and micewine rootfs mod
2. Install the micewine then open it
3. Enable files permissions and choose the .rat file that has been downloaded to install the rootfs
4. Wait in a few minutes until the installation of rootfs done
5. Then, configure the micewine in the settings
6. Now, you can enjoy the games by using my rootfs!

For more details installation can be checked from here: 

https://youtu.be/Nj4VIHdsziE?si=KyEbYdDxN6NUOZJw

### Some Information

This mod project focused on modifying on rootfs only, so don't mind if you want to request feature in the app because I'm here to mod the rootfs only, not mod the app. If you need that, please request it directly to developer of micewine. We will update it regularly based on latest changes in official micewine github

### Compatible Android Versions

Support Android 10+

### Compatible GPUs

| GPU        | Support               | Driver                      |
|------------|-----------------------|-----------------------------|
| Adreno     | Supported             | Turnip/Native/Zink          |
| Xclipse    | Supported             | Native/Zink                 |
| Mali       | Supported             | Native/Zink                 |

The native driver works well for Xclipse GPUs, Adreno GPUs, Mali GPUs.

About Mali GPUs, Only tested on Mali-G615, Mali-G610, Mali G76 and Mali-G925-Immortalis. And the rest of Mali GPUs are unknown for compatibility with native driver

For PowerVR GPUs or any other GPUs, the native driver doesn't compatible yet

If you're using Snapdragon that have support with Turnip, it's highly recommended to use turnip than a native driver to avoid glitch. And if you're using Snapdragon that don't have a turnip support, especially 8 elite you can only use native driver but you may encounter glitch in some games

Vulkan 1.3 is Recommended for better performance and graphical precision. 1.1 works with DXVK-Stripped-Requirements, but displays various graphical issues.

## Third Party Open Source Applications:

- [Box64](https://github.com/ptitSeb/box64)
- [WineHQ](https://gitlab.winehq.org/wine/wine)
- [Termux-X11](https://github.com/termux/termux-x11)
- [Mesa](https://gitlab.freedesktop.org/mesa/mesa)
