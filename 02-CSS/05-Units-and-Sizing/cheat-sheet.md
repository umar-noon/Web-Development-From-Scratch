# CSS Module 05 — Units & Sizing Cheat Sheet

## Units

| Unit | Meaning | Example |
|---|---|---|
| `px` | Fixed size | `20px` |
| `%` | Relative to parent | `width: 80%` |
| `em` | Relative to current element font-size | `2em` |
| `rem` | Relative to root font-size | `2rem` |
| `vw` | 1% of viewport width | `50vw` |
| `vh` | 1% of viewport height | `50vh` |
| `vmin` | 1% of smaller viewport dimension | `50vmin` |
| `vmax` | 1% of larger viewport dimension | `50vmax` |

## Functions

```css
min(90%, 1200px)        /* smaller value */
max(1rem, 2vw)          /* larger value */
clamp(2rem, 5vw, 4rem)  /* min, preferred, max */
```

## Quick Rule

* `px` → fixed values
* `%` → parent-based sizing
* `em` → current element
* `rem` → root element
* `vw / vh` → viewport
* `vmin / vmax` → viewport dimensions
* `min()` → limit from above
* `max()` → limit from below
* `clamp()` → fluid + controlled sizing