# Mini Book Cover Maker

A free tool for making printable covers for tiny books. Drop in a back cover, spine and front cover, and it sizes everything to fit, lays the covers out on a letter-size page, and saves a print-ready PDF.

**Use it here:** https://iqualx.github.io/mini-books/

Nothing to install and no account needed. It runs entirely in your browser.

## What it's for

- **Small:** Dollar Tree Super Glue foam mounting tabs (0.5" × 0.75"), or the small 3D printed book.
- **Medium and Large:** 3D printed hardcover books (18 × 25 × 5 mm and 22 × 30 × 6 mm).
- **3D printed mini books.** Get the customizable book model on MakerWorld: YOUR-MAKERWORLD-LINK
- **Anything else.** Choose **Custom** and enter your own sizes in inches or millimeters.

## How to use it

1. **Pick a profile** in the left panel, or choose **Custom** and enter your sizes.
2. **Add your images.** Each book has three sections: Back, Spine and Front.
   - Click a section and paste an image (Ctrl+V). The next empty section is selected automatically, so you can paste back, spine and front in a row.
   - Or drag image files onto a section, or onto the page to fill empty spots in order.
   - Files with "front", "back" or "spine" in the name go to the right spot on their own.
3. **Adjust the fit** by clicking any section:
   - **Stretch** fills the section edge to edge.
   - **Fill** fills the section without squishing and trims the overflow.
   - **Fit** shows the whole image and fills leftover space with a background color.
   - **Custom** lets you drag the image and its handles to place it by hand. Arrow keys nudge it.
   - **Trim blank edges** removes transparent or white borders from your image.
   - Use the eyedropper to pick a background color from the image.
4. **Set copies** under each book if you want more than one.
5. **Click Save PDF.** The button shows how many pages it will print.

### Draw-your-own books

Click **+ Add outline book**, or check **Outline** under any book. Outline books print as a blank cover with a cut border and dashed fold lines on both sides of the spine, so kids can draw their own.

### Using the 3D model

If you customized the book model on MakerWorld, choose **Custom**, switch the units to **mm**, and enter the same width, height and thickness you used there. If you have the customized `.scad` file, click **Load sizes from .scad** to fill them in automatically.

## Printing tips

- Print the PDF at **100% / Actual size**. "Fit to page" will shrink the covers.
- The default export is **600 DPI**, which keeps tiny spine text sharp.
- Turn on **Cut outlines** (on by default) to get thin guide lines for cutting.
- A thin white line in your PDF viewer is usually just how Chrome or Edge draws the page. It won't print. Zoom in or out to check.

## Other features

- **Undo / Redo** with Ctrl+Z and Ctrl+Y
- **Save PNG** or **Copy** a single book to use in Canva or another app
- Your settings are remembered between visits

## Privacy

Your images never leave your computer. Everything happens in your browser. Nothing is uploaded to this site or anywhere else. Images aren't saved, so they're cleared when you close or reload the page.

## Files

- `index.html` is the entire tool in one file. You can also download it and open it locally.
