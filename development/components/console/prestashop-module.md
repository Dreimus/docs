---
title: prestashop:module
---

# `prestashop:module`

## Informations

* Path: `src/PrestaShopBundle/Command/ModuleCommand.php`
* Arguments:
  * `action`: Action to execute, must be one of: install, uninstall, enable, disable, enable_mobile, disable_mobile, reset, upgrade, configure, registerHook, unregisterHook
  * `module name`: Module on which the action will be executed
  * `file path`: YML file path for configuration __(optional)__
* Options:
  * `hook`: Hook name to use with the registerHook|unregisterHook action __(array|optional)__

## Description

This command aims to manage your modules via command line.

