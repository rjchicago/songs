# Song Repository Conventions

## Directory Structure

Each song is organized in its own directory under `src/` following this pattern:

```
src/
└── song-name/
    ├── lyrics.txt
    ├── suno.txt
    ├── style.txt
    ├── hd.wav
    └── cover.jpg/png
```

## File Naming

- **Directory names**: Use lowercase with hyphens (kebab-case)
  - Examples: `white-wedding`, `tik-tik-tok`, `shes-a-fox`
- **File names**: Use lowercase with specific extensions
  - `lyrics.txt` - Clean lyrics
  - `suno.txt` - Production version with notes
  - `style.txt` - Genre and style information
  - `hd.wav` - High-quality audio
  - `cover.jpg` or `cover.png` - Album artwork

## Content Formatting

### lyrics.txt
- Clean lyrics without production notes
- First character of each line capitalized
- No brackets `[]` or parentheses `()` 
- No production directions or timing notes

### suno.txt
- Original lyrics with production notes
- May include brackets for verse/chorus labels
- May include parentheses for directions
- May include timing and production notes

### style.txt
- Musical genre and style descriptors
- Tempo, mood, and instrumentation notes

## Git Tracking

- **Tracked**: `.txt` files, `README.md`, `.gitignore`
- **Ignored**: `*.wav`, `*.png`, `*.jpg` (binary files)