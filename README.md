# Gamepad button glyphs addon
This addon will help you change xbox one button glyphs to another set of glyphs that are already shipped with the game, but unavailable through normal settings.

It works by explicitly remapping xbox textures to a selected variation.

To install, unpack zip in your `<My Documents>\Elder Scrolls Online\live\AddOns` (it should look like `AddOns\CustomGamepadButtons\<addon files here>`).

In-game UI settings require additional addon [LibHarvensAddonSettings](https://www.esoui.com/downloads/info584-HarvensAddonSettings.html).

Or you can use `/script ButtonsManager:ChangeButtonsTo("switchpro")` command in chat.

# Development info
Official ESO UI SDK: https://github.com/esoui/esoui

IntelliJ completion library files (add path to the extracted folder to `lua.workspace.library` in VSCode): https://github.com/Baertram/IntelliJ_ESOUI_AutoCompletion/tree/main/Releases

Manifest format: https://wiki.esoui.com/Addon_manifest_(.txt)_format