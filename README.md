# @nib-styles/sticky-footer

Simple `flexbox` sticky footer by adding two classes

## Installation

    npm install --save @nib-styles/sticky-footer
    
## Usage

Add `sticky` class to the direct parent element wrapping both the div you wish to expand and the footer.
Add `sticky__content` class to the element you wish to expand to take up the remaining space on the page and push the footer to the bottom.

    <div class=sticky">
        <header></header>
        <div class="sticky__content"></div>
        <footer></footer>
     </div>