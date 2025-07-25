---
title: SVG Mask
description: A dynamic SVG mask component that reveals content with hover and mouse movement.
---

::ComponentLoader{label="预览" componentName="SvgMaskDemo" type="examples" id="svg-mask"}
::

## 通过 CLI 安装

::InstallationCli{componentId="svg-mask"}
::

## 手动安装

在同一个文件中，复制并粘贴以下代码：

::code-group

:CodeViewerTab{label="SVGMask.vue" language="vue" componentName="SVGMask" type="ui" id="svg-mask"}

```html [mask.svg]
<svg
  width="1298"
  height="1298"
  viewBox="0 0 1298 1298"
  fill="none"
  xmlns="http://www.w3.org/2000/svg"
>
  <circle
    cx="649"
    cy="649"
    r="649"
    fill="black"
  />
</svg>
```

::

## API

| Prop 名称    | 类型     | 默认值 | 描述                                       |
| ------------ | -------- | ------ | ------------------------------------------ |
| `class`      | `string` | `""`   | Additional CSS classes for custom styling. |
| `size`       | `number` | `10`   | Initial size of the mask in pixels.        |
| `revealSize` | `number` | `600`  | Size of the mask during hover in pixels.   |

## 功能特性

- **Hover-Activated Mask**: The SVG mask dynamically enlarges when hovered, revealing the content beneath.
- **Mouse Tracking**: The mask follows the cursor, creating an engaging and interactive effect.
- **Customizable Mask Size**: Adjust the initial size (`size`) and hover size (`revealSize`) for different effects.
- **Slot-Based Content**: Supports named slots for base and reveal content, making it flexible for various use cases.
- **Responsive Background**: Includes hover-based background color transitions for added visual appeal.

## 感谢

- Ported from [Aceternity UI's SVG Mask Effect](https://ui.aceternity.com/components/text-generate-effect).
