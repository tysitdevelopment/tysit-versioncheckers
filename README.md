# 🔄 Tysit Version Checkers

<div align="center">
    <img src="https://img.shields.io/github/stars/GITHUB_USERNAME/tysit-versioncheckers?style=for-the-badge&color=yellow" alt="Stars">
    <img src="https://img.shields.io/github/forks/GITHUB_USERNAME/tysit-versioncheckers?style=for-the-badge&color=cyan" alt="Forks">
    <img src="https://img.shields.io/github/license/GITHUB_USERNAME/tysit-versioncheckers?style=for-the-badge&color=green" alt="License">
</div>

## 📋 Description

Tysit Version Checkers is a powerful version control system for FiveM/RedM resources. It helps developers manage their script versions and keeps users informed about updates through an elegant notification system.

## ✨ Features

- 🚀 Real-time version checking
- 🎯 Automatic update notifications
- 📝 Detailed changelog display
- 🎨 Colored console messages
- ⚡ Lightweight and efficient
- 🔒 Secure GitHub integration

## 📥 Installation

1. Create a repository on GitHub
2. Upload the `version.json` file to your repository
3. Replace `GITHUB_KULLANICI_ADI` and `REPO_ADI` in `versionchecker.lua` with your GitHub information
4. Add `versionchecker.lua` to your resource
5. Update your `fxmanifest.lua` to include the version checker

## 🔧 Configuration

### version.json
```json
{
    "version": "1.0.0",
    "changelog": [
        "- Initial Release",
        "- Added Feature X",
        "- Fixed Bug Y"
    ]
}
```

### fxmanifest.lua
```lua
version '1.0.0'

client_scripts {
    'versionchecker.lua',
    -- your other scripts
}
```

## 📊 Version Status Messages

### Up to Date ✅
```
[YourScript] ╔════════════════════════════════════════╗
[YourScript] ║ ✅ Version 1.0.0 Up to date            ║
[YourScript] ╚════════════════════════════════════════╝
```

### Update Available ❌
```
[YourScript] ╔════════════════════════════════════════╗
[YourScript] ║ ❌ Version 1.0.1 OUTDATED!             ║
[YourScript] ║ - Added new features                   ║
[YourScript] ║ - Fixed bugs                          ║
[YourScript] ╚════════════════════════════════════════╝
```

## 📝 Usage

1. When you release an update:
   - Update the version number in `version.json`
   - Add changelog entries
   - Update `fxmanifest.lua` version

2. Users will automatically see:
   - Current version status
   - Available updates
   - Detailed changelog

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Support

For support, join our [Discord Server](YOUR_DISCORD_LINK) or create an issue in this repository.

## 🌟 Show Your Support

Give a ⭐️ if this project helped you!
