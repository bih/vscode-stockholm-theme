<div align="center">
  <img width="1200" src="https://raw.githubusercontent.com/bih/vscode-stockholm-theme/main/masthead.png" alt="Screenshots of the Stockholm visual studio code theme" />
  
  <p>A beautiful theme for VS Code.</p>

  <p>
    <a href="https://marketplace.visualstudio.com/items?itemName=bilawal-hameed.vscode-stockholm-theme">
      <img src="https://vsmarketplacebadge.apphb.com/version-short/bilawal-hameed.vscode-stockholm-theme.svg?style=flat-square" alt="Version">
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=bilawal-hameed.vscode-stockholm-theme">
      <img src="https://vsmarketplacebadge.apphb.com/installs/bilawal-hameed.vscode-stockholm-theme.svg?style=flat-square" alt="Installs">
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=bilawal-hameed.vscode-stockholm-theme">
      <img src="https://vsmarketplacebadge.apphb.com/rating/bilawal-hameed.vscode-stockholm-theme.svg?style=flat-square" alt="Ratings">
    </a>
  </p>
</div>

## Install

```yarn
ext install vscode-stockholm-theme
```

Or go in the marketplace and search for `Stockholm`. Note there are two VSCode themes called "Stockholm", be sure you're installing the right one :)

## Colors

The color scheme passes both WCAG AA and WCAG AAA checks. It was checked using [WebAIM](https://webaim.org/resources/contrastchecker/).

## Contributing

```sh
git clone git@github.com:bih/vscode-stockholm-theme.git
code ./vscode-stockholm-theme
```

Then press <kbd>F5</kbd> to open up a new VSCode with the theme. You can then make changes and see it live update instantly.

## Publishing New Release

1. Commit using [Conventional Commits](https://www.conventionalcommits.org) (i.e. `fix: [describe fix]`, `docs: [describe docs change]`, etc)
2. Update the `version` in package.json. As VSCode themes technically never break, a minor change should be sufficient.
3. Once published, create a new GitHub release with the same version set in Step 2.
4. Success! GitHub Actions will automatically trigger and publish to NPM (as `vscode-stockholm-theme`). No action is required from your end.

## License

[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)
