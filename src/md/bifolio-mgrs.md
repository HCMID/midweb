# Managing a bifolio image project #

Project managers, 2012-2013:

- Venetus B bifolios: Pat Rapuano
- Escorial Upsilon 1.1 bifolios:  Pat Rapuano
-  Jerome, *Chronicles* : Debbie Sokolowski

## Guide ##

Please review [the HMT project guide to creating bifolio images](http://www.homermultitext.org/hmt-doc/guides/bifolios.html), to be sure you are familiar with current standards, and to be able to help team members use it as a reference.

## Assigning bifolios to teams ##

Use the following Google tables to keep track of what team has been assigned what bifolio pairs:

- [Venetus B](https://www.google.com/fusiontables/DataSource?docid=1zNfsoWwIaOrx-p9dHs_BFw2O1SdPJwdeYpVDsp4)
- [Upsilon 1.1](https://www.google.com/fusiontables/DataSource?docid=13DqSaY3rJQYFNT_uHcISFAuHoEwRdglrHX3J6sg)
- Jerome, [Geneva 49](https://www.google.com/fusiontables/DataSource?docid=1CcdeVPQSVbJAEdGnRundM3ISwbOiH8NKmlkL8Vs)

Remember to use the "Sequence" column to sort bifolios into the correct order in the MS.

## Verifying and accepting bifolios ##

Team members will turn in two images to you: a `xcf` file, and a `png` file.  Check the `png` to be sure that it is properly aligned and cropped.  If it is, upload it to our server as follows.

1. Open a terminal, and `cd` (change directory) to the directory where the image files are located.  If you've copied them to your Desktop, that will be `cd Desktop`;  if they're on a thumb drive, that will be something like `cd /Volumes/NAMEOFTHUMBDRIVE`
2. Copy the files to the appropriate limbo directory on server using the `scp` command. To copy *all* .xcf and .png files:
    -  for Geneva 49:  `scp *.xcf *.png debbiesokolowski@shot.holycross.edu/Volumes/eikon/gen49-limbo`
    - for Venetus B:   `scp *.xcf *.png PatR@shot.holycross.edu/Volumes/eikon/venb-limbo`
    -  for Upsilon 1.1:   `scp *.xcf *.png PatR@shot.holycross.edu/Volumes/eikon/e3-limbo`

## Update the record in the Google table ##

When the file has been copied to our server, add a date to the "submitted" column in the Google table (same links above).
