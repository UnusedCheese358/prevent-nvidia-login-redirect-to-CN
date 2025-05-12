(Disclaimer: The scripts are made by Nvidia, not by me. I just somehow found a way not to get forcefully redirected when logging in my Nvidia account)

TODO: The description will be updated later, stay tuned! 



# Switch Nvidia app login region with ease!
Are you one of the victims of being forcefully redirected to Nvidia CN site when logging in with your global account?
Fear not, look no further than here!

# More about the json files posted

## How do I switch between global and CN when logging in with my Nvidia account via the Nvidia App?
The json file `LocalizedConfig.json`  (located in your drive where you installed your Nvidia App, such as `C:\ProgramData\NVIDIA Corporation\NVIDIA app\NvConfig\LocalizedConfig.json`) changes your login site depending on your region.
Modify the file `LocalizedConfig.json` to apply the changes, so you can log in your Nvidia account via Nvidia (Global) or Nvidia (Mainland China) as you desire!

## cn-LC.json
This is for Mainland Chinese users. (Usable inside and outside Mainland China)

## en-LC.json
This is for global users (not usable in Mainland China!)
