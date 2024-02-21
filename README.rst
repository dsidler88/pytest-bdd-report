=================
pytest-bdd-report
=================

Requirements
------------

* Jinja2
* pytest
* pytest-bdd


Installation
------------

1. Ensure that you have `pytest`_ and `pytest-bdd`_ installed in your development environment.
2. Open a terminal window.
3. Execute the following command to install the `pytest-bdd-report` plugin via `pip`_ from `PyPI`_

::

    $ pip install pytest-bdd-report


Usage
-----

Once the plugin is installed, you can generate BDD reports in an HTML file using the command

::

    $ pytest --bdd-report="report.html"


Contributing
------------
Contributions are very welcome. Tests can be run with `pytest`_, please ensure
the coverage at least stays the same before you submit a pull request.

License
-------

Distributed under the terms of the `MIT`_ license, "pytest-bdd-report" is free and open source software


Issues
------

If you encounter any problems, please `file an issue`_ along with a detailed description.

.. _`Cookiecutter`: https://github.com/audreyr/cookiecutter
.. _`@hackebrot`: https://github.com/hackebrot
.. _`MIT`: http://opensource.org/licenses/MIT
.. _`BSD-3`: http://opensource.org/licenses/BSD-3-Clause
.. _`GNU GPL v3.0`: http://www.gnu.org/licenses/gpl-3.0.txt
.. _`Apache Software License 2.0`: http://www.apache.org/licenses/LICENSE-2.0
.. _`cookiecutter-pytest-plugin`: https://github.com/pytest-dev/cookiecutter-pytest-plugin
.. _`file an issue`: https://github.com/mattiamonti/pytest-bdd-report/issues
.. _`pytest`: https://github.com/pytest-dev/pytest
.. _`tox`: https://tox.readthedocs.io/en/latest/
.. _`pip`: https://pypi.org/project/pip/
.. _`PyPI`: https://pypi.org/project
.. _`pytest-bdd`: https://github.com/pytest-dev/pytest-bdd
