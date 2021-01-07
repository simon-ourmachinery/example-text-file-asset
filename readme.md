# How to create a custom asset for The Machinery

This repositry contains the code for the walkthough on how to create a custom asset for [The Machinery](http://ourmachinery.com/).
The walkthrough shows you how to add a custom asset for the engine. This walkthrough expects basic knowledge about how to write a custom plugin. The goal is to have a txt file asset at the end of the walkthrough.

All parts of the walkthrough will cover the following topics:

- How to create your own asset (Part 1)
- How to associate data with your asset (Part 2)
- How to add a custom UI to your asset (Part 2)
- How to create your own importer (Part 3)

The code has been tagged depending on the part of the walkthrough.

- [Part 1](#)
- [Part 2](#)
- [Part 3](#)

## How to build

The plugin code can be build as usual via tmbuild. Therefore the enviroment variable `TM_SDK_DIR` needs to exists and point to the SKD root. Besides, this repositry offers a easy way to publish your plugin into the engines plugin folder via tmbuild's package command.

*Build*

To build your plugin just open the folder of the plugin and open powershell or CMD and run:

```
%TM_SDK_DIR%/bin/tmbuild.exe
```

This will automatically build the plugin and run the unit tests.

*Publish*

To build your plugin just open the folder of the plugin and open powershell or CMD and run:

```
%TM_SDK_DIR%/bin/tmbuild.exe --package publish-debug.json
```

or the release version:

```
%TM_SDK_DIR%/bin/tmbuild.exe --package publish.json
```

This will automatically copy your plugin into your engines plugin folder.


## License

CC0 1.0 Universal

    CREATIVE COMMONS CORPORATION IS NOT A LAW FIRM AND DOES NOT PROVIDE
    LEGAL SERVICES. DISTRIBUTION OF THIS DOCUMENT DOES NOT CREATE AN
    ATTORNEY-CLIENT RELATIONSHIP. CREATIVE COMMONS PROVIDES THIS
    INFORMATION ON AN "AS-IS" BASIS. CREATIVE COMMONS MAKES NO WARRANTIES
    REGARDING THE USE OF THIS DOCUMENT OR THE INFORMATION OR WORKS
    PROVIDED HEREUNDER, AND DISCLAIMS LIABILITY FOR DAMAGES RESULTING FROM
    THE USE OF THIS DOCUMENT OR THE INFORMATION OR WORKS PROVIDED
    HEREUNDER.