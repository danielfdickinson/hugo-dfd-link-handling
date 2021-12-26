# DFD Hugo Link Handling

A module for handling links in Hugo

## Status

ARCHIVED: This module has been renamed and moved to <https://github.com/link-handling-mod-hugo-dfd>.

This repo remains (although archived) for the benefit of other archived repos that depend on it.

## Demo Site

<https://hugo-dfd-link-handling.wildtechgarden.ca>

## GitHub Repository

<https://github.com/danielfdickinson/hugo-dfd-link-handling>

## Features

TBD

## Basic Usage

### Importing the Module

1. The first step to making use of this module is to add it to your site or theme.  In your configuration file:

   ``config.toml``
   ```toml
   [module]
     [[module.imports]]
       path = "github.com/danielfdickinson/hugo-dfd-link-handling"
   ```
   OR
   ``config.yaml``
   ```yaml
   module:
     imports:
       - path: github.com/danielfdickinson/hugo-dfd-link-handling
   ```
2. Execute
   ```bash
   hugo mod get github.com/danielfdickinson/hugo-dfd-link-handling
   hugo mod tidy
   ```
