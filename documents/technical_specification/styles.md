# Components Style

<details>
<summary>Table of Contents</summary>

- [Components Style](#components-style)
  - [1. Introduction](#1-introduction)
  - [2. Elements](#2-elements)
    - [2.1. Search Box](#21-search-box)
    - [2.2. Button](#22-button)
      - [2.2.1. Outline Light Primary Contrast](#221-outline-light-primary-contrast)
      - [2.2.2. Filled Light Primary Contrast](#222-filled-light-primary-contrast)
      - [2.2.3. Filled White](#223-filled-white)
      - [2.2.4. Filled Black](#224-filled-black)
      - [2.2.5. Filled Surface](#225-filled-surface)
      - [2.2.6. Tabs Disabled Left](#226-tabs-disabled-left)
      - [2.2.7. Tabs Disabled Right](#227-tabs-disabled-right)
      - [2.2.8. Tabs Enabled Left](#228-tabs-enabled-left)
      - [2.2.9. Tabs Enabled Right](#229-tabs-enabled-right)
    - [2.3. Repeating Groups](#23-repeating-groups)
      - [2.3.1. Transparent (Default)](#231-transparent-default)
    - [2.4. Slider Inputs](#24-slider-inputs)
      - [2.4.1. Range (Default)](#241-range-default)
      - [2.4.2. Properties](#242-properties)
    - [2.5. Text](#25-text)
      - [2.5.1. Body 12](#251-body-12)
      - [2.5.2. Body 14](#252-body-14)
      - [2.5.3. Body 16](#253-body-16)
      - [2.5.4. Bold 16](#254-bold-16)
      - [2.5.5. Card Text 14](#255-card-text-14)
      - [2.5.6. Card Text 16](#256-card-text-16)
      - [2.5.7. Heading 1](#257-heading-1)
      - [2.5.8. Heading 2](#258-heading-2)
      - [2.5.9. Heading 2 Underlined](#259-heading-2-underlined)
      - [2.5.10. Heading 3](#2510-heading-3)
      - [2.5.11. Popup Header 16](#2511-popup-header-16)
      - [2.5.12. Tags](#2512-tags)


</details>

## 1. Introduction

This document defines comprehensively the styles which will be set up in the Bubble app's Styles tab. 

## 2. Elements

### 2.1. Search Box

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="14">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Regular (400)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Text Alignment</td><td>Left</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.2</td></tr>
  <tr><td>Placeholder Color</td><td>#000000 (50% opacity)</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#FFFFFF</td></tr>
  <tr><td>Border Type</td><td>Solid</td></tr>
  <tr><td>Border Width</td><td>1px</td></tr>
  <tr><td>Border Roundness</td><td>12px</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>12px</td></tr>
  <tr><td>Padding Right</td><td>12px</td></tr>

  <tr>
    <td rowspan="1">Conditional Logic</td>
    <td>When This SearchBox isn't valid</td>
    <td>Border color - all borders: Destructive (#B0200C)</td>
  </tr>
</table>

---

### 2.2. Button

#### 2.2.1. Outline Light Primary Contrast

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="15">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Font Color</td><td>#DECE9C</td></tr>
  <tr><td>Text Alignment</td><td>Center</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.4</td></tr>
  <tr><td>Icon Size</td><td>24px</td></tr>
  <tr><td>Icon Color</td><td>#DECE9C</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#FFFFFF</td></tr>
  <tr><td>Border Type</td><td>Dashed</td></tr>
  <tr><td>Border Width</td><td>4px</td></tr>
  <tr><td>Border Roundness</td><td>99px</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Gap</td>
    <td>10px</td>
  </tr>
  <tr><td>Padding Top</td><td>0px</td></tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>20px</td></tr>
  <tr><td>Padding Right</td><td>20px</td></tr>

  <tr>
    <td rowspan="1">Conditional Logic</td>
    <td>When This Button is hovered</td>
    <td>Background Color: Surface (#F1F1F2)</td>
  </tr>
</table>

#### 2.2.2. Filled Light Primary Contrast

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="15">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Text Alignment</td><td>Center</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.4</td></tr>
  <tr><td>Icon Size</td><td>24px</td></tr>
  <tr><td>Icon Color</td><td>#000000</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#DECE9C 75%</td></tr>
  <tr><td>Border Color</td><td>DECE9C 100%</td></tr>
  <tr><td>Border Type</td><td>Dashed</td></tr>
  <tr><td>Border Width</td><td>4px</td></tr>
  <tr><td>Border Roundness</td><td>99px</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Gap</td>
    <td>10px</td>
  </tr>
  <tr><td>Padding Top</td><td>0px</td></tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>20px</td></tr>
  <tr><td>Padding Right</td><td>20px</td></tr>

  <tr>
    <td rowspan="1">Conditional Logic</td>
    <td>When This Button is hovered</td>
    <td>Background Color: Surface (#F1F1F2)</td>
  </tr>
</table>

#### 2.2.3. Filled White

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="20">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Medium (500)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Text Alignment</td><td>Center</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.4</td></tr>
  <tr><td>Icon Size</td><td>16px</td></tr>
  <tr><td>Icon Color</td><td>#000000</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#FFFFFF</td></tr>
  <tr><td>Border Type</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>12px</td></tr>
  <tr><td>Boxshadow Color</td><td>#000000 25%</td></tr>
  <tr><td>Shadow Style</td><td>Outset</td></tr>
  <tr><td>Horizontal Offset</td><td>4px</td></tr>
  <tr><td>Vertical Offset</td><td>4px</td></tr>
  <tr><td>Blur Radius</td><td>4px</td></tr>
  <tr><td>Spread Radius</td><td>0px</td></tr>

  <tr>
    <td rowspan="5">Layout</td>
    <td>Gap</td>
    <td>12px</td>
  </tr>
  <tr><td>Padding Top</td><td>0px</td></tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>12px</td></tr>
  <tr><td>Padding Right</td><td>12px</td></tr>
</table>

#### 2.2.4. Filled Black

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="20">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Medium (500)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Font Color</td><td>#FFFFFF</td></tr>
  <tr><td>Text Alignment</td><td>Center</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.4</td></tr>
  <tr><td>Icon Size</td><td>16px</td></tr>
  <tr><td>Icon Color</td><td>#FFFFFF</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#000000</td></tr>
  <tr><td>Border Type</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>12px</td></tr>
  <tr><td>Boxshadow Color</td><td>#000000 25%</td></tr>
  <tr><td>Shadow Style</td><td>Outset</td></tr>
  <tr><td>Horizontal Offset</td><td>4px</td></tr>
  <tr><td>Vertical Offset</td><td>4px</td></tr>
  <tr><td>Blur Radius</td><td>4px</td></tr>
  <tr><td>Spread Radius</td><td>0px</td></tr>

  <tr>
    <td rowspan="5">Layout</td>
    <td>Gap</td>
    <td>12px</td>
  </tr>
  <tr><td>Padding Top</td><td>0px</td></tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>12px</td></tr>
  <tr><td>Padding Right</td><td>12px</td></tr>
</table>

#### 2.2.5. Filled Surface

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="20">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Bold (700)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Text Alignment</td><td>Center</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.4</td></tr>
  <tr><td>Icon Size</td><td>16px</td></tr>
  <tr><td>Icon Color</td><td>#000000</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#F1F1F2</td></tr>
  <tr><td>Border Type</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>12px</td></tr>
  <tr><td>Boxshadow Color</td><td>#000000 25%</td></tr>
  <tr><td>Shadow Style</td><td>Outset</td></tr>
  <tr><td>Horizontal Offset</td><td>4px</td></tr>
  <tr><td>Vertical Offset</td><td>4px</td></tr>
  <tr><td>Blur Radius</td><td>4px</td></tr>
  <tr><td>Spread Radius</td><td>0px</td></tr>

  <tr>
    <td rowspan="5">Layout</td>
    <td>Gap</td>
    <td>12px</td>
  </tr>
  <tr><td>Padding Top</td><td>0px</td></tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>12px</td></tr>
  <tr><td>Padding Right</td><td>12px</td></tr>
</table>

#### 2.2.6. Tabs Disabled Left

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="29">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>20px</td></tr>
  <tr><td>Font Color</td><td>#000000 80%</td></tr>
  <tr><td>Text Alignment</td><td>Center</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.4</td></tr>
  <tr><td>Icon Size</td><td>20px</td></tr>
  <tr><td>Icon Color</td><td>#000000 80%</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#DECE9C 60%</td></tr>
  <tr><td>Define Each Border Independently</td><td>yes</td></tr>
  <tr><td>Border Type - Top</td><td>None</td></tr>
  <tr><td>Border Type - Left</td><td>None</td></tr>
  <tr><td>Border Type - Right</td><td>None</td></tr>
  <tr><td>Border Type - Bottom</td><td>Solid</td></tr>
  <tr><td>Border Type - Bottom - Width</td><td>4px</td></tr>
  <tr><td>Border Type - Bottom - Color</td><td>#E00E1F</td></tr>
  <tr><td>Border Roundness - Top-Left</td><td>12px</td></tr>
  <tr><td>Border Roundness - Top-Right</td><td>0px</td></tr>
  <tr><td>Border Roundness - Bottom-Left</td><td>0px</td></tr>
  <tr><td>Border Roundness - Bottom-Right</td><td>0px</td></tr>
  <tr><td>Boxshadow Color</td><td>#000000 25%</td></tr>
  <tr><td>Shadow Style</td><td>Outset</td></tr>
  <tr><td>Horizontal Offset</td><td>4px</td></tr>
  <tr><td>Vertical Offset</td><td>4px</td></tr>
  <tr><td>Blur Radius</td><td>4px</td></tr>
  <tr><td>Spread Radius</td><td>0px</td></tr>

  <tr>
    <td rowspan="5">Layout</td>
    <td>Gap</td>
    <td>12px</td>
  </tr>
  <tr><td>Padding Top</td><td>0px</td></tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>12px</td></tr>
  <tr><td>Padding Right</td><td>12px</td></tr>
</table>

#### 2.2.7. Tabs Disabled Right

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="29">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>20px</td></tr>
  <tr><td>Font Color</td><td>#000000 80%</td></tr>
  <tr><td>Text Alignment</td><td>Center</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.4</td></tr>
  <tr><td>Icon Size</td><td>20px</td></tr>
  <tr><td>Icon Color</td><td>#000000 80%</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#DECE9C 60%</td></tr>
  <tr><td>Define Each Border Independently</td><td>yes</td></tr>
  <tr><td>Border Type - Top</td><td>None</td></tr>
  <tr><td>Border Type - Left</td><td>None</td></tr>
  <tr><td>Border Type - Right</td><td>None</td></tr>
  <tr><td>Border Type - Bottom</td><td>Solid</td></tr>
  <tr><td>Border Type - Bottom - Width</td><td>4px</td></tr>
  <tr><td>Border Type - Bottom - Color</td><td>#E00E1F</td></tr>
  <tr><td>Border Roundness - Top-Left</td><td>0px</td></tr>
  <tr><td>Border Roundness - Top-Right</td><td>12px</td></tr>
  <tr><td>Border Roundness - Bottom-Left</td><td>0px</td></tr>
  <tr><td>Border Roundness - Bottom-Right</td><td>0px</td></tr>
  <tr><td>Boxshadow Color</td><td>#000000 25%</td></tr>
  <tr><td>Shadow Style</td><td>Outset</td></tr>
  <tr><td>Horizontal Offset</td><td>4px</td></tr>
  <tr><td>Vertical Offset</td><td>4px</td></tr>
  <tr><td>Blur Radius</td><td>4px</td></tr>
  <tr><td>Spread Radius</td><td>0px</td></tr>

  <tr>
    <td rowspan="5">Layout</td>
    <td>Gap</td>
    <td>12px</td>
  </tr>
  <tr><td>Padding Top</td><td>0px</td></tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>12px</td></tr>
  <tr><td>Padding Right</td><td>12px</td></tr>
</table>

#### 2.2.8. Tabs Enabled Left

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="29">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Bold (700)</td></tr>
  <tr><td>Font Size</td><td>20px</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Text Alignment</td><td>Center</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.4</td></tr>
  <tr><td>Icon Size</td><td>20px</td></tr>
  <tr><td>Icon Color</td><td>#000000</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#DECE9C</td></tr>
  <tr><td>Define Each Border Independently</td><td>yes</td></tr>
  <tr><td>Border Type - Top</td><td>None</td></tr>
  <tr><td>Border Type - Left</td><td>None</td></tr>
  <tr><td>Border Type - Right</td><td>None</td></tr>
  <tr><td>Border Type - Bottom</td><td>Solid</td></tr>
  <tr><td>Border Type - Bottom - Width</td><td>4px</td></tr>
  <tr><td>Border Type - Bottom - Color</td><td>#E00E1F</td></tr>
  <tr><td>Border Roundness - Top-Left</td><td>12px</td></tr>
  <tr><td>Border Roundness - Top-Right</td><td>0px</td></tr>
  <tr><td>Border Roundness - Bottom-Left</td><td>0px</td></tr>
  <tr><td>Border Roundness - Bottom-Right</td><td>0px</td></tr>
  <tr><td>Boxshadow Color</td><td>#000000 25%</td></tr>
  <tr><td>Shadow Style</td><td>Outset</td></tr>
  <tr><td>Horizontal Offset</td><td>4px</td></tr>
  <tr><td>Vertical Offset</td><td>4px</td></tr>
  <tr><td>Blur Radius</td><td>4px</td></tr>
  <tr><td>Spread Radius</td><td>0px</td></tr>

  <tr>
    <td rowspan="5">Layout</td>
    <td>Gap</td>
    <td>12px</td>
  </tr>
  <tr><td>Padding Top</td><td>0px</td></tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>12px</td></tr>
  <tr><td>Padding Right</td><td>12px</td></tr>
</table>

#### 2.2.9. Tabs Enabled Right

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="29">Appearance</td>
    <td>Font</td>
    <td>Inter</td>
  </tr>
  <tr><td>Font Weight</td><td>Bold (700)</td></tr>
  <tr><td>Font Size</td><td>20px</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Text Alignment</td><td>Center</td></tr>
  <tr><td>Word Spacing</td><td>0</td></tr>
  <tr><td>Letter Spacing</td><td>0</td></tr>
  <tr><td>Line Spacing</td><td>1.4</td></tr>
  <tr><td>Icon Size</td><td>20px</td></tr>
  <tr><td>Icon Color</td><td>#000000</td></tr>
  <tr><td>Background Style</td><td>Flat Color</td></tr>
  <tr><td>Background Color</td><td>#DECE9C</td></tr>
  <tr><td>Define Each Border Independently</td><td>yes</td></tr>
  <tr><td>Border Type - Top</td><td>None</td></tr>
  <tr><td>Border Type - Left</td><td>None</td></tr>
  <tr><td>Border Type - Right</td><td>None</td></tr>
  <tr><td>Border Type - Bottom</td><td>Solid</td></tr>
  <tr><td>Border Type - Bottom - Width</td><td>4px</td></tr>
  <tr><td>Border Type - Bottom - Color</td><td>#E00E1F</td></tr>
  <tr><td>Border Roundness - Top-Left</td><td>0px</td></tr>
  <tr><td>Border Roundness - Top-Right</td><td>12px</td></tr>
  <tr><td>Border Roundness - Bottom-Left</td><td>0px</td></tr>
  <tr><td>Border Roundness - Bottom-Right</td><td>0px</td></tr>
  <tr><td>Boxshadow Color</td><td>#000000 25%</td></tr>
  <tr><td>Shadow Style</td><td>Outset</td></tr>
  <tr><td>Horizontal Offset</td><td>4px</td></tr>
  <tr><td>Vertical Offset</td><td>4px</td></tr>
  <tr><td>Blur Radius</td><td>4px</td></tr>
  <tr><td>Spread Radius</td><td>0px</td></tr>

  <tr>
    <td rowspan="5">Layout</td>
    <td>Gap</td>
    <td>12px</td>
  </tr>
  <tr><td>Padding Top</td><td>0px</td></tr>
  <tr><td>Padding Bottom</td><td>0px</td></tr>
  <tr><td>Padding Left</td><td>12px</td></tr>
  <tr><td>Padding Right</td><td>12px</td></tr>
</table>

---

### 2.3. Repeating Groups

#### 2.3.1. Transparent (Default)

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="8">Appearance</td>
    <td>Style</td>
    <td>None</td>
  </tr>
  <tr><td>Font Weight</td><td>Bold (700)</td></tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>no</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Roundness</td><td>0px</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>
</table>

---

### 2.4. Slider Inputs

#### 2.4.1. Range (Default)

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="5">Appearance</td>
    <td>Slider Style</td>
    <td>Range</td>
  </tr>
  <tr><td>Border Color</td><td>#000000</td></tr>
  <tr><td>Background Color</td><td>#000000</td></tr>
  <tr><td>Handle Color</td><td>#000000</td></tr>
  <tr><td>Range Area Color</td><td>#000000</td></tr>

  <tr>
    <td rowspan="1">Conditional Logic</td>
    <td>This SliderInput is hovered</td>
    <td>Handle Color: Text (#000000)</td>
  </tr>
</table>

#### 2.4.2. Properties

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="4">Appearance</td>
    <td>Slider Style</td>
    <td>Simple</td>
  </tr>
  <tr><td>Border Color</td><td>#000000</td></tr>
  <tr><td>Background Color</td><td>#000000</td></tr>
  <tr><td>Handle Color</td><td>#E00E1F</td></tr>

  <tr>
    <td rowspan="1">Conditional Logic</td>
    <td>This SliderInput is hovered</td>
    <td>Handle Color: Text (#E00E1F)</td>
  </tr>
</table>

---

### 2.5. Text

#### 2.5.1. Body 12

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>Normal</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Regular (400)</td></tr>
  <tr><td>Font Size</td><td>12px</td></tr>
  <tr><td>Alignment</td><td>Right</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>
<table>

#### 2.5.2. Body 14

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>Normal</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Medium (500)</td></tr>
  <tr><td>Font Size</td><td>14px</td></tr>
  <tr><td>Alignment</td><td>Right</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>

  <tr>
    <td rowspan="1">Conditional Logic</td>
    <td>Current page width < Mobile (320px)</td>
    <td>Font Size: 12px</td>
  </tr>
</table>

#### 2.5.3. Body 16

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>Normal</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Medium (500)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Alignment</td><td>Right</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>

  <tr>
    <td rowspan="1">Conditional Logic</td>
    <td>Current page width < Mobile (320px)</td>
    <td>Font Size: 14px</td>
  </tr>
</table>

#### 2.5.4. Bold 16

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>Normal</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Bold (700)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Alignment</td><td>Right</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>

  <tr>
    <td rowspan="1">Conditional Logic</td>
    <td>Current page width < Mobile (320px)</td>
    <td>Font Size: 14px</td>
  </tr>
</table>

#### 2.5.5. Card Text 14

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>Normal</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>14px</td></tr>
  <tr><td>Alignment</td><td>Right</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>
</table>

#### 2.5.6. Card Text 16

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>Normal</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Alignment</td><td>Right</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>
</table>

#### 2.5.7. Heading 1

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>h1</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>32px</td></tr>
  <tr><td>Alignment</td><td>Center</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>
</table>

#### 2.5.8. Heading 2

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>h2</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>24px</td></tr>
  <tr><td>Alignment</td><td>Center</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>
</table>

#### 2.5.9. Heading 2 Underlined

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="22">Appearance</td>
    <td>HTML Tag</td>
    <td>h2</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>24px</td></tr>
  <tr><td>Alignment</td><td>Right</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>Yes</td></tr>
  <tr><td>Border Style - Top</td><td>None</td></tr>
  <tr><td>Border Style - Right</td><td>None</td></tr>
  <tr><td>Border Style - Bottom</td><td>Solid</td></tr>
  <tr><td>Border Style - Bottom - Width</td><td>1px</td></tr>
  <tr><td>Border Style - Bottom - Color</td><td>#E00E1F</td></tr>
  <tr><td>Border Style - Left</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>32px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>
</table>

#### 2.5.10. Heading 3

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>h3</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>20px</td></tr>
  <tr><td>Alignment</td><td>Right</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>
</table>

#### 2.5.11. Popup Header 16

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="17">Appearance</td>
    <td>HTML Tag</td>
    <td>Normal</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Semi-Bold (600)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Alignment</td><td>Right</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>None</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>None</td></tr>
  <tr><td>Border Roundness</td><td>0px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>0px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>0px</td></tr>
  <tr><td>Padding - Left</td><td>0px</td></tr>
  <tr><td>Padding - Right</td><td>0px</td></tr>
</table>

#### 2.5.12. Tags

<table>
  <tr>
    <th>Tab</th>
    <th>Property</th>
    <th>Value</th>
  </tr>
  <tr>
    <td rowspan="20">Appearance</td>
    <td>HTML Tag</td>
    <td>Normal</td>
  </tr>
  <tr><td>Opacity</td><td>100%</td></tr>
  <tr><td>Font Style</td><td>Inter</td></tr>
  <tr><td>Font Weight</td><td>Medium (500)</td></tr>
  <tr><td>Font Size</td><td>16px</td></tr>
  <tr><td>Alignment</td><td>Center</td></tr>
  <tr><td>Font Color</td><td>#000000</td></tr>
  <tr><td>Word Spacing</td><td>0px</td></tr>
  <tr><td>Line Spacing</td><td>1.4px</td></tr>
  <tr><td>Letter Spacing</td><td>0px</td></tr>
  <tr><td>Center Text Vertically</td><td>yes</td></tr>
  <tr><td>Background Style</td><td>Solid</td></tr>
  <tr><td>Background Color</td><td>#DECE9C 75%</td></tr>
  <tr><td>Define Each Border Independently</td><td>No</td></tr>
  <tr><td>Border Style</td><td>Solid</td></tr>
  <tr><td>Border Width</td><td>4px</td></tr>
  <tr><td>Border Color</td><td>#DECE9C</td></tr>
  <tr><td>Border Roundness</td><td>30px</td></tr>
  <tr><td>Show Text Shadow</td><td>No</td></tr>
  <tr><td>Shadow Style</td><td>None</td></tr>

  <tr>
    <td rowspan="4">Layout</td>
    <td>Padding - Top</td>
    <td>12px</td>
  </tr>
  <tr><td>Padding - Bottom</td><td>12px</td></tr>
  <tr><td>Padding - Left</td><td>8px</td></tr>
  <tr><td>Padding - Right</td><td>8px</td></tr>
</table>
