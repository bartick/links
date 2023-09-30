# 🚀 Quick start

1. **Customize your general settings**

   Open `src/config.ts` and edit the `SUBTITLE`, `TITLE`, `TAGLINE`, `contact`, `phone` and `email` variables.

2. **Customize your links**

    Create a new file in `src/pages/links/` for each link you want to add.
    The file name will be not used, but it is recommended to use a descriptive name.
    The file should contain a frontmatter section with the following variables:
    
    * `title`: The title of the link
    
    * `icon`: The icon to use for the link (See `src/components/Icon.astro` for a list of available icons)
    
    * `href`: The URL of the link

    Example:
    
    ```md
    ---

    title: Link 1
    icon: www
    href: https://lorem.com

    ---
    ```

3. **Customize your avatar**

    Replace the file `public/avatar.jpg` with your own avatar.

4. **Customize your social media links**

    Create a new file in `src/pages/social/` for each social media link you want to add.
    The file name will be not used, but it is recommended to use a descriptive name.
    The file should contain a frontmatter section with the following variables:

    * `icon`: The icon to use for the link
    
    * `url`: The URL of the link

    Example:

    ```md
    ---
    icon: linkedin
    url: https://linkedin.com/in/yoan-bernabeu

    ---
    ```

All commands are run from the root of the project, from a terminal:

| Command                | Action                                             |
| :--------------------- | :------------------------------------------------- |
| `npm install`          | Installs dependencies                              |
| `npm run dev`          | Starts local dev server at `localhost:4321`        |
| `npm run build`        | Build your production site to `./dist/`            |
| `npm run preview`      | Preview your build locally, before deploying       |

## 📝 License

Licensed under the [MIT License](./LICENSE).
