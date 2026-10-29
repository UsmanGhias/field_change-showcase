# Decimal Asset Duration

![Odoo](https://img.shields.io/badge/Odoo-17.0-714B67) ![Editions](https://img.shields.io/badge/Editions-Enterprise_(Assets)-2563EB) ![License](https://img.shields.io/badge/License-LGPL--3-0F766E) [![Odoo App Store](https://img.shields.io/badge/Odoo_App_Store-Free-875A7B)](https://apps.odoo.com/apps/modules/17.0/field_change)

Odoo stores an asset's duration (`method_number`) as a whole number, which rules out schedules such as 2.5 years. This app redefines the field with two decimals so fractional durations can be entered.

## What it does

- Asset duration accepts values such as 2.5 or 7.25

## How to use it

1. Install the app, then edit the duration on an asset.

## Screenshots

![Decimal Asset Duration screenshot 1](screenshots/banner.png)

## Technical notes

Technical name `field_change`, Odoo 17.0.

Overrides `account.asset.method_number` as a Float with digits (6, 2). Depends on `account`.

> Review the depreciation board after changing the duration of an existing asset.

## Get the module

Download it free from the [Odoo App Store](https://apps.odoo.com/apps/modules/17.0/field_change).

Need it on another Odoo version, with changes for your workflow, or installed and tested on Odoo.sh? Email [iusmanghias@gmail.com](mailto:iusmanghias@gmail.com?subject=field_change%20customisation) or see [CODCrafters](https://codcrafters.org).

---

This repository is the product page. The module itself is downloaded from the Odoo App Store.

Built by [Usman Ghias](https://usmanghias.co.uk), [CODCrafters](https://codcrafters.org).
