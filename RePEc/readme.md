# Notes on RePEc archive 

## Key Identifiers and Directories

Archive handle: asx (assigned by RePEc)

Institution handle: gsbnukz (assigned by RePEc)

Archive URL: https://gsb.nu.edu.kz/storage/files/5/RePEc/asx/  (5Oct2021 this needs to be confirmed by Miras)

Series handles: nugsbw (for working papers), nugsbd (for Business Digest). These need to be six characters.

## Overview

The folder RePEc (along with its contents and file structure) must be uploaded to the GSB webserver. The Archive URL must match the URL field in the file RePEc/asx/asxarch.rdf     

General instructions may be found at https://ideas.repec.org/stepbystep.html

## Instructions for Updating

For each new working paper or business digest, create a new RDF file matching the previous ones. (e.g. for working paper 2021/02 create the file 2021-02.rdf and complete the metadata fields analogous to 2021-01.rdf)

A line should be added to index.html for every new file.

## Additional Notes and Concerns

### By David De Remer, 5Oct2021

- Once the archive is first ready for the public, inform RePEc by emailing the Archive URL to repec@repec.org . RePEc does not need to be notified again unless the Archive URL changes. 
- I assumed article handles had to follow file naming restrictions, so I created article handles with dashes (e.g. 2021-01) rather than slashes (2021/01). I believe we can still include slashes in the Number field though of each article.
- I assumed the URL of the first working paper would be https://gsb.nu.edu.kz/storage/files/5/NUGSB%20Workingpaper/NUGSB_workingpaper_2021_01.pdf   This can be updated in the asx/nugsbw/2021-01.rdf file if the URL is any different. 
- As I understand, the index.html files are usually necessary to simulate browsing. I added them in case they indeed were. This is discussed here: https://ideas.repec.org/t/httpserver.html



