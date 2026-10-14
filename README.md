# GodSuite Mac Builder

This is a dedicated runner repository to build macOS DMG packages for GodSuite using free public GitHub Actions runners.

## How to trigger a build:
1. Ensure `GH_PAT` (Personal Access Token with read access to private `GodSuite` repo) is configured in **Settings → Secrets and variables → Actions**.
2. Optionally add `VPS_SSH_KEY` to deploy directly to the VPS downloads directory.
3. Go to the **Actions** tab → **Build Mac Client** → click **Run workflow**.
