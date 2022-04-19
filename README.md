# slider module
Left-right Slider for blocks.

You can export this module for adding slider functionality.
Slide function takes arguments:

- container - class of main container with images and buttons;
- slide - class of each slide;
- nextArrow - class of button to slide next;
- prevArrow - class of button to slide previous;
- totalCounter - id of element with total slides counter; 
- currentCounter - id of element with current slide counter;
- wrapper - class of wrapper with inner field. Field contains slides;
- field - visible window of all slides.


Example of using such slider:
script.js:

import slider from './modules/slider';

   slider({        
        container: '.offer__slider',
        slide: '.offer__slide',
        nextArrow: '.offer__slider-next',
        prevArrow: '.offer__slider-prev',
        totalCounter: '#total',
        currentCounter: '#current',
        wrapper: '.offer__slider-wrapper',
        field: '.offer__slider-inner'
    });
    
index.html
![image](https://user-images.githubusercontent.com/94894170/164005715-910aa43b-c0f4-4330-bb8f-17e9fced1034.png)


   
