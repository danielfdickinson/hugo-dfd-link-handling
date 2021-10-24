# DFD Hugo Link Handling

A module for handling links in Hugo

## Status

[![Netlify Status](https://api.netlify.com/api/v1/badges/b54490a1-f9ec-4783-ace8-cf70ead68db7/deploy-status)](https://app.netlify.com/sites/hugo-dfd-link-handling/deploys)

## Demo Site

<https://hugo-dfd-link-handling.wildtechgarden.ca>

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
