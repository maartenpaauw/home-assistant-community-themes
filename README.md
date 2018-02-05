# Home Assistant Community Themes
> All community themes in one repository

## Themes

| Theme           | Credits                                                                                                                                                                | Variable            |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- |
| Christmas       | [moose517](https://community.home-assistant.io/u/moose517) posted [Christmas Theme](https://community.home-assistant.io/t/christmas-theme/34036/3)                     | christmas           |
| Dark Cyan       | [broesie](https://community.home-assistant.io/u/broesie) posted [Dark Cyan Theme](https://community.home-assistant.io/t/dark-cyan-theme/28594/3)                       | dark_cyan           |
| Dark Orange     | [Bram_Kragten](https://community.home-assistant.io/u/Bram_Kragten) posted [Orange Theme](https://community.home-assistant.io/t/orange-theme/28601/6)                   | dark_orange         |
| Dark Red        | [broesie](https://community.home-assistant.io/u/broesie) posted [Dark Red Theme](https://community.home-assistant.io/t/dark-red-theme/28592/6)                         | dark_red            |
| Another Dark    | [lambtho](https://community.home-assistant.io/u/lambtho) posted [Another Dark Theme](https://community.home-assistant.io/t/another-dark-theme/28595/10)                | dark                |
| Halloween       | [skalavala](https://community.home-assistant.io/u/skalavala) posted [Halloween Theme](https://community.home-assistant.io/t/halloween-theme/30872/3)                   | halloween           |
| Material Dark   | [matust](https://community.home-assistant.io/u/matust) posted [Material dark theme](https://community.home-assistant.io/t/material-dark-theme/30796/1)                 | material_dark_green |
| Midnight        | [marcelhoffs](https://community.home-assistant.io/u/marcelhoffs) posted [Midnight Theme](https://community.home-assistant.io/t/midnight-theme/28598/8)                 | midnight            |
| Grey Night      | [ksya](https://community.home-assistant.io/u/ksya) posted [Grey Night theme](https://community.home-assistant.io/t/grey-night-theme/30848/7)                           | night               |
| Black and Green | [GreenTurtwig](https://community.home-assistant.io/u/GreenTurtwig) posted [Black and Green Theme](https://community.home-assistant.io/t/black-and-green-theme/28602/2) | teal                |

## Installation

Clone this repository in your existing `themes/` folder.

```bash
cd themes/
git clone https://github.com/maartenpaauw/home-assistant-community-themes.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/maartenpaauw/home-assistant-community-themes.git
```

Add the following code to your `configuration.yaml` file.

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```
