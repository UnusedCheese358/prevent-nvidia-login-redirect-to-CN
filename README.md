(Disclaimer: The scripts are made by Nvidia, not by me. I just somehow found a way not to get forcefully redirected when logging in my Nvidia account)

TODO: The description will be updated later, stay tuned! 



# Change the region of the website when logging in your NVIDIA account with ease! 輕鬆切換 NVIDIA 賬號登錄網站地區

Are you, for some reason, unable to log in your Nvidia (Global) account repeatedly because it constantly takes you to the cn site instead of global?

# More about the json files posted

## How do I switch between global and CN when logging in with my Nvidia account via the Nvidia App? 
1. Locate the json file `LocalizedConfig.json`  (By default and in most cases, the json file should be located in C drive, where you installed your Nvidia App. In my case:  `C:\ProgramData\NVIDIA Corporation\NVIDIA app\NvConfig\LocalizedConfig.json`)

2. Modify the file `LocalizedConfig.json` to apply the changes, so you can log in your Nvidia account via Nvidia (Global) or Nvidia (Mainland China) as you desire!

## cn-LC.json (Mainland China users only 仅限中国大陆用户)
This is for Mainland Chinese users, or those who registered their Nvidia accoubt via the CN site. (Usable inside and outside Mainland China). This is what you'll see in the json file if you've recently been connected to a Mainland Chinese Wi-Fi network (it's weird but it seems to be the case)

## en-LC.json (Global)
This is for global users (the global site is not usable in Mainland China!)
