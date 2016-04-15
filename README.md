# Rosalind Serif

Rosalind Serif is a fork of [Merriweather](https://github.com/EbenSorkin/Merriweather) and is released under
the SIL Open Font License v1.1 (<http://scripts.sil.org/OFL>) with Reserved Font Name 'Rosalind Serif'.

Major Changes:

* Align x-height to the x-height of Georgia
* Redesign the Questionmark character



## Weights and Styles
Rosalind Serif is available in Black, Black Italic, Bold, Bold Italic, Regular, Regular Italic, Light and Light Italic.

## Usage
Rosalind Serif is available in TrueType as well as OpenType format as well as WOFF, WOFF2 and EOT format for web usage.

## Web
Rosalind comes with a set of webfonts perfectly subsetted for Cyrillic, Cyrillic Ext, Greek, Greek Ext, Latin Ext and a combined
subset of Latin and Greek glyphs. Make sure to target the right subset using the ```unicode-range```, ```font-style``` and ```font-weight``` 
declaration in CSS:


    @font-face{
      font-family: "Rosalind Serif";
      font-style: normal;
      font-weight: 700;
      src: url("rosalind-serif-v1-latin-700.eot");
      src: url("rosalind-serif-v1-latin-700.eot?#iefix") format("embedded-opentype"), 
           url("rosalind-serif-v1-latin-700.woff2") format("woff2"), 
           url("rosalind-serif-v1-latin-700.woff") format("woff"), 
           url("rosalind-serif-v1-latin-700.ttf") format("truetype");
      unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2212, U+2215, U+E0FF, U+EFFD, U+F000;
    }
    
You can find the relevant unicode ranges in the following table.

| Subset | Unicode Range | CSS Definition |
|----|----|----|
| Cyrilic Ext | 0460-052F, 20B4, 2DE0-2DFF, A640-A69F | U+0460-052F, U+20B4, U+2DE0-2DFF, U+A640-A69F  |
| Cyrilic | 0400-045F, 0490-0491, 04B0-04B1, 2116 | U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116 |
| Latin Ext | 0100-024F, 1E00-1EFF, 20A0-20AB, 20AD-20CF, 2C60-2C7F, A720-A7FF | U+0100-024F, U+1E00-1EFF, U+20A0-20AB, U+20AD-20CF, U+2C60-2C7F, U+A720-A7FF |
| Latin | 0000-00FF, 0131, 0152-0153, 02C6, 02DA, 02DC, 2000-206F, 2074, 20AC, 2212, 2215, E0FF, EFFD, F000 | U+0000-00FF, U+0131, U+0152-0153, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2212, U+2215, U+E0FF, U+EFFD, U+F000 |
| Latin Greek | 0000-00FF, 0131, 0152-0153, 02C6, 02DA, 02DC, 2000-206F, 2074, 20AC, 2212, 2215, E0FF, EFFD, F000, 0394, 03A9, 03BC, 03C0 | U+0000-00FF, U+0131, U+0152-0153, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2212, U+2215, U+E0FF, U+EFFD, U+F000, U+0394, U+03A9, U+03BC, U+03C0 |




The x-height of Rosalind Serif matches the one of Georgia. In order to reduce the effects of FOUT (Flash of unstyled text) or fallback characters
you should setup your font-stack like this:

    font-family: "Rosalind Serif", Georgia, serif;
    

## Licence

Copyright (c) 2016, ResearchGate (www.researchgate.net) with Reserved Font Name 'Rosalind Serif'.

Rosalind Serif is licensed under the SIL Open Font License v1.1 (<http://scripts.sil.org/OFL>)


