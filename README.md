# Fauve for Floorp

![The Sideberg logo put inside the Floorp logo](images/logo.png "Fauve for Floorp")

A simple [Sidebery](https://github.com/mbnuqw/sidebery) CSS file for use with (a specific configuration using) Floorp or a modification of Firefox.

Xan uses the [Catppuccin Mocha Mauve](https://addons.mozilla.org/en-US/firefox/addon/catppuccin-mocha-mauve-git/) theme with it.

My goal with these settings was to create a minimalistic yet functional setup
with Sidebery tuned to match Firefox Default Dark Theme and optimise the
workspace. If you find any odd behaviour feel free to send a pull request.

![Screenshot of the full browser with Sidebery opened](images/thumbnail.png)

## How to install?

1. In Firefox, go to `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `True`. Make sure you have the [chrome folder](https://www.userchrome.org/how-create-userchrome-css.html) within your Firefox profile
2. Get [Sidebery v5 (beta)](https://github.com/mbnuqw/sidebery/) if you don't have it already installed
3. Copy `userChrome.css`, `darkTheme.css` and `private.css` to the chrome folder
4. Go to Sidebery settings and paste the content of my `sidebery.css` file into _Styles editor > Sidebar_
5. Enjoy your new setup!

Set these settings under appearance in Sidebery (optional but recommended):

![Recommended settings to change in Sidebery](images/sidebery-appearance.png)

## Known issues

- Due to the width of the tabs, if marks to indicate indentation is enabled, it might produce multiple lines. This can be fixed by increasing the width of tabs.

## Credits

- to [@mgastonportillo](https://github.com/mgastonportillo) for their [Gale for FF](https://github.com/mgastonportillo/gale-for-ff)
- to [u/captainkaba](https://www.reddit.com/user/captainkaba/) for his [Denkfabrik](https://www.reddit.com/r/FirefoxCSS/comments/rqo5z6/some_people_asked_for_the_css_so_here_is_my_setup/) theme (which was used as a base)
- to Reddit user [u/It_Was_The_Other_Guy](https://www.reddit.com/user/It_Was_The_Other_Guy/) for his [tip](https://www.reddit.com/r/FirefoxCSS/comments/vzcqzn/comment/ig8a8ba/)