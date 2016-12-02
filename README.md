# @nib-styles/grow-layout

Simple `flexbox` sticky footer by adding two classes

## Installation

    npm install --save @nib-styles/grow-layout

## Usage

Add `grow-layout` class to the direct parent element wrapping both the div you wish to expand and the footer.

Add `grow-layout__content` class to the element you wish to expand to take up the remaining space on the page and push the footer to the bottom.

    <div class="grow-layout"">
        <header></header>
        <div class="grow-layout__content"></div>
        <footer></footer>
     </div>
