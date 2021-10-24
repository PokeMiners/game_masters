# PokeMiners Game Master
Repository for latest JSON and txt versions of the Game Master for Pokemon GO.

The `latest` folder will contain a .txt and a .json of the latest Game Master. Only one of each will be found here. They will always be called `latest.txt` and `latest.json`. This folder will also contain a `timestamp.txt` file that contains the timestamp/batch ID from the latest Game Master. This can be used to check if a new Game Master has been updated.

The `previous_game_master` folders will contain a timestamped folder for each previous Game Master release. Each folder will contain a .txt and .json file as well. Timestamp format is:

`gm`  
`gm_version`  
`apk_version`  
`year-month-day`  
`hour-minute-second`  

Original timestamp format is:

`gm`  
`gm_version`  
`apk_version`  
`day_of_week`  
`month_and_day`  
`hour_minute_second`  
`year`

## Note on Obfuscation
Niantic obfuscates parts of their game code, to make it harder to determine field names. We spend a lot of time going through and trying to make sense of these obfuscated names, but please note they may not be fully accurate. We have prefixed all obfuscated field names that we were not able to 100% determine their names with `ob`. We will try our best to name these fields as accurately as possible, with some being more accurate than others. Even if we are fairly certain of the field name, we will leave the `ob` prefix on until we have confirmation from the code. 

**These fields names may change over time as we determine more accurate names for them so please be aware when using these fields in your apps to put in proper error handling in case of changes.**

## Disclaimer
This repo is for educational use only. All content found within this repo is the property of The Pokemon Company and Niantic. PokeMiners did not create or modify any files found within this repo and all copyright belongs to the respective companies. Please respect the original source material.
