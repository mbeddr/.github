# mbeddr

:wave: Welcome to the `mbeddr` GitHub organization.

> mbeddr aims at creating a different way of developing embedded software systems.
> Instead of using archaic modeling tools and manually written C code, we use the open source [JetBrains MPS language workbench](https://www.jetbrains.com/mps) to create an integrated approach to embedded development, where C programming, DSLs, domain specific extensions to C, product line variability, requirements traceability and model checking are supported directly.

## documentation

- old homepage: [mbeddr.com](http://mbeddr.com/)
- [mbeddr user guide](http://mbeddr.com/userguide/UserGuideExport.html) + [mbeddr documentation language](http://mbeddr.com/files/documentationdocumentation.pdf)
- practical knowledge (MPS + platforms): [MPS Platform Docs](http://mbeddr.com/mps-platform-docs/)

## mbeddr platform

If you are interested in the reusable part of mbeddr, have at look at the old [mbeddr platform page](http://mbeddr.com/platform.html) and visit the repository at [mbeddr.core](https://github.com/mbeddr/mbeddr.core).
Some of the old documentation can still be found in the [mbeddr.core wiki](https://github.com/mbeddr/mbeddr.core/wiki), the rest of it has moved to [MPS Platform Docs](http://mbeddr.com/mps-platform-docs/mbeddr).
Some plugins that were migrated to MPS-extensions are documented in the [MPS-extensions documentation](https://jetbrains.github.io/MPS-extensions/).
For everything else there are sandboxes and test cases in the corresponding repositories to learn from.

## Other projects and platforms

- [MPS-extensions](https://github.com/JetBrains/MPS-extensions): The MPS extensions aim to ease language development within MPS.
- [iets3.opensource](https://github.com/IETS3/iets3.opensource): The platform of the IETS3 research project.
- [mbeddr.formal](https://github.com/mbeddr/mbeddr.formal): FASTEN (FormAl SpecificaTion ENvironment) is a set of DSLs to experiment with rigorous systems and safety engineering.
- [mps-qa](https://github.com/mbeddr/mps-qa): Quality Assurance Tooling for Jetbrains' MPS


## Gradle + Maven dependencies

- [mps-gradle-plugin](https://github.com/mbeddr/mps-gradle-plugin): miscellaneous tasks that were found useful when building MPS-based projects with Gradle.
- [mps-build-backends](https://github.com/mbeddr/mps-build-backends): command-line utilities used e.g. by Gradle plugins to generate or check models.
- [build.publish.mps](https://github.com/mbeddr/build.publish.mps): contains a gradle script for publishing MPS and its jars to a few Maven repositories.
- [build.publish.jdk](https://github.com/mbeddr/build.publish.jdk): the published Jetbrains Runtime Environment for MPS

For a broader overview of MPS resources, please visit [mps.rocks](https://mps.rocks/).

## Contact

Join the dicussion on [Slack](https://slack-mps.jetbrains.com) in the #mbeddr room.
