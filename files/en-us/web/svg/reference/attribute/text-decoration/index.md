---
title: text-decoration
slug: Web/SVG/Reference/Attribute/text-decoration
page-type: svg-attribute
browser-compat: svg.global_attributes.text-decoration
sidebar: svgref
---

The **`text-decoration`** attribute defines whether text is decorated with an underline, overline and/or strike-through. It is a shorthand for the {{cssxref("text-decoration-line")}} and {{cssxref("text-decoration-style")}} properties.

The fill and stroke of the text decoration are given by the fill and stroke of the text at the point where the text decoration is declared.

The paint order of the text decoration, i.e., the fill and stroke, is determined by the value of the {{SVGAttr("paint-order")}} attribute at the point where the text decoration is declared.

> [!NOTE]
> As a presentation attribute, `text-decoration` also has a CSS property counterpart: {{cssxref("text-decoration")}}. When both are specified, the CSS property takes priority.

You can use this attribute with the following SVG elements:

- {{SVGElement("text")}}
- {{SVGElement("textPath")}}
- {{SVGElement("tspan")}}

## Example

```css hidden
html,
body,
svg {
  height: 100%;
}
```

```html
<svg viewBox="0 0 250 50" xmlns="http://www.w3.org/2000/svg">
  <text y="20" text-decoration="underline">Underlined text</text>
  <text x="0" y="40" text-decoration="line-through">Struck-through text</text>
</svg>
```

{{EmbedLiveSample("Example", "250", "100")}}

## Usage notes

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">Value</th>
      <td>
        <code
          ><a href="/en-US/docs/Web/CSS/text-decoration-line"
            >&#x3C;'text-decoration-line'></a
          ></code
        >
        ||
        <code
          ><a href="/en-US/docs/Web/CSS/text-decoration-style"
            >&#x3C;'text-decoration-style'></a
          ></code
        >
        ||
        <code
          ><a href="/en-US/docs/Web/CSS/text-decoration-color"
            >&#x3C;'text-decoration-color'></a
          ></code
        >
      </td>
    </tr>
    <tr>
      <th scope="row">Default value</th>
      <td>See individual properties</td>
    </tr>
    <tr>
      <th scope="row">Animatable</th>
      <td>Yes</td>
    </tr>
  </tbody>
</table>

For a description of the values, please refer to the [CSS `text-decoration`](/en-US/docs/Web/CSS/text-decoration#values) property.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- CSS {{cssxref("text-decoration")}} property
