# TransparentFirefox!

![Screenshot](https://github.com/muhammadfaruq72/TransparentFirefox/assets/51035641/4d6b017c-2476-46c6-8d2f-b4d4505ad232)

# Installation


1 - Visit about:config
Search for toolkit.legacyUserProfileCustomizations.stylesheets, set it to true
While you're here, you can enable other customizations you may want here.

2 - Visit about:support
In the Profile Directory row, copy the full path
May look something like: /home/{username}/.mozilla/firefox/...

3 - If there is no chrome" folder, create one.
4 - Then, inside the chrome folder, create a file called "userChrome.css", Copy & Paste the contents of userChrome.css into the file.

5 - Install Sidebery https://addons.mozilla.org/en-US/firefox/addon/sidebery/
6 - Add This style to Sidebery Styles Editor.

`
#root.root {--tabs-progress-bg: #ffffffff;}
#root.root {--tabs-activated-fg: #000000ff;}
#root.root {--tabs-activated-bg: #efefefff;}
#root.root {--general-margin: 4px;}
.NavigationBar {
  display: none;
}
`

7 - Make sure to Customise toolbar, Add/Remove Spaces.
8 - If you have any issues with Close/Minimize Buttons on windows or Mac try to alter these CSS properties in "min-one-line/userChrome.css" file.

`
.titlebar-buttonbox-container {
  display: block !important;
  position: absolute !important;
  top: 13px;
  left: 4px;
}
`
