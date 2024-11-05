# Touhou Game Selector

I have created this application as i am working on making an arcade cabinet for Touhou Project. I wanted a way to be able to launch the games using just the cabinet buttons. 
(Keyboard and mouse will only be needed for the initial setup). I thought it would be nice to share it with the public. The appearance may be a bit meh and the code is a bit dirty but it works and i plan on improving the code and appearance in future.

**Support for Touhou 1 through to 19**

# How to use
This is the selection screen. It is pretty basic, bear in mind that this is the first version. The controls are displayed on the screen. It is pretty straight forward to use.

- `Down Arrow` to increment. 
- `Up Arrow` to decrement. 
- `Z` to Launch the selected game. 
- `X` to exit. 

In the future i may implement custom keybinds. 
You will not be able to launch anything until you configure the paths, so lets take a look at the configuration page.
![image](https://github.com/user-attachments/assets/c0b8b1a6-2bc8-4482-8f1c-2af1115d2827)


# Compatibility
- .NET Framework 4.0
- Tested and working on Windows 7 and 11.
- Tested and working on Windows XP x64. (However, some of the later games are incompatible with XP)

  
**Conclusion?**
- **Supports Windows XP to Windows 11 (64-Bit)**
- **Yet to be tested on 32-Bit machines.**




# DOSBox-X PC-98 Config
This launcher uses custom .conf files for DOSBox-X. I used the default config as a template and changed these values.


[dosbox]
`machine = pc98`
`memsize = 64`

[cpu]
`cputype = 486`

[autoexec]
`imgmount c C:\PC98\TH04.HDI`
`boot c:`

I did this for each game (1-5). 
Pretty basic DOSBox-X stuff. :)

# Configuration
This is the configuration page. You can get here by pressing `ALT + C` Here you can set the location of your games. 

On this page you need to select your games and hit save. **Your changes will be kept.**

![image](https://github.com/user-attachments/assets/57402004-4e32-454b-b9b3-fab3d1c9ba33)




Now the launcher is ready to go. Enjoy!

# Planned Features
- Ability to disable/enable games in the menu.

