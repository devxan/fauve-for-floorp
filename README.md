# Fauve for Floorp

A simple [Sidebery](https://github.com/mbnuqw/sidebery) CSS file for use with (a specific configuration using) [Floorp](https://floorp.app/) or a modification of Firefox.

![Screenshot of the full browser with Sidebery opened and a Fauve for Firefox/Sidebery logo](images/thumbnail.png "Fauve for Floorp/Sidebery logo on top of Floorp with Sidebery panel enabled")

## Installation

1. Install [Sidebery](https://github.com/mbnuqw/sidebery/) from the [addon page](https://addons.mozilla.org/firefox/addon/sidebery/).
2. In Floorp, go to `about:preferences` and locate _Design_ in the navigation. Use the following options:

### Enable

- Firefox Photon • Lepton UI
  - _Automatically hide browser elements >_ Automatically hide Sidebar
  - _Manage browser elements >_ Hide Sidebar Headers
- _Tab Bar >_ Optimise browser for Vertical Tab Bar

### Disable

- _Firefox Photon • Lepton UI > Tab Bar >_ Combine Tab Bar and Toolbar
<details>

<summary>Optional options that Xan enabled</summary>

### Optional

- _Firefox Photon • Lepton UI_
  - _Lepton Settings >_ Use tweaked Proton design
  - _Automatically hide browser elements >_ Automatically hide back button
  - _Automatically hide browser elements >_ Automatically hide forward button
  - _Manage browser elements >_ Enable Lepton's context menu icons
- _Bookmarks Toolbar >_ Show the Bookmarks Toolbar at the bottom of Floorp
- _Navigation Bar >_ Show the Toolbar at the bottom of Floorp

</details>

### Continued installation

3. Open Sidebery settings and locate _Styles editor_ in the navigation. Paste the contents of [sidebery.css](sidebery.css) into the panel that says "Write custom CSS here..."
4. Find a theme, like Catppuccin, Dracula, Gruvbox, Noir, Nord, Tokyo Night, or . (optional)
5. Enjoy your new setup! (optional)

## Additional notes and known issues

- Due to the width of the tabs, if marks to indicate indentation is enabled, multiple lines may show. This can be fixed by increasing the width of tabs.
- You might want to use a theme, like the [Catppuccin Mocha Mauve](https://addons.mozilla.org/en-US/firefox/addon/catppuccin-mocha-mauve-git/) theme used in this repos images.
- To replicate this setup in a much more limited -but possibly better integrated fashion- enable these options instead:
  - _Design > Tab Bar Style >_ Vertical Tab Bar
    - Collapse Vertical Tab Bar


## Credits

- to [Xan](https://xan.lol/) for finally using Floorp after recomemnding it to another person a year prior
- to [@mgastonportillo](https://github.com/mgastonportillo) for their [Gale for FF](https://github.com/mgastonportillo/gale-for-ff)
- to [u/captainkaba](https://www.reddit.com/user/captainkaba/) for his [Denkfabrik](https://www.reddit.com/r/FirefoxCSS/comments/rqo5z6/some_people_asked_for_the_css_so_here_is_my_setup/) theme (which was used as a base)
- to Reddit user [u/It_Was_The_Other_Guy](https://www.reddit.com/user/It_Was_The_Other_Guy/) for his [tip](https://www.reddit.com/r/FirefoxCSS/comments/vzcqzn/comment/ig8a8ba/)