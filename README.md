# CityGML to CityJSON

A simple Java application to convert CityGML files to CityJSON using [citygml4j](https://github.com/citygml4j/citygml4j).

## Requirements

You need to have installed Java 8 and `gradle`.

## Usage

On Linux/MacOS give execution permission:

```
chmod u+x gradlew
```

Then:
```
./gradlew run --args="[/input/citygml/path] [/output/cityjson/path]"
```