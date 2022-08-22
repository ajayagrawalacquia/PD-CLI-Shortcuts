# Pager Duty CLI Shortcuts
## _Automate your HotSeat like Never Before_ 💪


This is NOT an entirly New Tool but a set of Functions which are written using the Already Existing Pager Duty CLI Tool.
And hence, The Major Dependency to use this is to have the existing tool Installed on your Computer.


Please download the tool from [Here](https://github.com/martindstone/pagerduty-cli) or you can follow any of ther Installation Methods mentioned [In this Page](https://github.com/martindstone/pagerduty-cli/wiki/PagerDuty-CLI-User-Guide)

Once you've Installed the PaderDuty CLI from the GitHub Link provided above. Please run the below bunch of Commands to get the Functions in your bashrc & Start using the Shortcuts 😊
```sh
mkdir ~/Documents/PDCLI
cd ~/Documents/PDCLI
git clone https://github.com/ajayagrawalacquia/PD-CLI-Shortcuts.git
cd PD-CLI-Shortcuts
echo 'PDCLIFUNCS=~/Documents/PDCLI/PD-CLI-Shortcuts/PDFunctions' >> ~/.bashrc
echo 'source $PDCLIFUNCS' >> ~/.bashrc
source ~/.bashrc
plsA
```

If  `plsA`  works and gives you output such as
```sh
Getting incidents 1/1 👍, 0/1 👎... done
```

Congratulations ✨ You've Successfully Installed PagerDuty CLI and got those functions on your Bashrc 🔥

This Tool has a lot of Potential to Automate a lot of things when it comes to PagerDuty and Hence, It'll feel like a blessing on the days when we have really busy Hotseats 😊


## Below is the brief of what the functions are capable of performing

- List all the Incidents which are assigned to you (or all if you wish to) on Pagerduty.
- Acknowledge all the Incidents assigned to you (or all if you wish to) on PagerDuty.
- Resolve all the Incidents assigned to you (or all if you wish to) on PagerDuty.
- Resolve Individual Alerts from PD.
- Automatically keep Acknowleding all the Incidents assigned to you (or all if you wish to) in every 15 seconds on PagerDuty.
- Can Quickly give you names of the Engineers who are in Primary and Secondary Hotseat currently.

> Offcourse, This is just a Start and there are a lot of Functions that can be created more based upon our needs.


## Let's Discuss Functions now ✨  Shall We 😊
---

To **List** all the Incidents which are Assigned to **You**
```sh
pls
```

To **List** all the Indicents on PD (Regardless it's assigned to you or not)
```sh
plsA
```

To **Acknowledge** all the Incidents which are Assigned to **You**
```sh
packall
```

To **Acknowledge** all the Indicents on PD (Regardless it's assigned to you or not)
```sh
packallA
```

To Keep Acknowledging All the Incidents assigned to **you** on PD in **Every 15 Seconds**
```sh
packloop
```

To Keep Acknowledging All the Incidents on PD (Regardless it's assigned to you or not) in **Every 15 Seconds**
```sh
packloopA
```

To **Resolve** Individual Indicents on PD
```sh
pres
```

To **Resolve** all the Incidents which are Assigned to **You**
```sh
presall
```

To **Resolve** all the Indicents on PD (Regardless it's assigned to you or not)
```sh
presallA
```

To Display who is in Primary and Secondary Hotseat Currently
```sh
pdoc
```

_Note:_ `pdoc` _function will display only the Hotseat details of **Ops Team** here. If you are from any other team, Please change the **Team ID** in the function. You can check your Team ID using_ `pd ep:list`

Whatever mentioned above is just the description of what ***Functions*** do and not about what the tool is capable of. Feel free to read about all the functionalities this tool provides [Here](https://github.com/martindstone/pagerduty-cli)

You can consider this as a Shortcut of using the actual PD CLI effectively 😊 

_As this will be always a Work In Progress based upon the needs of the Team, Feel free to Contribute and let's make the Hotseat a little Cool 😉_

Enjoy 🔥
