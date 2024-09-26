<!-- LTeX: enabled=false -->
# Alfred dock switcher
<!-- LTeX: enabled=true -->
![Download count](https://img.shields.io/github/downloads/chrisgrieser/alfred-dock-switcher/total?label=Total%20Downloads&style=plastic)
![Version number](https://img.shields.io/github/v/release/chrisgrieser/alfred-dock-switcher?label=Latest%20Release&style=plastic)

Switch between dock layouts.

<img alt="Showcase" width=70% src="https://github.com/user-attachments/assets/ac0d7d3e-f323-46da-96a3-66744d89b57c">

## Usage
- Save the current dock as a layout for this workflow via the keyword `:dock
  new`.
- Select a dock layout via the keyword `dock`:
	+ <kbd>⏎</kbd>: Switch to the layout (load the layout).
	+ <kbd>⌘⏎</kbd>: Overwrite the layout with the layout of the current dock.

> [!WARNING]
> This workflow saves **all** information related to the current dock. This
> includes dock sizes, dock position, animation settings, or hot corners.

## Automation
Load a dock layout from another app via this AppleScript:

```applescript
tell application id "com.runningwithcrayons.Alfred" to run trigger "load-dock-layout" in workflow "de.chris-grieser.dock-switcher" with argument "NAME_OF_DOCK_LAYOUT"`
```

or via URI:

```txt
alfred://runtrigger/de.chris-grieser.dock-switcher/load-dock-layout/?argument=NAME_OF_DOCK_LAYOUT
```

## Installation
[➡️ Download the latest release.](https://github.com/chrisgrieser/alfred-dock-switcher/releases/latest)

When admitted to the Alfred Gallery, the workflow auto-updates via Alfred's
workflow-update mechanism.

<!-- vale Google.FirstPerson = NO -->
## About the developer
In my day job, I am a sociologist studying the social mechanisms underlying the
digital economy. For my PhD project, I investigate the governance of the app
economy and how software ecosystems manage the tension between innovation and
compatibility. If you are interested in this subject, feel free to get in touch.

- [Academic Website](https://chris-grieser.de/)
- [Mastodon](https://pkm.social/@pseudometa)
- [ResearchGate](https://www.researchgate.net/profile/Christopher-Grieser)
- [LinkedIn](https://www.linkedin.com/in/christopher-grieser-ba693b17a/)

<a href='https://ko-fi.com/Y8Y86SQ91' target='_blank'>
	<img
	height='36'
	style='border:0px;height:36px;'
	src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3'
	border='0'
	alt='Buy Me a Coffee at ko-fi.com'
/></a>
