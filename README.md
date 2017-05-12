# coolstory.js
Generate a random story title! Produces masterpieces such as:

    The Breezy Winter
    Between the Worst Souls
    Entrusted by Azure Kings
    The Star Box
    Authority's Worst Bones
    His Skulls
    Old Spider Hand
    The Shade Beans
    How It Is
    Smile

## Basic Usage
coolstory.js works in Node and in a browser.

### Browser

    <script src="https://unpkg.com/coolstory.js"></script>
    <script>
        var amazingTitle = coolstory.title(); // "Doubting"
    </script>

### Node

From the terminal:

    npm install --save coolstory.js

In Node:

    const coolstory = require('coolstory.js');
    let reallyGoodTitle = coolstory.title(); // "It Was the Bat"

### Bower

    TODO

## API

### coolstory.title()
Generate a story title.

    coolstory.title();
    
### coolstory.title(maxLength)
Generate a story title whose length is less than or equal to `maxLength` characters. (including spaces)

    coolstory.title(10);
    
## License

[MIT](/LICENSE)
