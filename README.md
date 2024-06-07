# JetBrains New UI Themes for [Zed](https://zed.dev/)

<p align="center">
	<a href="https://github.com/kpitt/zed-theme-intellij-newui/stargazers"><img alt="GitHub Stars" src="https://img.shields.io/github/stars/kpitt/zed-theme-intellij-newui?style=for-the-badge&labelColor=393B40&color=3574F0"></a>
	<a href="https://github.com/kpitt/zed-theme-intellij-newui/issues"><img alt="GitHub Issues" src="https://img.shields.io/github/issues/kpitt/zed-theme-intellij-newui?style=for-the-badge&labelColor=393B40&color=BD5757"></a>
	<a href="https://github.com/kpitt/zed-theme-intellij-newui/contributors"><img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/kpitt/zed-theme-intellij-newui?style=for-the-badge&labelColor=393B40&color=24A394"></a>
</p>

This is a dark theme for the [Zed editor](https://zed.dev/) based on the UI theme and editor colors from the "New UI" for the JetBrains IntelliJ platform.  Currently, only the new "Dark" theme is implemented, but I plan to eventually add support for the "Light" and "Light with Light Header" themes as well.

The colors used for syntax highlighting should be an exact match to IntelliJ. However, some elements won't be highlighted in exactly the same way due to differences in the syntax queries.

The UI elements are a bit trickier, but I believe this comes close enough to at least be in the _spirit_ of the JetBrains New UI.  The Zed theme system is relatively new, and is still somewhat limited compared to the complexity of IntelliJ or even VSCode.  The documentation is also very minimal at this point, so determining which theme color controls a particular UI element, or finding all the different ways that a particular color might be used, still requires a lot of trial-and-error and searching of the Zed source code.

The Zed editor and its theme system are still evolving rapidly, so the behavior of the theme colors could change at any time.  If you notice an unexpected change in the appearance after installing a Zed update, please [create a GitHub issue](https://github.com/kpitt/zed-theme-intellij-newui/issues/new/choose), preferably including screenshots of both the before and after appearance.

## Usage

### Install via Zed Extensions

(future: not yet published to Zed Extensions reposiory)

1. Open Zed
2. Press `cmd+shift+p` and select _zed: extensions_
3. Select _JetBrains New UI Theme_ and Install
4. Press `cmd+k` `cmd+t` and select _JetBrains New Dark_ in the theme picker

### Install Manually

1. Download the [intellij-newui.json](./themes/intellij-newui.json) theme file
2. Put the theme file into `~/.config/zed/themes/`

### Enable the Theme

1. Press `cmd+k` `cmd+t`, or choose _Settings... > Select Theme..._ from the Zed menu
2. Select _JetBrains New Dark_ in the theme picker

## Known Issues

- Starting in Zed 0.137.2, there was a change that broke the ability to properly theme some of the UI buttons.  This affects the hover style most, but also changes some of the normal button backgrounds.  I opened [issue #12592](https://github.com/zed-industries/zed/issues/12592) in the Zed repository for the hover styling.

---

<p align="center">
  <a href="https://github.com/kpitt/zed-theme-intellij-newui/blob/main/LICENSE.txt"><img alt="License" src="https://img.shields.io/github/license/kpitt/zed-theme-intellij-newui?style=for-the-badge&labelColor=393B40&color=3574F0"></a>
</p>
