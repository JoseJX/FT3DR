# FT3DR
Tools for working with the FT3DR
Joe Jezak (AC3GA)

aprs_extractor - A tool to extract APRS information from an FT3D backup file
  Usage:
    aprs_extractor <backup file>

  Output:
    This tool will output up to 60 APRS Stations from the backup. Each will be
    dumped to a separate file in the same format strings as aprs.fi. There are
    still a few missing fields and some garbage data. This will also print out
    the metadata for each file as it's processed including the reception date
    and time.

  Issues:
    - I may need to add escaping for non-ascii bytes
    - There are still some missing fields and unknown values
    - Any suggestions?
