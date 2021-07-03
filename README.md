# Electron Widevine CDM

*The project is deprecated. The old codebase can be found [here](https://github.com/quanglam2807/electron-widevinecdm).*

WidevineCDM for Electron - Allows you to run Netflix and other streaming websites in your Electron apps.

## Using Widevine in Electron as of 2021

If you would like to run Widevine CDN inside your Electron application you should look at using the [Castlabs Electron](https://github.com/castlabs/electron-releases) fork along with using the [Castlabs EVS](https://github.com/castlabs/electron-releases/wiki/EVS) service to sign the application for Windows and macOS (Linux doesn't require this level of signing).
