# quarto-invoice

This is [quarto](https://quarto.org) extension to create an invoice. The output format is PDF.

## Installation

`quarto use template produnis/quarto-letter`


## Usage

- Fill out your data (sender / recipient) in the YAML-Header.
- if you have your signature as a png file, set parameter `signature: my-signature.png`. If you don't want a graphical signature, set parameter  `signature: ""`.
- The default language is german. If you want to switch to english, set YAML-parameter:

```
---
english: true
lang: en      
---
```

### Invoice
The table of items is created inside an R chunk. You need to change the tibble to fit your needs.

## Screenshots

![](https://i.imgur.com/Rf8jtF1.jpg)
