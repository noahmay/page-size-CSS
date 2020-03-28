# Page size CSS

Page size CSS is a collection of CSS snippets to create HTML elements for pages. 

Used for creating pages in HTML e.g. creating a printable web-based CV.

## Installation

Download [page.css](page.css) manually.

## Usage

include page.css in your `<head>` like this:

```html
<link rel="stylesheet" href="page.css">
```

create an `<page>` element and set the size

```html
<page size="A4">
    Some text here
</page>
```

you can also set the margin and layout
```html
<page size="A4" margin="standard" layout="landscape">
    Some text here
</page>
```

All available page sizes:

* A0 to A10
* B0 to B10
* C0 to C10
* letter
* half-letter
* legal
* junior-legal
* ledger or tabloid

All available margins:

* standard
* thin
* thick

All available layouts:

* portrait (none)
* landscape

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)