<p align="center">
    <img src="https://raw.githubusercontent.com/nander1117/Dioxus-RSX/refs/heads/main/assets/images/icon.jpg" width="80" />
    <h2 align="center" style="letter-spacing:2px;font-weight:700">Dioxus-RSX (Rust-HTML)</h2>
</p>

<p align="center">Highlight Dioxus RSX(HTML) files in VS Code</p>

> This is with much love for the Dioxus community.


## This example is not a Theme, it is only a highlight of syntax.
The used theme is [Monokai Vibrant Rust](https://marketplace.visualstudio.com/items?itemName=DioxusLabs.monokai-vibrant-rust)

![Dioxus-RSX Example](/assets/images/example.png)


## Change Colors

If you want to change the colors, you can do so by adding the following to your `settings.json` file:
> replace `#customColor` with the color you want to use, for example `#ff0000` for red.

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
        "name": "tags html",
        "scope": "entity.name.tag.rsx",
        "settings": {
            "foreground": "#customColor"

        }
    },
    {
        "name": "attributes html",
        "scope": "entity.other.attribute-name.rsx",
        "settings": {
        "foreground": "#customColor"
        }
    }
  ]
}
```

## Extras

if you want to collaborate or you find a bug, don't hesitate to let me know [Contact Me/Jhon AF](https://github.com/nander1117/Dioxus-RSX)

---

Don't forget to leave a review on the marketplace! **Enjoy!**