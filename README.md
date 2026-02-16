# Shipwright AppImage Mirror

This repository provides an automated mirror for [Shipwright](https://github.com/HarbourMasters/Shipwright) AppImage builds.

## Purpose

The official Shipwright project releases zipped builds. Hosting the AppImage directly and statically can be useful for certain automations, or other specific needs. This project uses GitHub Actions to:
1.  Check the upstream repository for new releases daily.
2.  Download the Linux `zip` file from the latest release.
3.  Extract and republish the `appimage` file to this repository's releases.

## Disclaimer

**This is an unofficial mirror.** This project is not affiliated with, endorsed by, or connected to Harbour Masters or the Ship of Harkinian project.

## License

The binary artifacts mirrored by this project are subject to the licenses of the upstream project and its dependencies. Please refer to the [Shipwright repository](https://github.com/HarbourMasters/Shipwright) for licensing details regarding the software itself. The github action workflow in *this* repository is licensed under the [MIT License](LICENSE).

