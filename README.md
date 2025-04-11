# Obsidian - Better Callouts
## Giving you the tools you need to make simple, efficient and aesthetic Obsidian Callouts.
Better Callouts is a package of CSS Snippets for Obsidian that enhances your note-taking experience.

If you are a dedicated user of Obsidian Callout, you may have noticed that native callouts provided by Obsidian can be quite restrictive in terms of customization.

Better Callouts solves this issue by offering you new pre-built callouts and innovative ways to personalize them, allowing you to structure your notes more effectively.
## How to install & use Better Callouts ?
To successfully install and use Better Callouts, please follow these steps.
- Download the latest `.zip` release of the project.
- Unpack the `.zip` and place the `.css` files in your `snippets` folder, located in the `.obsidian` folder of your vault.

> [!NOTE]
> If the `snippets` folder doesn't exist in your vault's `.obsidian` folder, just create it. :>

- Open Obsidian and go to `Options > Appearance`.
- Scroll down this "Appearance" settings page until you see a section called "CSS Snippets".
- Activate all the files you downloaded.

> [!TIP]
> If you already have disabled CSS Snippets, and are unsure which ones you've just installed, enable files with a name starting by "Custom Callout".
## How does it work ?
This package includes various CSS snippets that consist of pre-built callouts declaration and callouts metadata.
Callout metadata are used to apply CSS styles to the callout they are applied on. Better Callouts leverages callout metadata to allow you to add or remove elements from a callout.

> [!TIP]
> To use callout metadata, simply add `|myMetadata1 myMetadata2` after the callout declaration.
> *For example :*
> ```md
> > [!CALLOUT|myMetadata1 myMetadata2]
> ```
> Keep in mind that in this example `myMetadata1` and `myMetadata2` are placeholder used to illustrate how callout metadata work, they do not represent actual metadata in Better Callouts.
___
## Contributions
- If you encounter a bug, you are welcome to fork this project, correct the code accordingly, and make a pull request to merge your patched version with the official repository.
    - If you do so (or if you just find a bug), please open an issue on the repository and tag it with the "bug" tag so we can document it.
- If you use the project and think that something should be added in order to better fit your needs, feel free to open an issue on the repository and tag it with the "enhancement" tag.
___
## License
This project is licensed under the Rift Open Source Software License v3.0, which allows for free use, modification, and distribution of the code.
You may use this project in a commercial context, but you can't sell it as a standalone product.