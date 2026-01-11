# Holiday Countdown Plugin

A festive countdown plugin for TRMNL that displays the number of days until your special event with themed emoji decorations.

<a href="https://usetrmnl.com/recipes/188160">
  <img src="https://usetrmnl.com/images/brand/badges/dark/show-it-on-trmnl/trmnl-badge-show-it-on-dark.svg" alt="TRMNL Badge" width="120">
</a>

## Overview

This plugin creates a visually engaging countdown to any date you choose. Perfect for holidays, birthdays, vacations, weddings, or any special event you're looking forward to. The display features themed emojis that match your occasion and shows a custom message when the big day arrives.

## Features

- **Customizable countdown date** - Set any future date
- **15+ themed emoji sets** - Match the countdown to your event
- **Custom text fields** - Personalize top text, bottom text, and event day message
- **Full-screen emoji decoration** - Festive emojis fill the display
- **Event day message** - Special text shown when the countdown reaches zero
- **Mashup support** - Fixed bug allows multiple countdowns in a single mashup (as of Dec 1, 2025)

## Settings

### Date
- **Type:** Date picker
- **Description:** Enter the date that you want to countdown to
- **Required:** Yes
- **Default:** 2025-12-25 (Christmas)

### Theme
- **Type:** Dropdown
- **Description:** Which emoji set to display
- **Options:**
  - Christmas 🎄
  - Valentine 💝
  - Easter 🐰
  - Summer ☀️
  - Autumn 🍂
  - Birthday 🎂
  - Sale 🛍️
  - Halloween 🎃
  - New Year 🎉
  - Wedding 💒
  - Baby 👶
  - Travel ✈️
  - Random Mix 🎲
  - St. Patrick's ☘️
  - Kingsday 🇳🇱
  - Formula 1 🏎️
  - Biking 🚴
- **Default:** Christmas

### Top Text
- **Type:** Text input
- **Description:** Shows above the number of days
- **Default:** "IT'S CHRISTMAS IN"

### Bottom Text
- **Type:** Text input
- **Description:** Shows under the number of days
- **Default:** "DAYS!"

### On the Date
- **Type:** Text input
- **Description:** The text that is shown when the countdown date is reached
- **Default:** "HAPPY HOLIDAYS!"

## Technical Details

- **Strategy:** Static
- **Refresh Interval:** 1440 minutes (24 hours)
- **Screen Padding:** No (full bleed design)
- **Dark Mode Support:** No

## How It Works

The plugin calculates the number of days between the current date and your target date. It displays this number prominently with your custom text and decorates the screen with themed emojis. When the countdown reaches zero (on your target date), it displays your custom event message instead.

## Layout Support

This plugin supports all TRMNL layout sizes:
- Full screen
- Half horizontal
- Half vertical
- Quadrant

## Recent Updates

**December 1, 2025** - Fixed bug that prevented having 2 or more countdowns in a mashup. You can now use multiple countdown instances together!
