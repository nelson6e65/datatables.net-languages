# DataTables Internationalization

## Description
Language files for [DataTables](http://datatables.net) jQuery Plugin, based on [DataTables/Plugins](https://github.com/DataTables/Plugins), powered by [Transifex](https://www.transifex.com/projects/p/ci_translations/) Translation Platform..

## Installing
- Download the latest [release](https://github.com/nelson6e65/datatables.net-translations/releases).
- Unzip that download.
- Rename the resulting folder to `datatables.net-translations`.
- Then move this folder into your assets directory.

### Via bower
You can install translations for your project with [Bower](http://bower.io):

```bash
bower install --save datatables.net-translations
```

>You can use a build tool, like [Gulp](http://gulpjs.com/) to publish `locale` directory in your public directory, like other assets.


## Usage
Just follow instructions in [DataTables manual](http://datatables.net/manual/i18n).

Translations files named following [ISO 639-1 code namming standard](http://www.loc.gov/standards/iso639-2/php/code_list.php) and using `.json` extension.
So, for example, default Spanish language file is `locale/es/default.json`.

That is the file you will use in the `language.url` option:

```js
$('#example').DataTable( {
    language: {
        url: '/assets/datatables.net-translations/locale/es/default.json'
    }
} );
```

There is another alternative, using mostly icons, but requires [Font Awesome](http://fortawesome.github.io/Font-Awesome/). Usage:

```js
$('#example').DataTable( {
    language: {
        url: '/assets/datatables.net-translations/locale/es/iconic.json'
    }
} );
```

## Contributing
Join the project in [Transifex](https://www.transifex.com/nelson6e65/datatables-translations/) and start to translate.

>Note: If you are not registered yet, you can easily register via Github.
