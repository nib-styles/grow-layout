# @nib-styles/grow-layout

Simple `flexbox` sticky footer by adding three classes

## Installation

    npm install --save @nib-styles/grow-layout

## Usage

Add `grow-layout` class to the direct parent element wrapping both the div you wish to expand and the footer.

Unfortunately due to this [flexbox issue in IE](https://github.com/philipwalton/flexbugs/blob/master/README.md#3-min-height-on-a-flex-container-wont-apply-to-its-flex-items), we need a second wrapping element for this to work.

Wrap your page with two divs with classes of `grow-layout` and `grow-layout__wrapper`. It is important that these divs are direct parents of the div you wish to expand and the header and footer elements.

Add `grow-layout__content` class to the element you wish to expand to take up the remaining space on the page and push the footer to the bottom.

    <div class="grow-layout">
        <div class="grow-layout__wrapper">
            <header></header>
            <div class="grow-layout__content"> This div will grow vertically to fill the screen</div>
            <footer></footer>
        </div>
     </div>

#### Want to change the flex-direction of the content to be vertical?

Add the modifier class `grow-layout__content--direction-column`.
