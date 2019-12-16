# IoT Engineering
## Hands-on of lesson 13
For slides and example code, see [lesson 13](../../../fhnw-iot/blob/master/13/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Parametric design, 15'
* Download [OpenSCAD](https://www.openscad.org/) and create a simple 3D design.
* OpenSCAD is a domain specific [language for CAD](https://en.wikibooks.org/wiki/OpenSCAD_User_Manual/The_OpenSCAD_Language).
* Objects can be built by [subtracting](https://en.wikibooks.org/wiki/OpenSCAD_User_Manual/The_OpenSCAD_Language#difference) simple shapes.
* Design a box that fits a [Raspberry Pi Zero](https://blog.protoneer.co.nz/raspberry-pi-zero-footprint-dimensions/).
* Export as STL and slice it e.g. in [Cura](https://ultimaker.com/software/ultimaker-cura).
* Done? Take a look at [this model](https://github.com/sgall17a/Raspi2_case/blob/master/rasppi2.scad).

### b) Second gen products, 15'
* Compare the [Echo Dot](https://www.ifixit.com/Teardown/Amazon+Echo+Dot+Teardown/61304) ([2nd gen](https://www.ifixit.com/Teardown/Amazon+Echo+Dot+2nd+Generation+Teardown/110989)) to the original [Echo](https://www.ifixit.com/Teardown/Amazon+Echo+Teardown/33953).
* What was changed, and what could be the rationale?
* If an injection mold is $10k, how much was saved?
* Which other parts could bring down the price?
* Be prepared to present your findings.

### Submitting results
* [Commit and push](#git) local changes to your repository.
* Want a review? [Create an issue](../../issues/new), mention me (@tamberg).

## Tools
### Git
On your computer
* In the hands-on repository [fork for your class](../../network/members), in README.md, click the _GitHub Classroom link_.
* Once you accept the assessment, you get a personal, private repository URL for your _USER_NAME_:<pre>
http://github.com/fhnw-iot-CLASS/fhnw-iot-work-13-USER_NAME</pre>

On your computer or Raspberry Pi
* Clone the repository<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Add a file<pre>
    $ git add FILE</pre>
* Commit changes<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Push changes<pre>
    $ git push</pre>

## Wiki
- [IoT Engineering Wiki](https://github.com/tamberg/fhnw-iot/wiki)

## Support
- [IoT Engineering Slack](https://fhnw-iot.slack.com/)
