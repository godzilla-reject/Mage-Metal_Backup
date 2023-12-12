```css
/*
author: FireIsGood
source: https://discord.com/channels/686053708261228577/702656734631821413/1103116637529456720
*/

[data-callout="scroller"] {
  --callout-color: 255, 0, 0; /* Replace this with rgb values */
  --shown-line-count: 8; /* Replace this with the number of text lines to show */
}
[data-callout="scroller"] .callout-title {
  display: none;
}
[data-callout="scroller"] .callout-content {
  max-height: calc(var(--line-height-normal) * 1rem * var(--shown-line-count));
}
```