# GalardOS document templates

Repository that holds all the templates for official GalardOS documents:

* **document**: Template used for long form documents such as specifications and documentation.

* **article**: Paper like document to express investigations done by the GalardOS project.

## How to use the templates
The templates come with a custom ``Makefile`` for compiling the end PDF and clear out temporary files generated by the latex compiler. To be able to use this ``Makefile`` you need to install the [texlive](https://www.tug.org/texlive/) latex distribution with all the necessary latex packages (normally linux distributions include a meta package like ``texlive-full`` that include all the latex packages and the compiler).

The ``main.tex`` file contains the template configuration such as the document name, author, logo... that should be changed to fulfill your own needs. After that, you can go to the ``body.tex`` file and start writing your documents!
