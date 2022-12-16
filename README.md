## Solar
Flutter package for using [Solar](https://solariconset.com/)  Icons. Solar is totally free, and you can use this package to bring these awesome icons to your Flutter project. 

This package has made from Solar v1.0 version. following sets are currently available in  this package:

- Bold

## installation:
Add the following line to your `pubspec.yaml` file, under the `dependencies:` section:

``` yaml
dependencies:
  Solar: <latest_version>
```

## Usage 
``` dart


class SolarWidget extends StatelessWidget {

  Widget build(BuildContext context) {
    return IconButton(
      icon: Icon(Solar.alarm), 
      onPressed: () { print("Solar Icons"); }
     );
  }
  
}
```
