# **BetterSave**
This mod saves information that the game does not save, such as computer and listening panel state.

**⚠️WARNING⚠️ This mod is designed to work with VotV-0.8.2c_0011. Using older or newer versions of the game may cause errors!**  

If you have any suggestions or find a bug, you can submit it as an "issue" in my [GitHub repository](https://github.com/Acitulen/BetterSave).

**⚠️ Many features were removed because they are now part of the base game.**

---

# Configs:
Configs can be accessed in the game settings under the **Mod configs** category or by pressing **Ctrl+Shift+C**.

- **SaveComputerData** – Enables saving the computer's power state and the currently opened tab. Default: true  

- **SaveListenerData** – Enables saving the state of the signal listening panel, including volume and visualization mode. Default: true  

---

# **Saveable data**: 
### Computer:
- Power state (on/off)  
- Opened tab

### Signal Listening Panel:
- Volume  
- Visualization mode

---

# **Manual instalation guide**.

<details>
<summary>Install unreal shimloader</summary>

1. Copy `dwmapi.dll` into the `GAME/Binaries/Win64` directory. Its new path should be `GAME/Binaries/Win64/dwmapi.dll`.
2. Copy the contents of the `UE4SS` folder in the package into `GAME/Binaries/Win64`.

`GAME/Binaries/Win64` should now contain the following *new* files and folders:
- `GAME-Win64-Shipping.exe`
- `ue4ss.dll`
- `UE4SS-settings.ini`
- `dwmapi.dll` ← *This is the unreal-shimloader binary. It will load UE4SS for you.*
- `Mods/`
</details>

<details>
<summary>Install BetterSave</summary>

1. Copy `BetterSave.pak` from the `pak` folder to `GAME/Content/Paks/LogicMods` directory. 
</details>

