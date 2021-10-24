# DFD Hugo Link Handling

A module for handling links in Hugo

## Status

TBD

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
