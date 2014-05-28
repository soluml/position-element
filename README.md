# Position: Element
A new value for the CSS property 'position' that allows relative positioning for any element to any element.
+ Authors: Benjamin Solum
+ License: MIT

## About the Project
The CSS Position Property gives us the ability to specify the positioning algorithms for elements. However, we're often limited in scope by the surrounding dom and the current abilities of the position property values. This often leads to ugly JavaScript hacks to circumnavigate the DOM and in doing so, puts the burden on the developer to maintain position should the landscape change (e.x. resizing the browser window).

The hope for this project is to ultimately provide developers with the ability to position a DOM element relatively to another anchor element **anywhere** in the DOM by providing the position property with a CSS selector.  This selector must identify a singular DOM element, either now or in the future. If the DOM element isn't found, the property defers to the body element.

## How does it work?
A "element positioned" element works as if that element was sitting next to the selected element in the DOM and was positioned relatively.




## Dependencies
None! Just include the JS file in your document.

## How Do I Use It?
First things first, make sure that you include the polyfill JS file in your document.


Next, in your CSS, set the position property like so:
    
    .position {
        position: el(#Element);
    }
    
That's it!

## Which selectors work?
Any CSS selectors work, as long as it selects 1 element.  If more than one element is selected, the property defaults to the property work.





## Limitations
There are a few limitations to this polyfill:
+ IE8+ support (IE8 is limited to CSS2 Selectors Only)



## Usage, Demos, Docs
Position: Element is still under active development. More information coming soon.
