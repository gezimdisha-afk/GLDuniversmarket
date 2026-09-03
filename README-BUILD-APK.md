# GLD Univers Market — Android APK build

This project is prepared for a GitHub Actions cloud build using Expo EAS.

1. Upload this project to a GitHub repository.
2. In Expo, create an access token and add it to GitHub as repository secret `EXPO_TOKEN`.
3. In GitHub: Actions → Build Android APK → Run workflow.
4. When EAS finishes, open the build URL shown in the workflow log/EAS dashboard and download the APK.

The `preview` profile is configured to produce an installable Android APK (`android.buildType: apk`).
