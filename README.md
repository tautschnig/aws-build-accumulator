AWS Build Accumulator
-

AWS Build Accumulator collects build jobs from multiple sources before executing them
concurrently. It provides platform-independent job control (timeouts,
return code control) and an output format that is easy to render into
reports (for example, using the built-in renderer).  AWS Build Accumulator
shines where your project uses multiple different build systems or requires
a unified interface describing heterogeneous build jobs.


Requirements
=

* Python 3
* [Ninja](https://ninja-build.org/)
  * `apt-get install ninja-build`, `brew install ninja`
* [Gnuplot](http://www.gnuplot.info/)
  * `apt-get install gnuplot`, `brew install gnuplot`
* [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)
  * `pip3 install jinja2`
* [Voluptuous](https://pypi.org/project/voluptuous/)
  * `pip3 install voluptuous`
