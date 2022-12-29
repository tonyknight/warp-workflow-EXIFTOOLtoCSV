# warp-workflows
These are Warp workflows to help create metadata tags for scanned images and optimize their sizes. Requires [exiftool] (https://github.com/exiftool/exiftool) and [jepgoptim] (https://github.com/tjko/jpegoptim)

1. EXIFTool2CSV -- Takes a SourceDirectory and dumps some essential metadata tags to a CSV file.
2. EXIFTool-PhotoRenamer -- Renames images based on the date the images was taken using the DateTimeOriginal tag.
