# SAHARSA SMART CLASSES — APK build

This project includes a GitHub Actions workflow that builds a debug APK automatically.

## Mobile-only steps
1. Create/sign in to a GitHub account.
2. Create a new repository, e.g. `saharsa-smart-classes`.
3. Upload all files/folders from this project ZIP to the repository.
4. Open **Actions** → **Build SAHARSA SMART CLASSES APK** → **Run workflow**.
5. When the workflow finishes, open the run and download the artifact named **SAHARSA-SMART-CLASSES-APK**.
6. Extract the artifact ZIP and install `app-debug.apk` on an Android phone.

No Play Store developer fee is required for this direct APK distribution method.

Note: This workflow creates a debug APK for testing/direct distribution. A signed release APK/AAB should be used for production publishing.
