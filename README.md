# MinDAPP Local — build in cloud

This is a standalone local UI shell, not a patch to the original MinDAPP APK. It does not implement the original remote builder or game-cheat functionality.

## Easiest build from a tablet
1. Create a GitHub account and a new repository.
2. Upload the contents of this ZIP (including the hidden `.github` folder).
3. Open the repository's **Actions** tab.
4. Select **Build MinDAPP Local APK** and press **Run workflow** (or wait for the automatic build after pushing to `main`).
5. Open the completed run, scroll to **Artifacts**, and download `MinDAPP-Local-debug`.
6. Extract the artifact ZIP to get `app-debug.apk`.

The workflow builds an unsigned-for-release, debug-signed APK suitable for testing. It does not need Android Studio on your tablet.
