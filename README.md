# Xml-Sample-Data-Generator

An Xml data generator to produce sample data. 
It's suited to generate XML documents with elements containing random words, dates, numbers or urls.

## Capabilities
Xml-Sample-Data-Generator is a command line tool build with node.js to generate XML sample data.
You can configure the XML elements of your sample data by providing a config files that describes the XML elements(Type,length..).

## Setup
1.Install node.js dependencies:

```
npm install
```
2.create a configuration file that describes the format of your XML elements:

An example is provides. See example_xml_elements_config.json

3.Run it:

You must provide the number of xml documents to generate and the config file path.

Here is an example:

```
node bin/sampledatagenerator -n 100000 -c example_xml_elements_config.json
```

