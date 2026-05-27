<div align="center">
  <h1>Magzine Theme</h1>
</div>

![Preview](https://github.com/user-attachments/assets/7bf5964e-9dfe-41f6-a281-3568bd5807ef)

<div align="center">
  <p>
    A modern magazine-style Hugo theme with fullscreen hero and dynamic layouts. Concise, elegant, and fast.
  </p>
</div>

## Preview
👉 My [Blog](https://2am.top)

## Documentation
👉 [Guide (Chinese)](https://2am.top/2026/01/28/magzine%E4%B8%BB%E9%A2%98%E6%8C%87%E5%8C%97/)

## Features

-   **Modern Design**: Minimalist aesthetics with smooth interaction.
-   **Magazine Layout**: Dynamic article cards with various sizes and positions.
-   **Responsive**: Adaptive for all devices, including ultra-wide screens.
-   **Highly Customizable**: Extensive configuration for colors, fonts, and layouts.
-   **Performance**: Smooth scrolling, optimized animations, and built-in search indexing.
-   **AI Summary**: DeepSeek AI summary integration.
-   **Shortcodes**: Ported tag plugins including notes, timelines, hidden content, labels, buttons, etc.

## Installation

1.  Add the theme as a submodule to your Hugo project:

``` bash
git submodule add https://github.com/forever218/hugo-theme-magzine.git themes/magzine
```

2.  Set the theme in your `hugo.yaml` (or `hugo.toml`) file:

``` yaml
theme: magzine
```

3.  Copy the example `hugo.yaml` from the theme to your site's root directory for customization.

## Configuration Example (hugo.yaml)

``` yaml
params:
  colors:
    accent: '#ff6b6b' # Theme color
  hero:
    enable: true
    typing_text: "Sky connects cloud waves, stars turn sails dance"
  author_card:
    enable: true
    name: "Author Name"
    bio: "Short bio"
  ai_summary:
    enable: true
    api_key: "your-api-key"
```

## Contributing

1.  Fork the repository
2.  Create a feature branch
3.  Commit your changes
4.  Submit a Pull Request

## License
Licensed under the **MIT** license.

## Credits

-   [Hugo](https://gohugo.io/)
-   [Font Awesome](https://fontawesome.com/)
