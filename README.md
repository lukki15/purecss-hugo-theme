# purecss Hugo theme

Hugo theme based on [purecss](https://purecss.io/).
The theme is based on the [purecss landing page example](https://purecss.io/layouts/marketing/).

[Live Demo](/#)

## Preview

![screenshot preview](./assets/img/screenshot_preview.png)

## Features

- Responsive
- Mobile first
- Multi-column layout
- Css only
- Make use of modern image formats: webp
- Optimized for speed and performance
- Built-in 404 page
- Automatically sitemap.xml generation
- Well formatted code.

## Get the theme

Minimum Hugo Version: 0.83

1. Add the repository into your Hugo Project repository as a submodule,  
`
git submodule add https://github.com/lukki15/purecss-hugo-theme.git themes/purecss
`
1. Copy the `assets`, `content`, `static` folders and the `config.toml` files form the `exampleSite` directory and paste it on you Hugo Project repository/directory. From the site home directory:  
`cp -a themes/purecss/exampleSite/* .`
1. Build your site with `hugo serve` and see the result at `http://localhost:1313/`
1. For production build with `hugo -D --minify`, and see the result in the `public` folder

## Issues

If you have a question, please [open an issue](https://github.com/lukki15/purecss-hugo-theme/issues) for help and to help those who come after you. The more information you can provide, the better!

## Contributing

Contributions, issues, and feature requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

The code is licensed under [MIT](https://github.com/lukki15/purecss-hugo-theme/blob/main/LICENSE)

The LK logo image is copyrighted and used by permission for this project only.  
All other images are licensed under public domain, more information [here](./exampleSite/content/images.md)