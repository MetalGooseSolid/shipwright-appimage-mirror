# Shipwright AppImage Mirror

This repository provides an automated mirror for [Shipwright](https://github.com/HarbourMasters/Shipwright) AppImage builds.

## Purpose

The official Shipwright project produces daily builds, but locating and downloading specific AppImage artifacts can sometimes be cumbersome depending on the platform or specific need. This project uses GitHub Actions to:
1.  Check the upstream repository for new releases daily.
2.  Download the Linux artifacts.
3.  Extract and republish the `.appimage` file to this repository's releases.

## Disclaimer

**This is an unofficial mirror.** This project is not affiliated with, endorsed by, or connected to the Harbour Masters or the Ship of Harkinian project.

## License

### Mirror Scripts
The scripts and configuration in *this* repository (e.g., the GitHub Actions workflows) are licensed under the [MIT License](LICENSE).

### Mirrored Artifacts
The binary artifacts mirrored by this project are subject to the licenses of the upstream project and its dependencies. Please refer to the [Shipwright repository](https://github.com/HarbourMasters/Shipwright) for full licensing details regarding the software itself.

As noted in the upstream project, Ship of Harkinian contains code from the ZeldaRET Ocarina of Time decompilation project and various other open-source libraries (e.g., SDL2, libultraship, etc.), each with their own licenses.