# Soliton

Watch Snake sneak through a different facility each run. He slips through vents, grabs keycards and tries to reach the exit before the patrols catch him. Soliton is a small, autonomous stealth game inspired by the radar in *Metal Gear Solid*.

## Download

| Platform | Download | Start the game |
| --- | --- | --- |
| Windows x64 | [ZIP](https://github.com/Phobiastrike/Soliton/releases/download/v1.0.7/Soliton-Portable-1.0.7-Windows-x64.zip) | Extract the whole folder and open **Soliton.exe**. |
| Mac with Apple silicon (M-series) | [macOS ARM64 ZIP](https://github.com/Phobiastrike/Soliton/releases/download/v1.0.7/Soliton-1.0.7-macOS-arm64.zip) | Extract the ZIP, move **Soliton.app** to Applications and open it. |
| Mac with Intel processor | [macOS Intel ZIP](https://github.com/Phobiastrike/Soliton/releases/download/v1.0.7/Soliton-1.0.7-macOS-x64.zip) | Extract the ZIP, move **Soliton.app** to Applications and open it. |
| Ubuntu / Debian x64 | [Debian package](https://github.com/Phobiastrike/Soliton/releases/download/v1.0.7/Soliton-1.0.7-Linux-amd64.deb) | In the download folder run `sudo apt install ./Soliton-1.0.7-Linux-amd64.deb`, then open **Soliton** from the applications menu. |
| Other desktop Linux x64 | [tar.gz](https://github.com/Phobiastrike/Soliton/releases/download/v1.0.7/Soliton-1.0.7-Linux-x64.tar.gz) | Extract the archive and run `./Soliton/soliton`. Requires desktop libraries and a working Chromium sandbox. |

The Mac builds require macOS 13 or later. They are ad-hoc signed and have no Apple notarization. macOS may ask for approval on first launch. [Apple's guide to opening downloaded apps](https://support.apple.com/en-us/102445)

Soliton runs offline. Windows stores progress in `data/state.json` beside the executable. macOS uses `~/Library/Application Support/Soliton/state.json`. Linux uses `$XDG_CONFIG_HOME/Soliton/state.json`, normally `~/.config/Soliton/state.json`. Press **Space** to pause, **M** to mute or **Esc** for options.

![Snake on the infiltration radar with one of two keycards collected](https://github.com/Phobiastrike/Soliton/releases/download/v1.0.7/infiltration-keycards.png)

*Infiltration.* Snake has one of the two cards that unlock this sector. The blue cones show where guards and cameras can see him.

![The same sector in red alert as a wall turret fires](https://github.com/Phobiastrike/Soliton/releases/download/v1.0.7/turret-alert.png)

*Alert.* A wall turret catches Snake in its sights. If he breaks contact, the radar turns yellow while the guards search.

![Colonel Campbell briefing Snake on CODEC frequency 140.85](https://github.com/Phobiastrike/Soliton/releases/download/v1.0.7/codec-14085.png)

*CODEC, 140.85.* Colonel Campbell briefs Snake at the start of each sector. You can switch off calls in the options.

Unofficial fan project. [Credits and asset sources](CREDITS.md).
