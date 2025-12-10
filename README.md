# ComfyUI App Store

This repository contains the ComfyUI app definition for CI-OS-Hub.

## Structure

```
apps/
  └── comfyui/
      ├── config.json           # App configuration
      ├── docker-compose.json   # Docker compose configuration
      └── metadata/
          └── description.md    # App description
```

## Adding to CI-OS-Hub

To add this app store to your CI-OS-Hub instance:

1. Go to Settings → App Stores
2. Click "Add App Store"
3. Enter:
   - **Name**: `comfyui` (or any name you prefer)
   - **URL**: `https://github.com/companionintelligence/comfy.git`
4. Click Submit

The app store will be cloned and the ComfyUI app will be available in the marketplace.

## App Details

- **App ID**: `comfyui`
- **Port**: 8188
- **Categories**: AI, Development
- **Architectures**: amd64, arm64
