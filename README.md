# Day 01 — Image Under 100 KB

A free, no-install tool for a common upload problem: shrinking a photo to fit an application form, profile, or website size limit.

**[Open the live compressor](https://mhussain-codes.github.io/day-01-image-under-100kb/)** · [View the source](index.html)

## What it does

- Accepts JPG, PNG, and WebP images up to 20 MB.
- Compresses toward a size limit from 10 KB to 5,000 KB.
- Lets you choose WebP or JPEG output and a maximum image width.
- Shows original size, compressed size, savings, dimensions, and a preview.
- Keeps the original file unchanged and processes the image in your browser.

## Use it

1. Open the live compressor in a modern browser.
2. Choose or drop a JPG, PNG, or WebP image.
3. Set the maximum size, output format, and width, then select **Compress image**.
4. Download the smaller copy.

## Privacy

The image is handled locally with browser image and canvas APIs. This page has no upload endpoint, analytics, external library, or request for the selected image.

## Notes

- The chosen size is a target. Some images cannot reach a very small limit without substantial quality or dimension loss; the tool reports when the target was not reached.
- JPEG does not support transparency, so transparent areas get a white background. Choose WebP to keep transparency.
- Check the result before using it. Compression quality depends on the source image and browser.
- Uses createImageBitmap and Canvas toBlob; an up-to-date browser is recommended.

## Day 01

The first project in a practical problem-solving series: one small, useful tool at a time. Contributions are real work, not generated or backdated activity.
