# draw-text-at-an-angles-using-PIL.
drawing the text onto a blank image, rotating that image, and then pasting the rotated image into the main image

How does it work:
1- Create a transparency mask.
2- Draw the text onto the mask.
3- Rotate the mask, and crop to proper size.
4- Paste the desired color into the image, using the rotated transparency mask containing the text.
