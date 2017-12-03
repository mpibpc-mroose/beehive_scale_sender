============
BeeHiveScale
============


.. image:: https://img.shields.io/travis/mpibpc-mroose/beehive_scale_sender.svg
        :target: https://travis-ci.org/mpibpc-mroose/beehive_scale_sender

Measure the bee hive wight using a load cell, a HX711 load cel amplifier and use a Rasberry Pi to send those measures
to a web server where the storage and visualization takes place.

Dividing the measuring part from the storage and visualization part allows to save energy by just waking up the
RaspPi for the measure (using a WittyPi2) and sleep nearly all the time. This could allow to use the power of an
RaspPi but lowering the energy comsumption in a way to allow solar powering.

* Free software: MIT license

Credits
---------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage

