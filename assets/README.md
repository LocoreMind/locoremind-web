# LocoreMind Assets

## Logo Files

- `logo.svg` - Main logo (100x100)
- `logo-og.svg` - Open Graph logo for social media (1200x630)

## Converting SVG to PNG

### Option 1: Online Conversion (Recommended)
1. Visit https://svgtopng.com/ or https://cloudconvert.com/svg-to-png
2. Upload `logo.svg` and export as `logo.png` (recommended: 512x512 or larger)
3. Upload `logo-og.svg` and export as `logo-og.png` (keep at 1200x630)

### Option 2: Using Figma/Sketch/Illustrator
1. Open the SVG file
2. Export as PNG at 2x or 3x resolution
3. For `logo.png`: export at least 512x512
4. For `logo-og.png`: export at 1200x630

### Option 3: Command Line (if you have ImageMagick)
```bash
# Install ImageMagick if needed
brew install imagemagick

# Convert logo
magick logo.svg -resize 512x512 logo.png

# Convert OG image
magick logo-og.svg logo-og.png
```

### Option 4: Using Chrome/Safari
1. Open the SVG file in browser
2. Right-click and "Save as" or take a screenshot
3. Use Preview (macOS) or Paint (Windows) to resize if needed

## Required Files for SEO
- ✅ `logo.svg` - Created
- ✅ `logo-og.svg` - Created
- ⚠️ `logo.png` - **Needs to be created** (at least 512x512)
- ⚠️ `logo-og.png` - **Needs to be created** (1200x630)

Once PNG files are created, the website will have proper logo display in:
- Google Search Results
- Social Media Shares (Twitter, Facebook, LinkedIn)
- Browser bookmarks
