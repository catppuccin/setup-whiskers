<h3 align="center">
 <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
 <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
 Catppuccin GitHub Action for <a href="https://github.com/catppuccin/whiskers">Whiskers</a>
 <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
 <a href="https://github.com/catppuccin/setup-whiskers/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/setup-whiskers?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
 <a href="https://github.com/catppuccin/setup-whiskers/issues"><img src="https://img.shields.io/github/issues/catppuccin/setup-whiskers?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
 <a href="https://github.com/catppuccin/setup-whiskers/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/setup-whiskers?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

## Usage

<!-- x-release-please-version -->

```yaml
- uses: catppuccin/setup-whiskers@v1.0.0
  with:
    # Semver compatible version of catppuccin/whiskers to install.
    # E.g. "2.5", "2.x"
    #
    # Defaults to the latest version.
    whiskers-version: ""

    # GitHub token to authenticate with when installing catppuccin/whiskers.
    #
    # Defaults to ${{ github.token }}.
    github-token: ""
```

## Examples

### Install the latest version

```yaml
- uses: catppuccin/setup-whiskers@v1.0.0
```

### Install v2.5.0

Equivalent to `=2.5.0`

```yaml
- uses: catppuccin/setup-whiskers@v1.0.0
  with:
    whiskers-version: "2.5.0"
```

### Install 2.x

Equivalent to `>=0.2.0 <0.3.0`

```yaml
- uses: catppuccin/setup-whiskers@v1.0.0
  with:
    whiskers-version: "2.x" # or just "2"
```

<!-- x-release-please-end -->

## 💝 Thanks to

- [Hammy](https://github.com/sgoudham)

&nbsp;

<p align="center">
 <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
 Copyright &copy; 2024-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
 <a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>

