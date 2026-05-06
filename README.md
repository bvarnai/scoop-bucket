# Scoop bucket

Welcome to my [Scoop](https://scoop.sh/) bucket. This repository contains manifests for specialized tools and custom builds.

## 📦 Available apps

| App | Description |
| --- | ----------- |
| **[rsync-for-git-bash](https://github.com/bvarnai/rsync-for-git-bash)** | A specialized build of `rsync` linked against the specific `msys-2.0.dll` runtime used by [Git for Windows](https://gitforwindows.org/). |

## 🚀 Installation

First, ensure you have [Scoop](https://scoop.sh/) installed. Then, add this bucket to your local Scoop installation:

```powershell
scoop bucket add bvarnai-bucket https://github.com/bvarnai/scoop-bucket
```

Now you can install apps from this bucket:

```powershell
scoop install rsync-for-git-bash
```

## 🛠️ Maintenance

Manifests in this bucket are automatically updated via GitHub Actions triggered by releases in their respective source repositories.

