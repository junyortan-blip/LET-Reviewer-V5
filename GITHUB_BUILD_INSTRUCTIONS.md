
# GitHub Cloud Build

This project includes a GitHub Actions workflow at:
`.github/workflows/build-apk.yml`

After uploading the project to your GitHub repository:
1. Open the **Actions** tab.
2. Select **Build LET Reviewer APK**.
3. Tap **Run workflow**.
4. Wait for the build to finish.
5. Open the completed workflow run.
6. Download the **LET-Reviewer-V5-APK** artifact.
7. Extract the artifact ZIP to get `app-debug.apk`.
8. Install the APK on your Android phone.

The workflow builds a debug APK in GitHub's cloud using Java 17 and Gradle 8.9.
