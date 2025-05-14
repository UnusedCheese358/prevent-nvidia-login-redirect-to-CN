Disclaimer: The scripts are made by Nvidia, not by me. I just somehow found a way not to get forcefully redirected when logging in my Nvidia account
宇宙通用免责声明：这些 json 档都是 Nvidia 编写出来的，非本人创作。只是我在 Nvidia 账户登录时，找到了不会被强制重定向的方法而以。

# Change the region of the website when logging in your NVIDIA account with ease! 轻松切換 NVIDIA 账号登陆网站地区
Are you, for some reason, unable to log in your Nvidia (Global) account repeatedly because it constantly takes you to the CN site instead of the global site when you're not in Mainland China physically? Do you want to change the region of the website when logging in your NVIDIA account with ease? Look no further! These scripts will help you achieve that.
你是否因为某些原因，尽管你人并不在大陆范围，还是不断无法透过 Nvidia (全球) 登陆 NVIDIA 账号，因为每次登陆时都会被强制重定向到国区 (CN) 站点，而并非全球站点？ 你是否想轻松切换 NVIDIA 账号登陆网站地区？这些脚本将会帮助你实现这一点。

# What's going on? 发生什么事了？
When you try to log in to your Nvidia account, it will always redirect you to the cn site. This is because the Nvidia website is set to redirect to the region of your IP address automatically. For example, you've recently been to Mainland China, and now your Nvidia account is set to redirect to the cn site. This can be frustrating, especially if you want to access the global site.
当你尝试透过 NVIDIA APP 登陆 NVIDIA 账号时，它会一直重定向到国区 (CN) 站点。这是因为 NVIDIA 网站会根据你的 IP 地址自动向到相应地区。例如，你最近访问过大陆范围， NVIDIA 账号现在会被设置为重定向到国区 (CN) 站点。这会让人很恼火，尤其是当你想访问全球站点时。


But what if you want to log in to the global site instead? That's where these json scripts comes in. They will change the region of the website when logging in your NVIDIA account with ease.
但如果你想透过全球站点登陆 NVIDIA 账号呢？这就是这些 json 脚本的作用。它会轻松改变 NVIDIA 账号登陆网站地区。

# More about the json files posted 多点关于我发出来的 json 档

## How do I switch between global and CN login site when logging in with my Nvidia account via the Nvidia App? 我如何透过 NVIDIA APP，切换全球站点和国区站点登陆 NVIDIA 账号？
1. Locate the json file `LocalizedConfig.json`  (By default and in most cases, the json file should be located in C drive, where you installed your Nvidia App. In my case:  `C:\ProgramData\NVIDIA Corporation\NVIDIA app\NvConfig\LocalizedConfig.json`) 找到 json 档 `LocalizedConfig.json` (正常情况下，json 档位于你安装 NVIDIA APP 的 C 盘，例如：`C:\ProgramData\NVIDIA Corporation\NVIDIA app\NvConfig\LocalizedConfig.json`)。

2. Modify the file `LocalizedConfig.json` to apply the changes, so you can log in your Nvidia account via Nvidia (Global) or Nvidia (Mainland China) as you desire! 通过修改 json 档 `LocalizedConfig.json` 来应用改变，透过 NVIDIA (全球) 或 NVIDIA (中国大陆) 登陆 NVIDIA 账号。

## cn-LC.json (For Mainland China registered users 国区站点注册用户使用)
This is for Mainland Chinese users, or those who registered their Nvidia accoubt via the CN site. (Usable inside and outside Mainland China). This is what you'll see the things coded in the json file if you've recently been connected to a Mainland Chinese Wi-Fi network (it's weird but it seems to be the case, it just changes it automatically)
这是为大陆中国用户，或者那些透过国区站点注册 NVIDIA 账号 的用户。 (可在大陆中国范围内和外使用)。如果你最近连接过大陆中国 WLAN 网络，你会在 json 档中看到这个 json 档的内容（这很奇怪，但似乎是这样）。

## en-LC.json (Global users only 仅限全球站点注册用户使用)
This is for global users (the global site is not usable in Mainland China!)
僅供全球站点注册用户使用，全球站点并不能在中国大陆地区使用。
