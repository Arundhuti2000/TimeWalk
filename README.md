# TimeWalk

# Historical AI Education Game

Master's thesis project: An interactive historical education game with AI-powered NPCs.

## Features

- Explore Ancient Greece, Medieval Europe, and Renaissance Italy
- Converse with AI-powered historical figures
- Learn through immersive dialogue and quests

## Tech Stack

- Unreal Engine 5.3
- AI API integration for dynamic dialogue
- Third-person exploration gameplay

## Development Status

🚧 In Development - Sprint 1: Foundation

## Git LFS Setup

This project uses Git Large File Storage (LFS) to handle large binary assets efficiently.

### First-time Setup

```bash
# Install Git LFS (if not already installed)
git lfs install

# Clone with LFS files
git clone https://github.com/yourusername/historical-ai-education-game.git
cd historical-ai-education-game
git lfs pull
```

### Tracked File Types

The following file extensions are automatically stored in LFS:

- **UE5 Assets**: `.uasset`, `.umap`
- **3D Models**: `.fbx`, `.obj`, `.blend`, `.max`
- **Textures**: `.png`, `.jpg`, `.tga`, `.psd`, `.exr`, `.hdr`
- **Audio**: `.wav`, `.mp3`, `.ogg`
- **Video**: `.mp4`, `.mov`, `.avi`

### Adding New File Types

```bash
# Track new file extension
git lfs track "*.newextension"

# Commit the updated .gitattributes
git add .gitattributes
git commit -m "Track .newextension files with LFS"
```

### Verifying LFS

```bash
# Check which files are tracked by LFS
git lfs track

# List LFS files in repository
git lfs ls-files

# Check LFS storage info
git lfs env
```

### Troubleshooting

- If large files aren't uploading properly, ensure LFS is installed: `git lfs install`
- For existing large files not in LFS: `git lfs migrate import --include="*.extension"`
- Check GitHub LFS quota in repository settings if uploads fail
