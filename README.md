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

``` html
<script src="https://unpkg.com/coolstory.js"></script>
<script>
    var amazingTitle = coolstory.title(); // "Doubting"
</script>
```

### Node

After installing it using npm: `npm install coolstory.js`

``` js
const coolstory = require('coolstory.js');
let reallyGoodTitle = coolstory.title(); // "It Was the Bat"
```

### Bower

``` bash
bower install --save coolstory.js
```

Include the file `coolstory.js` in your project.

## API

### coolstory.title()
Generate a story title.

``` js
coolstory.title();
```

### coolstory.title(maxLength)
Generate a story title whose length is less than or equal to `maxLength` characters. (including spaces)

``` js
coolstory.title(10);
```

## License

[MIT](/LICENSE)
