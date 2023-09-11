---
sidebar_position: 2
---

# Theme Content

This is a basic object representation of the theme content property. It consists of the following:

```ts title="Theme Content Object" showLineNumbers
interface ThemeJSONSchema {
  sidebarBG?: string;
  primaryBG?: string;
  primaryTextColor?: string;
  iconColor?: string;
  lightTextOpacity?: number;
  sidebarInsetBg?: string;
  sidebarInsetTextColor?: string;
  iconLightOpacity?: number;
  sidebarBorderColor?: string;
  primaryBorderColor?: string;
  scrollbarThumbColor?: string;
  scrollbarThumbHoverColor?: string;
  scrollbarThumbActiveColor?: string;
  scrollbarTrackColor?: string;
}
```

## Example

Below is the default theme configurations as an example for creating your own theme.

```json title="Bytes Browser Dark" showLineNumbers
{
  "sidebarBG": "#1C1B20",
  "primaryBG": "#27272D",
  "primaryTextColor": "white",
  "iconColor": "#B0B0B0",
  "iconLightOpacity": 0.7,
  "lightTextOpacity": 0.7,
  "sidebarInsetBg": "#1C1B20",
  "sidebarBorderColor": "#E2E5E8",
  "sidebarInsetTextColor": "white",
  "primaryBorderColor": "#555555",
  "scrollbarThumbColor": "#E0E0E0",
  "scrollbarThumbHoverColor": "#B0B0B0",
  "scrollbarThumbActiveColor": "#888888",
  "scrollbarTrackColor": "#1C1B20"
}
```

```json title="Bytes Browser Light" showLineNumbers
{
  "sidebarBG": "#E2E5E8",
  "primaryBG": "#F2F3F5",
  "primaryTextColor": "black",
  "iconColor": "gray",
  "iconLightOpacity": 1,
  "lightTextOpacity": 1,
  "sidebarInsetBg": "#1C1B20",
  "sidebarBorderColor": "#1C1B20",
  "sidebarInsetTextColor": "white",
  "primaryBorderColor": "lightgray",
  "scrollbarThumbColor": "#1C1B20",
  "scrollbarThumbHoverColor": "#333333",
  "scrollbarThumbActiveColor": "#555555",
  "scrollbarTrackColor": "#E0E0E0"
}
```
