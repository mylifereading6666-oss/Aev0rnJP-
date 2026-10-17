# Aev0rnJP Roulette Android APK

This Android app opens the published Aev0rnJP Roulette website in a WebView, so website changes (including the support page status) are shown when the device is online.

## Build
The GitHub Actions workflow `.github/workflows/build-apk.yml` builds a debug APK automatically when Android project files change. To run manually, open the repository's Actions tab, select **Build Aev0rnJP APK**, choose **Run workflow**, then download the **Aev0rnJP-Roulette-APK** artifact from the completed run.

This is a debug APK for direct testing, not a signed production release. Internet access is required to load the website.
