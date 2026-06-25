# OpenVGAL Virtual Gallery

Your virtual 3D art gallery is ready to deploy!

## Quick Start

1. Extract this ZIP to your web server folder
2. Open viewer.html in a browser (or serve with any web server)

Your images are already included in the ZIP under these folders:
- Room 1/
- Room 2/

## Folder Structure

```
your-gallery/
├── viewer.html         # Main viewer
├── building_v2.json    # Gallery configuration
├── declarations.js     # Path configuration
├── templates/          # 3D room templates
├── materials/          # Textures and materials
├── Room 1/               # Your images
├── Room 2/               # Your images
├── overlay.js          # UI overlay
├── overlay.css         # UI styles
└── babylon.js          # 3D engine
```

## Deploying to a Subfolder

This gallery works in any subfolder — just extract and serve. All paths are
relative to viewer.html, so no configuration needed. For example:
- https://example.com/ (root)
- https://example.com/gallery/ (subfolder)
- https://example.com/art/my-gallery/ (nested subfolder)

If you need to customize paths, edit `declarations.js`.

## Custom Logo

Replace `materials/logo.png` with your own image.
Use white artwork on a black background (the white areas will glow).
Recommended size: 1024x512 px, PNG format.

## Need Help?

Visit https://openvgal.com for documentation and support.

Generated with OpenVGAL Generator
