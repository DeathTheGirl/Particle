# rgb-values [Public]

A Particle library for rgb-values

_TODO: update this README_

## Usage

Connect XYZ hardware, add the rgb-values library to your project and follow this simple example:

```
#include "rgb-values.h"
rgb-values rgb-values;

void setup() {
  rgb-values.begin();
}

void loop() {
  rgb-values.process();
}
```

See the [examples](examples) folder for more details.

## Documentation

TODO: Describe `rgb-values`

## Contributing

Here's how you can make changes to this library and eventually contribute those changes back.

To get started, [clone the library from GitHub to your local machine](https://help.github.com/articles/cloning-a-repository/).

Change the name of the library in `library.properties` to something different. You can add your name at then end.

Modify the sources in <src> and <examples> with the new behavior.

To compile an example, use `particle compile examples/usage` command in [Particle CLI](https://docs.particle.io/guide/tools-and-features/cli#update-your-device-remotely) or use our [Desktop IDE](https://docs.particle.io/guide/tools-and-features/dev/#compiling-code).

After your changes are done you can upload them with `particle library upload` or `Upload` command in the IDE. This will create a private (only visible by you) library that you can use in other projects. Do `particle library add rgb-values_myname` to add the library to a project on your machine or add the rgb-values_myname library to a project on the Web IDE or Desktop IDE.

At this point, you can create a [GitHub pull request](https://help.github.com/articles/about-pull-requests/) with your changes to the original library. 

If you wish to make your library public, use `particle library publish` or `Publish` command.

## LICENSE
Copyright 2019 SkippyTheIdiot

Licensed under the GNU GENERAL PUBLIC LICENSE license
