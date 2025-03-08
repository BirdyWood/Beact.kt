
![Logo](src/main/resources/drawable/Logo_NameIcon.svg?raw=true)
# 

Beact is a compiler for a new language that improves the HTML language. It uses the extension Beact Markup Language (.bml) to give news features to this old language.

## Documentation

[Wiki](https://example.com) Not yet available


## Installation

Installer packages for Windows is found [here](https://github.com/BirdyWood/beact.kt/releases/latest).

## How to use?

To build your project, execute this command

```sh
beact build
```

<!--You can **customize** the build by creating a `./config_beact.json` file

```json
{
  "name": "beact_website",
  "version": "1.0.0",
  "outputDir": "./out",
  "watchDir": "./",
  "excludeDir": [
    "node_modules"
  ]
}
```-->

## Usage/Examples

```html
<:BigTitle content="BigTitle_content">
    <h1><#BigTitle_content/> - <#Name/></h1>
    <hr />
</:BigTitle>


<$foreach range="0..10">
    <BigTitle Name="Title"><#times/></BigTitle>
</$foreach>
```


## FAQ

#### Why should I use Beact?

Instead of others librairies to improve frontend developpment, Beact is based on HTML to provide more features to code a website. And it compiles bml files directly in HTML files after making modificatoins, so it's easy to export the files to the production server.

#### How does Beact provide new features while using the HTML structure?

Beact introduce a new type of tag that starts with ```$```. This tag provides access to new functions like
```<$foreach range="0..3"> </$foreach>```


## Feedback

If you have any feedback, please reach out to us at [support@birdywood.fr](mailto:\\support@birdywood.fr)


## License

[MIT](LICENSE.md)
