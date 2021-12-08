# Notes on RePEc archive 

Original author: David DeRemer (updated 16 Nov. 2021)

## Key Identifiers and Directories

Archive handle: asx (assigned by RePEc)

Institution handle: gsbnukz (assigned by RePEc)

Archive URL: https://NUGSB.github.io/RePEc/asx/
(determined by us: we must notify RePEc to change it)

Series handles (determined by us: must be six characters): 
nugsbw (for working papers)
nugsbd (for Business Digest)

## Overview

The RePEc archive is presently mirrored on the following shared folder (on David DeRemer's GDrive): https://drive.google.com/drive/folders/12-u-zeLo1yTg3xFLb0we_48n4CYi39bn

Edits to the archive on GDrive can then be pushed to the github webserver, https://NUGSB.github.io
I (David DeRemer) will be notified of GDrive updates and push the files to this server.

The folder RePEc (along with its contents and file structure) must be uploaded to the webserver. 

## Instructions for regular updates (new materials)

For each new working paper or business digest, add a new block of metadata to the series RDF file on Google Drive, following the structure of previous entries. 

I suggest adding metadata in reverse chronological order and leave a line of white space between blocks.

Files must be saved in a simple text format (with extension rdf).

The series RDF files are 
Working papers: https://NUGSB.github.io/RePEc/asx/nugsbw/wpdata.rdf
Business Digest: https://NUGSB.github.io/RePEc/asx/nugsbd/bddata.rdf

For the title and abstract, be careful to use a simple text encoding. This in practice means only straight quotes and apostrophes (no curly quotes or curly apostrophes).

Part of the metadata includes the URL to the paper on the [NUGSB research website](https://gsb.nu.edu.kz/en/faculty-and-research/research). Miras is in charge of uploading papers to the NUGSB research website. This upload should be completed before we submit the RDF files. 

After updates are pushed to our archive server, RePEc should update within 48 hours.  

Links where the RePEc papers can be found include the following:

https://econpapers.repec.org/paper/asxnugsbd/
https://econpapers.repec.org/paper/asxnugsbw/
https://ideas.repec.org/s/asx/nugsbd.html
https://ideas.repec.org/s/asx/nugsbw.html

## More general instructions (not necessary for regular maintenance) 

### Adding more .rdf files

It is possible to add more rdf files to any archive. The key point is that any new rdf files must be added to the index.html file in the same directory. Otherwise the index.html files do not need to be updated. 

### Adding new series

To add a new series,
* Add a new series to the asxseri.rdf file following the format for the intial two series. 
* A six-character handle must be created.
* A subfolder matching the handle should be created containing an rdf file for the new series.

### Changing the metadata server

To change the metadata server, 
* The new server URL must be entered into asxarch.rdf
* Upload the whole asx directory structure to the new server
* RePEc must be notified of the new asx URL at repec@repec.org 

### Further instructions

General RePEc instructions may be found at https://ideas.repec.org/stepbystep.html



