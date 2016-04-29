.. {% if False %}
CapiTainS/cookiecutter-guidelines
=================================

A CapiTainS Guidelines template for cookiecutter.


Use it now

.. code-block:: bash

	pip install cookiecutter
	cookiecutter https://github.com/capitains/cookiecutter-guidelines.git

```

You will be asked about your basic info (name, project name, app name, etc.). This info will be used in your new project.

.. {% elif True %}

{{user-name}}/{{repo-name}}
===========================

|Hook Status| |Hook Coverage| |Hook Texts| |License|

.. |Hook Status| image:: http://ci.perseids.org/api/rest/v1.0/code/{{user-name}}/{{repo-name}}/status.svg?branch=refs%2Fheads%2Fmaster
   :target: http://ci.perseids.org/repo/{{user-name}}/{{repo-name}}
.. |Hook Coverage| image:: http://ci.perseids.org/api/rest/v1.0/code/{{user-name}}/{{repo-name}}/coverage.svg?branch=refs%2Fheads%2Fmaster
   :target: http://ci.perseids.org/repo/{{user-name}}/{{repo-name}}
.. |Hook Texts| image:: http://ci.perseids.org/api/rest/v1.0/code/{{user-name}}/{{repo-name}}/cts.svg?branch=refs%2Fheads%2Fmaster
   :target: http://ci.perseids.org/repo/{{user-name}}/{{repo-name}}
.. |License| image:: https://img.shields.io/badge/License-{{license.replace("-", "--")}}-blue.svg


{{description}}

.. {% endif %}