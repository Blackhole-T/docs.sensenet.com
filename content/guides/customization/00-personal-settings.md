---
title: "Personal settings"
metaTitle: "sensenet Admin UI - Personal settings"
description: Some guidance on what can you personalize on the Admin UI
---

There are several things that you can customize according to your taste on the Admin UI. You can do most of them in the Personal Settings page. You can open your settings by using the 'Personal settings' menuitem from the user menu.

The settings are stored in a JSON format but you can get some help with the available settings by pressing the **CTRL+SPACE** combo.

Your personal settings are stored in your browsers local storage, so it won't be there if you use another browser or clear the browser cache, but can be recreated or overwritten anytime again and if there's no custom settings in the local storage, you can see and use the admin-ui by the default settings.

## Default, Mobile, Desktop, Tablet

Some settings can depend on the device that you use. You can set different settings for these devices - and a default value that will be applied if you don't provide a setting on device level.

### Theme

You can change between **light** 🌞 and **dark** 🌜 theme.

### Content

You can set up a `browseType` - it can be `explorer` (a tree with a content list), `commander` (a two-panel view) or `simple` (just a simple content list, the best for mobile). You can also define a list of `fields` that should be displayed.

### Drawer

You can enable or disable the [drawer](/guides/customization/01-menu-customization/), change the drawer type and define a list of preconfigured items to display. The drawer types are:

- temporary, useful for mobile devices
- permanent with icons and text
- mini-variant which displays only the icon by default but can be expanded

### Command Palette

You can enable or disable the [command palette](/guides/search/03-command-palette/) and define a `wrapQuery` expression that will be added to any command palette query.

## Dashboard

You can customize your `globalDefault`and`repositoryDefault` [dashboards](/guides/customization/05-dashboard-customization/) here.

## Repositories

Your `repositories` are also stored in the personal settings with an `url` and the last user's `loginName`. You can also define a user-friendly `displayName` (that will be displayed as the repository's title instead of the URL) and you can also override the repository's default _dashboard_

## Last used repository

The last used repository's URL is also stored in your settings in the `lastRepository` field. This field will be updated automatically when you switch between repositories.

## Language

You can select between the `default` (english) and `hungarian` language with the `language` field.

## Events and logging

You can define the size of the event log with the `eventLogSize`. Only the last N entries will be saved. There is another setting for the entries to persist in the log: the `logLevel` field. You can also enable / disable attaching the log when you send a crash report with the `sendLogWithCrashReports` field.

![Changing the theme in the personal settings](../img/personal_settings.gif "Changing the theme in the personal settings")
