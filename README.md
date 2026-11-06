# Skorp7 Engine

A 3D engine and editor for Windows, built so that people and AIs can work in the same scene at the same time.

**Get it:** install Skorp7 Launcher from [skorp7.com](https://skorp7.com), then install the engine from [its page](https://skorp7.com/AppPage.php?slug=Skorp7Engine). The launcher is the only way to install it, and it keeps the engine up to date.

This is an alpha: expect rough edges, and keep copies of your projects.

## How it works

**The editor.** Viewports, an outliner, a details panel, a content browser, gizmos with snapping, undo and redo, and as many windows as you want. Import glTF and FBX models, whole or split into one object per node, with their animations. A timeline holds clips, keyframes, markers and camera cuts.

**The renderer.** Real-time, with soft shadows from every lamp, bounce light, reflections, volumetric light, depth of field and motion blur, plus a path traced view.

**Your game.** Walk your scene in first person from the editor, then File > Package Game makes a folder anyone can play without the engine. A project can also start your own game program with Play.

**AIs work beside you.** The engine runs a local API, on your computer only. Press Copy AI prompt, paste it into any AI coding assistant, and it connects to the scene you have open. Each AI gets its own mouse, keyboard, selection and clipboard inside the engine, so several AIs and you can work at once and your own mouse is never touched. You see each AI's pointer with its name. A text box an AI is typing in is locked for you, and the same goes the other way. Undo is shared, and everything keeps working while the engine is minimised.

**AIs can ask you things.** When an AI needs a decision, a question window stays on top until you press a key, and your answer goes straight back to it.

**Problem reports.** When an AI finds something missing, it can send an anonymous report so it gets fixed, at most 5 a day. You can turn this off in the AI menu.

## Requirements

Windows 10 or 11, 64-bit, and a graphics card with OpenGL 3.3.

## Plugins

Anyone can make plugins, in any language, and post or share them however they like. It costs nothing and you owe nothing. A plugin is a folder with a small `plugin.json` and your program or script; its commands show up in the Plugins menu, and it works through the same local API as the AIs. Plugins stay off until you turn them on.

## License

Free to use, including for commercial work, and what you make with it is yours. Reverse engineering and redistributing the engine are not allowed. Plugins are free to make and distribute.

Games and apps may ship the engine's runtime files. A game or app with a budget of GBP 100,000 or less pays nothing, ever. A bigger one pays 2.8% only on its revenue above its first GBP 500,000, and nothing is reported before that. Films, renders, assets and services pay nothing. No credit or splash screen is required.

See [LICENSE](LICENSE) for the full terms, which no lawyer has reviewed yet. The libraries it includes keep their own licences, listed in THIRD_PARTY_NOTICES.md.
