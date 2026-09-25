# Android Dex — GitHub Actions

1. Create a GitHub repository.
2. Upload ALL files in this ZIP to the repository root.
3. Open **Actions**.
4. Select **Build Android Dex APK**.
5. Press **Run workflow**.
6. Wait for the workflow to finish.
7. Open the completed run.
8. Under **Artifacts**, download **AndroidDex-debug-apk**.
9. Extract it and install the `.apk` on Android.

This workflow installs the Android SDK on the GitHub runner and then runs the Gradle build.

IMPORTANT: this first workflow creates a debug APK. For a permanent release APK, use a private signing key stored in GitHub Secrets; never commit the keystore or password into the repository.
