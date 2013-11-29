bakedoc
=======

Bakedoc is a set of scripts and makefiles, written in Bash and PHP. They exist
to help you get a multi-section document together, splice in generated images
from Dotty and MSCGen, etc.

## Create a new document

Navigate to the directory where you want to store the document, and run the
command `/path/to/bakedoc/install`. This will copy bakedoc into the directory
as well as bootstrap all the files needed. When it is done, all you need to
do is type `make` to generate your first PDF. Then start editing the files in
the `source` directory to edit your document.
