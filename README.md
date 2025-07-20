This is unfinished and discontinued, go ahead if you want to finish this or look at for learning purposes.

**[Simple setup]**
- Put it into Roblox Studio and then make the UI into a package, it should look like this if you done it properly
<img width="321" height="34" alt="RobloxStudioBeta_LsImNDUvYh" src="https://github.com/user-attachments/assets/fc2b7df9-83eb-4ede-bc0c-7c65fa423c82" />

- Grab your package id and go into the Library module and replace the variable packageId value to yours.
<img width="334" height="23" alt="RobloxStudioBeta_lQp3GDNonw" src="https://github.com/user-attachments/assets/59bb911f-1dac-4943-b9c6-659ee4528798" />
<img width="92" height="20" alt="RobloxStudioBeta_euEbhGOvA2" src="https://github.com/user-attachments/assets/a281c6c8-dd92-4543-947f-359233c81367" />

```lua
local packageId = "yourId"
```
- Now you can do whatever you like to the UI components, you can execute the example code by copying and pasting the Library module code into the Roblox Studio console bar
<img width="2137" height="55" alt="RobloxStudioBeta_ToqGOtknXc" src="https://github.com/user-attachments/assets/fa0d8da9-8a7d-46e6-a7a7-068e7fff4f8a" />

**[Small notes]**
- Toggle, Slider is finished
- ColorPicker, Dropdown, TextBox, Buttons, Popups, are unfinished
- "Settings" are case insensitive, example below

```
Library:createTab({texT = "hi"}) 
Library:createTab({text = "wow"}))
```

**[Picture]**

<img width="869" height="666" alt="RobloxStudioBeta_eAiYF6y016" src="https://github.com/user-attachments/assets/740d051d-026f-464a-962b-148a75db0012" />
