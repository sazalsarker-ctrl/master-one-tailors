# Master One Tailors — APK Ready

This project wraps the supplied Master One Tailors Supabase web application as an Android app using Capacitor.

## What is included
- Supabase-backed Master One Tailors HTML app
- Fixed JavaScript runtime issues found in the supplied HTML
- Android application configuration
- GitHub Actions workflow that builds a debug APK automatically

## GitHub APK build
1. Upload the contents of this project to the repository's `main` branch.
2. Open **Actions**.
3. Select **Build Master One Tailors APK**.
4. Run **workflow_dispatch**.
5. When the workflow finishes, download the artifact named `master-one-tailors-debug-apk`.

No Android Studio is required if GitHub Actions is used.

## Security
The HTML contains a Supabase public/publishable client key. Do not put a Supabase service-role/secret key into this app. Ensure Supabase RLS policies protect every table.
