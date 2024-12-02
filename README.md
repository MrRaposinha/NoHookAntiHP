### **No Hook AntiHP v1.0.0 - Penalty-Free Gameplay**

**No Hook AntiHP** is a simple yet powerful mod for ULTRAKILL, designed to offer a more relaxed and penalty-free gameplay experience. By eliminating the effects of AntiHP, it lets players focus on movement, combat, and exploration without the worry of style penalties tied to mechanics like the HookArm.

---

## 🌟 Features

1. **Disable HookArm AntiHP**:
   - Prevents the accumulation of AntiHP when using the HookArm, allowing unrestricted use of the hook for movement and combat without penalties.

2. **Disable All AntiHP**:
   - Completely removes the AntiHP system, ensuring no penalties are applied in any context, regardless of gameplay mechanics.

3. **Configurable Options**:
   - Powered by **Configgy**, the mod includes a graphical interface where players can toggle these features:
     - **Disable HookArm AntiHP**: Blocks AntiHP only for the hook.
     - **Disable All AntiHP**: Resets the player's AntiHP to zero whenever an increase is detected.

---

## 🚧 How It Works

The mod dynamically interacts with ULTRAKILL's core systems:
- **HookArm Monitoring**: Constantly tracks the HookArm's usage to prevent AntiHP from being applied.
- **Global AntiHP Reset**: Monitors the player's AntiHP value and resets it to zero whenever an increase is attempted.
- **Seamless Integration**: Built with BepInEx, the mod modifies systems like `NewMovement` and `HookArm` to ensure compatibility and smooth performance.

---

## 📥 Installation

### Requirements
- **BepInEx**: This mod requires BepInEx to function. Ensure it’s installed in your ULTRAKILL directory.

### Steps to Install
1. Download the latest release of **No Hook AntiHP** from the [Releases](https://github.com/YourRepo/NoHookAntiHP/releases) page.
2. Place the `NoHookAntiHP.dll` file in your `BepInEx/plugins` folder.
   - If the `plugins` folder doesn’t exist, create it manually.
3. Launch ULTRAKILL and customize the mod’s settings via the in-game Configgy menu.

---

## 🎮 Who Is This Mod For?

This mod is ideal for:
- **Casual Players**: Those who want to explore ULTRAKILL without penalties for using mobility mechanics.
- **Fans of Relaxed Gameplay**: Players seeking a more forgiving experience where AntiHP mechanics no longer hinder their enjoyment.
- **Experimenters**: Gamers who love to push ULTRAKILL's mechanics to the limit without the complexity of style penalties.

---

## 🔧 Troubleshooting

If the mod isn’t working:
1. Verify that **BepInEx** is properly installed.
2. Ensure the mod file is in the correct `BepInEx/plugins` directory.
3. Check the game logs (`BepInEx/LogOutput.log`) for errors.

For further support, visit the [Issues](https://github.com/YourRepo/NoHookAntiHP/issues) section of this repository.

---

## 🤝 Contributing

Want to refine this mod or suggest new features? Contributions are welcome! Here’s how:
1. Fork this repository.
2. Create a new branch for your changes.
3. Submit a pull request with a description of your updates.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

Thank you for trying out **No Hook AntiHP**! Enjoy a penalty-free adventure in ULTRAKILL, where movement and combat flow freely without interruptions. 🎮🔥
