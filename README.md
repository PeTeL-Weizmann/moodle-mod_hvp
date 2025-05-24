# H5P Moodle Plugin + RTL support

Create and add rich content inside your LMS for free. Some examples of what you
get with H5P are Interactive Video, Quizzes, Collage and Timeline.
with RTL support for viewing and editing H5P content.

There is also H5P quiz question type plugin wiht RTL support at:
https://github.com/PeTeL-Weizmann/moodle-qtype_hvp

## Versions

* H5P v1.26.1 for Moodle 4.1+ version is available in branch: v1261_rtl_support
* H5P v1.27.2 for Moodle 4.5+ version is available in branch: m45_hvp_1272_rtl_support

## Usage

If you intend to use the repository directly in production, make sure that you're using the "Stable" branch, as this is the production branch.
There are no guarantees for the state of the other branches at any given time.
Also make sure that all submodules are pulled as well using:

```
git submodule update --init
```

## Description

One of the great benefits with using H5P is that it gives you access to lots of
different [interactive content types](https://h5p.org/content-types-and-applications).

Another great benefit with H5P is that it allows you to easily share and reuse
content. To reuse content, you just download the H5P you would like to edit and
make your changes – e.g. translate to a new language or adjust it to a new
situation.

H5P is:

* Open Source
* Free to Use
* HTML5
* Responsive

The H5P community is actively contributing to improve H5P. Updates and new
features are continuously made available on the community portal
[H5P.org](https://h5p.org).

View our [setup for Moodle](https://h5p.org/moodle) to get information on how
to get started with H5P.

### GDPR Compliance
Information useful to help you achieve GDPR compliance while using this plugin
can be found at [H5P.org's GDPR Compliance](https://h5p.org/plugin-gdpr-compliance) page.

### Development Version
Warning! Never use the development version in production, there are no guarantees for which state the development branches are in at a given time.

Inside your `moodle/mod` folder you run the following command:
```
git clone -b master https://github.com/h5p/h5p-moodle-plugin.git hvp && cd hvp && git submodule update --init
```

### Enabling The Plugin
In Moodle, go to administrator -> plugin overview, and press 'Update database'.

## Settings
Settings can be found at: Site Administration -> Plugins -> Activity Modules -> H5P

## Contributing
Feel free to contribute by:
* Submitting translations to the [Moodle AMOS translator](https://lang.moodle.org/local/amos/view.php)
* Testing and creating issues. But remember to check if the issues is already
reported before creating a new one. Perhaps you can contribute to an already
existing issue?
* Solving issues and submitting code through Pull Requests to the 'master' branch or on a separate feature branch.

## License

This plugin is a fork from the original plugin mod_hvp by [H5P.org](https://h5p.org).
This plugin is licensed under the [GNU GPL v3 or later](https://www.gnu.org/licenses/gpl-3.0.html).
RTL support added and funded by the [Department of science teaching](https://www.weizmann.ac.il/ScienceTeaching/) at the [Weizmann institute of science](https://www.weizmann.ac.il/), israel. 
for the [PeTeL](https://stwww1.weizmann.ac.il/petel/) - personalized teaching and learning envirunment project.

## Credit

* Moodle 4.1 H5P version with RTL support by Nadav Kavalerchik <nadav.kavalerchik@weizmann.ac.il>
* Moodle 4.5 H5P version with RTL support by Oshrat Luski <oshrat.luski@weizmann.ac.il>
