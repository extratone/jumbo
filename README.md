# Tiny-Theme-for-Micro.blog

- [Introduction](#introduction) and Demo
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Bio](#bio)
- [Customization](#customization)
- [Support](#support)
- [Changelog](#changelog)

### Introduction
A custom theme for Micro.blog. It includes micro.blog specific features and an automatic dark mode (loosely based on Dracula). It has no additional scripts, no custom fonts, and only 1 media query (for dark mode). It has full support for default comments, the reply by email plugin, and the conversation on Micro.Blog plugin.

Out-of-the-box, this theme supports these Micro.blog plugins and options:
- Conversation on Micro.blog plugin
- Reply by Email plugin
- Search page plugin
- Enable comments option
- Add reply page option
- Add archive page option

[View the Demo](https://www.mattlangford.com)

### Screenshot
![Tiny Theme Screenshot GIF](https://github.com/MattSLangford/Tiny-Theme-for-Micro.blog/blob/main/screenshot.gif?raw=true)

### Installation
This theme is now listed in the plugins directory of Micro.blog. You can install with one click there. Within Micro.blog, you can instead clone this repo if you prefer (choose plugin instead of theme).

### Bio
The bio portion in the header is pulled from the "About Me" field in your Account settings on Micro.blog.

### Customization
Basic design changes can be made using CSS in your Micro.blog dashboard. Go to Design > Edit CSS. If you have existing content from a previous theme there, I suggest starting fresh. You can modify colors, spacing, sizing, and much more. To get you started, here are a few common changes.

##### Overall Site Size
While you can dig into the CSS and individually manipulate the size of individual elements on their own, I've created this theme to dynamically alter the **entire** design based on the font-size. By default, the theme uses a font-size of 18px. While you can change that to any value, I suggested keeping it between 14-22px. Copy the following code and choose your size.

```
body {font-size: 18px;}
```

##### Remove Categories from Single Posts
By default, categories are shown on individual posts. If you prefer to hide them, simply add this snippet.

```
ul.post-tags {display: none;}
```

##### Footer Content
The Tiny Theme uses Micro.blog's default Custom Footer options. In the Micro.blog "Design" section of your dashboard, click "Edit Footer". Any content added here will show in the footer of your site.

### Support
If you're having any trouble, feel free to [contact me](https://mattlangford.com/contact/). If you would like to support this project financially, [you can do that via Paypal](https://paypal.me/mattslangford).

### Changelog

#### **1.2.0**
- Added basic Microformats support
- Added category classes to allow styling of posts in the feed and single page to be customized based on category
- Added a special .note class that can be used inside paragraph tags for special information

#### **1.1.0**
- Removed the Settings Screen for the bio page. Instead, it now pulls from the "About Me" field on your account.
- Added support for Micro.blog's Bookshelf feature
- Add attribution but hidden by default

#### 1.0.6
- New fix for horizontal scrolling issue with long strings of text
- Fix for text wrap issue in nav bar for site with many nav links
- Fixed typo in CSS variables

#### 1.0.5
- Fixed alt text for logo (profile photo) in header

#### 1.0.4
- Added pagination to category pages

#### 1.0.3
- Reformatted Readme
- Removed specialized styling for visited links (still available in custom)
- Accessibility Improvements

#### 1.0.2
- Improved blockquote styling
- Fixed potential horizontal scroll on archive page
- Fixed comment spacing

#### 1.0.1
- Added screenshots
- Bug Fixes

#### 1.0.0
- Initial Release
