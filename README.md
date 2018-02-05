# Home Assistant Community Themes
> All community themes in one repository

## Themes

| Theme               | Credits                                                                                                                                        | Variable            |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- |
| Christmas           | [moose517](https://community.home-assistant.io/u/moose517) posted at https://community.home-assistant.io/t/christmas-theme/34036               | christmas           |
| Dark Cyan           | [broesie](https://community.home-assistant.io/u/broesie) posted at https://community.home-assistant.io/t/dark-cyan-theme/28594                 | dark_cyan           |
| Dark orange         | [Bram_Kragten](https://community.home-assistant.io/u/Bram_Kragten) posted at https://community.home-assistant.io/t/orange-theme/28601          | dark_orange         |
| Dark red            | [broesie](https://community.home-assistant.io/u/broesie) posted at https://community.home-assistant.io/t/dark-red-theme/28592                  | dark_red            |
| Dark                | [lambtho](https://community.home-assistant.io/u/lambtho) posted at https://community.home-assistant.io/t/another-dark-theme/28595              | dark                |
| Halloween           | [skalavala](https://community.home-assistant.io/u/skalavala) posted at https://community.home-assistant.io/t/halloween-theme/30872             | halloween           |
| Material Dark Green | [matust](https://community.home-assistant.io/u/matust) posted at https://community.home-assistant.io/t/material-dark-theme/30796               | material_dark_green |
| Midnight            | [marcelhoffs](https://community.home-assistant.io/u/marcelhoffs) posted at https://community.home-assistant.io/t/midnight-theme/28598          | midnight            |
| Night               | [ksya](https://community.home-assistant.io/u/ksya) posted at https://community.home-assistant.io/t/grey-night-theme/30848                      | night               |
| Teal                | [GreenTurtwig](https://community.home-assistant.io/u/GreenTurtwig) posted at https://community.home-assistant.io/t/black-and-green-theme/28602 | teal                |

## Installation

Clone this repository in your existing `themes/` folder.

```bash
cd themes/
git clone git@github.com:maartenpaauw/home-assistant-community-themes.git
```

Add the following code to your `configuration.yaml` file.

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```
