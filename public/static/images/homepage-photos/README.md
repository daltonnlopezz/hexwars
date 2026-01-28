# Homepage Photo Gallery

Add your images to this folder to display them in the homepage photo gallery.

## Supported Formats
- .jpg / .jpeg
- .png
- .gif
- .webp

## How to Add Images

1. Place your image files in this folder (`static/images/homepage-photos/`)
2. Open `homepage.html` and find the `loadGalleryImages()` function
3. Add your image filenames to the `imageFiles` array, for example:
   ```javascript
   const imageFiles = [
       'my-image-1.jpg',
       'my-image-2.png',
       'my-image-3.jpg',
   ];
   ```

The gallery will automatically scroll through the images every 5 seconds, and users can manually navigate using the arrow buttons.
