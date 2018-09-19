# iview-theme

Theme generator cli tool for iview

## Installation

```
npm i iview-theme -g
```

## Usage

Initialize a theme project
"xxx" means iview tags or releases number, example: v2.14.3.
If you havn't defined the version number, it will use the latest version.

```
iview-theme init my-theme

or

iview-theme init my-theme xxx
```

2. Edit `my-theme/custom.less` and build your theme project

```
cd my-theme
iview-theme build -o dist/
```
