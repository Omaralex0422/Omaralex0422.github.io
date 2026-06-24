# images/ — your portfolio photos live here

Every picture container on the site loads its image from a file in THIS folder.
The rule is simple:

    the file name (before the extension) = the container's id shown below

Drop a correctly-named file in here, reload the page, and it appears. Remove the
file and the container goes back to its empty "Drop…" placeholder. Nothing is
lost on reload, because the images are real files you control.

Any common format works — .jpg, .jpeg, .png, .webp, or .avif. You do NOT write
the extension into the site; it's auto-detected. So `portrait.png` and
`portrait.jpg` both work for the `portrait` slot.

You only need to add the ones you actually want. Empty slots just show their
placeholder — no broken images.

QUICK WAY TO FILL IT (no manual renaming):
Click a container and choose a photo. The page hands you back the image already
named for this folder (e.g. `shot-mmg.webp`) — either as an automatic download,
or via the "⤓ Save to images/" button that appears when you hover a filled
container. Just drag that downloaded file into this folder and reload.

--------------------------------------------------------------------------------
FILE NAME              WHERE IT SHOWS                              BEST SHAPE
--------------------------------------------------------------------------------
portrait              About section — the tall portrait frame      3:4 vertical

shot-mmg              MMG Operations — laptop screen (home + detail) 16:10 wide
shot-receiptflow      ReceiptFlow — phone screen (home + detail)    9:19.5 tall
shot-dmc              Modern/Dock Marine — laptop screen            16:10 wide
shot-mindtomind       A Mind to Mind — laptop screen                16:10 wide

  (One "shot-…" file fills BOTH the small card on the home page AND the big
   device on that project's detail page — they share the image.)

GALLERY PLATES (the "Gallery" grid at the bottom of each project's detail page,
shown in a 4:3 box — any aspect is fine, it letterboxes):

  MMG Operations (4 plates):
    gallery-mmg-1   gallery-mmg-2   gallery-mmg-3   gallery-mmg-4

  ReceiptFlow (6 plates):
    gallery-receiptflow-1 … gallery-receiptflow-6

  Modern/Dock Marine (6 plates):
    gallery-dmc-1 … gallery-dmc-6

  A Mind to Mind (6 plates):
    gallery-mindtomind-1 … gallery-mindtomind-6
--------------------------------------------------------------------------------

Example: to set your About portrait, save your photo as  images/portrait.jpg
         to set the MMG laptop screenshot, save  images/shot-mmg.png
         to fill the first MMG gallery plate, save  images/gallery-mmg-1.jpg
