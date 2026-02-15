# Shipwright AppImage Mirror

This repository provides an automated mirror for [Shipwright](https://github.com/HarbourMasters/Shipwright) AppImage builds.

## Purpose

The official Shipwright project offers zipped build artifacts, but hosting the AppImage artifacts directly can be useful for automations or other specific needs. This project uses GitHub Actions to:
1.  Check the upstream repository for new releases daily.
2.  Download the Linux artifact from the latest release.
3.  Extract and republish the `appimage` file to this repository's releases.

## Disclaimer

**This is an unofficial mirror.** This project is not affiliated with, endorsed by, or connected to Harbour Masters or the Ship of Harkinian project.

## License

### Mirror Scripts
The script in *this* repository (e.g., the GitHub Actions workflow) is licensed under the [MIT License](LICENSE).

### Mirrored Artifacts
The binary artifacts mirrored by this project are subject to the licenses of the upstream project and its dependencies. Please refer to the [Shipwright repository](https://github.com/HarbourMasters/Shipwright) for full licensing details regarding the software itself.
