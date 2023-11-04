# Ansible Role: Lighthouse
## Description

Deploy [Lighthouse](https://github.com/VKCOM/lighthouse/) lightweight GUI interface for ClickHouse.

## Requirements

- Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)

## Role Variables

All variables which can be overridden are stored in [defaults/main.yml](defaults/main.yml) file as well as in table below.

| Name           | Default Value | Description                                                                                                                                                                                                                                |
| -------------- | ------------- |--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `document_root` | "/var/www" | Root web server direcotry.                                                                                                                                                                                                                 |
| `app_root` | lighthouse | Lighthouse deployment directory.                                                                                                                                                                                                           |
| `lighthouse_vcs` | "https://github.com/VKCOM/lighthouse/" | ALink to lighthouse repository|


