# Components

Repository of components used in [Raspberry Pi learning resources](https://www.raspberrypi.org/learning/)

[![](components/camera.png)](components/)

## Usage

When writing resources for the Raspberry Pi website, in the repository's `hardware.yml` file, refer to the filename of the component, without file extension (they're all `.png`), like so:

```yml
- name: 1 x Solderless breadboard
  img: breadboard
```

This will use the text "1 x Solderless breadboard" with the image `breadboard.png` (as found in [components/breadboard.png](components/breadboard.png)) and will also link to the component's own page, the contents of which are kept in a markdown file with the same name, e.g. [components/breadboard.md](components/breadboard.md)).

## Image files

Image files live in the [components](components/) folder. They should be `600 x 500` in dimension at 72dpi, on a transparent background.

## Markdown files

Markdown files also live in the [components](components/) folder. They should contain:

- A `h1` of the component title
- The component image
- A one-line description of the component
- A `h2` "Buy"
- A line saying "Buy X from:"
- A list of links to webpages to buy the component from

See [any component markdown](https://github.com/raspberrypilearning/components/blob/master/components/breadboard.md) file as an example.

## Contributing

Images are illustrated by our in-house designer, so we are not likely to accept submissions. Please use issues to provide feedback.

Issues or Pull Requests relating to component information pages are welcome. Component descriptions should be short and simple. Proposals for additional URLs for products is welcome, and will be accepted at our discretion.

## Issues

Open issues at [/issues](https://github.com/raspberrypilearning/components/issues)

## Licence

Images are covered by the following licence:

[![Creative Commons Licence](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

***Components*** by the [Raspberry Pi Foundation](https://www.raspberrypi.org/) is licensed under a [Creative Commons Attribution 4.0 International Licence](http://creativecommons.org/licenses/by-sa/4.0/).

Based on a work at https://github.com/raspberrypilearning/components
