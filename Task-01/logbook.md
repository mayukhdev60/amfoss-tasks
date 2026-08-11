LEVEL 1
Found the awakening line for level 1: ONE_PIECE{GITO_GITO_NO_AWAKENING}
Navigated into the GrandLine cargo directory.
Ran find . -executable -type f to inspect file permissions across all four folders. The files were plain text files, but the fruit possessed executable permissions.
GrandLine/Loguetown_Reef/sector_C/devil_fruit_6.txt
Ran ./eat.sh sector_C/devil_fruit_6.txt from Loguetown_Reef/ to consume the genuine fruit and reveal the awakening signature.

LEVEL 2
Switched to branch whiskey_peak_investigation.
Checked all files, found .baroque_works_cache, ran ls -la in that and found an unlock_vault.sh file
Using the hint, xported AWAKENING_SIGNATURE="ONE_PIECE{GITO_GITO_NO_AWAKENING}" and ran .baroque_works_cache/unlock_vault.sh. 
Used diff on the generated log files to find the flag.
Flag: BAROQUE_DIAL{SPLIT_TIMELINE_MISDIRECTION}

