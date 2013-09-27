
# Notes on creating images of bifolio spreads#

Prerequisites:

- install [GIMP][1]

[1]: http://www.gimp.org/


## Set up

-  Open GIMP
-  Select “File” then “New”
-  Set  Width: 10000 px 	Ignore any warning that the file is too large.	 Height: 7000 px

## Image Editing

1.	Copy the Verso image
2.	In GIMP, select “Edit”, “Paste As”, and then “New Layer” 
3.	Repeat Step 2 (creating another layer) for the corresponding Recto image
4.	Using the “Move Tool” in the left-hand artist bar (it looks like four arrows in a cross pattern), move the Recto image to the right until its left edge slightly overlaps with the Verso’s right edge (i.e., make the image look like an open book)
5.	Make sure both images as aligned properly
6.	Use the “Crop Tool” in the left-hand bar (it looks like the tip of a small x-acto knife), cut off the black border all around the edge of the image (i.e., leave only the manuscript pages)
7.	Delete the “background layer” in the right-hand artist bar by selecting it and clicking the trash button below

## Saving

-	Select “File” and “Save As”, and choose a place to save it where you will have easy access (desktop, a folder, etc.)
-	Name the file using the pattern: *manuscript* - *verso number* v- *recto number* r (e.g., `gen49-10v-11r.xcf`).  This should create an `.xcf` file (still in GIMP).
-	In that same file, go to “File”, “Export” then select the location where the `.xcf` was saved, click “Export” in the saving window, and then click “Export” a final time in the new window which pops up. This should create a `.png` file with the same name.
