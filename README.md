# OpenGL Planetary System

An interactive OpenGL coursework application featuring the Sun, Earth, Moon, and Mars, with textured spheres, orbital guides, tracking cameras, and a Milky Way background.

## Download / 下载

**[Download the macOS app](https://github.com/Fang0000420/opengl-planetary-system/releases/latest/download/OpenGL_Planetary_System_macOS_arm64.zip)**

- Apple Silicon (M-series chips), **macOS 15 or newer**.
- Python and dependencies are included; no separate Python installation is needed.
- Extract the ZIP, then open `OpenGL Planetary System.app`.
- The app is ad-hoc signed, without Apple notarization. If macOS blocks it, use System Settings → Privacy & Security → Open Anyway.

解压后双击 `.app` 即可运行。完整说明在压缩包内的 `START_HERE.md` 和 `README.md` 中。

## Controls

| Input | Action |
| --- | --- |
| Left click | Switch overview / Earth–Moon / Mars view |
| Right drag | Rotate the camera |
| Up / Down | Zoom in / out |
| R | Reset the current camera |
| Space | Pause / resume |
| L | Toggle lighting |
| + / - | Change animation speed |
| Esc | Exit |

## Verification

Rendering, camera switching, pause/resume, and Escape exit were checked on macOS 15.7.4. The extracted application also passes its dependency and texture self-check.

ZIP SHA-256: `26c2018398a1b07c8d1abb6534fe71816d3e306a9896990fc7dd0efc1fd6a189`

## Image credit

Milky Way panorama: **ESO/S. Brunier**, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). [Original image](https://www.eso.org/public/images/eso0932a/). Full credits and bundled dependency notices are included in the download.
