# OTA Bundle Repository

This repository stores Over-The-Air (OTA) update bundles for the routine_app application.

## Structure

```
├── staging/
│   ├── android/          # Staging Android bundles
│   └── ios/             # Staging iOS bundles
└── production/
    ├── android/         # Production Android bundles
    └── ios/            # Production iOS bundles
```

## Purpose

- **Clean Separation**: Keeps bundle files separate from application source code
- **Easy Cleanup**: Remove old bundles without affecting main app history
- **Independent Versioning**: Bundle releases independent of app releases
- **CDN Hosting**: Can be used with GitHub Pages for free hosting

## Maintenance

- Bundles are automatically deployed via GitHub Actions
- Old bundles can be safely removed to save space
- Each bundle includes metadata about the source commit and app version

## Source

Bundles are built from: https://github.com/Krimxpotato/routine_app

---

*This repository is automatically managed by the hot-updater system.*
