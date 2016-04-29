{{cookiecutter.username}}/{{cookiecutter.reponame}}
===========================

|Hook Status| |Hook Coverage| |Hook Texts| |License|

.. |Hook Status| image:: http://ci.perseids.org/api/rest/v1.0/code/{{cookiecutter.username}}/{{cookiecutter.reponame}}/status.svg?branch=refs%2Fheads%2Fmaster
   :target: http://ci.perseids.org/repo/{{cookiecutter.username}}/{{cookiecutter.reponame}}
.. |Hook Coverage| image:: http://ci.perseids.org/api/rest/v1.0/code/{{cookiecutter.username}}/{{cookiecutter.reponame}}/coverage.svg?branch=refs%2Fheads%2Fmaster
   :target: http://ci.perseids.org/repo/{{cookiecutter.username}}/{{cookiecutter.reponame}}
.. |Hook Texts| image:: http://ci.perseids.org/api/rest/v1.0/code/{{cookiecutter.username}}/{{cookiecutter.reponame}}/cts.svg?branch=refs%2Fheads%2Fmaster
   :target: http://ci.perseids.org/repo/{{cookiecutter.username}}/{{cookiecutter.reponame}}
.. |License| image:: https://img.shields.io/badge/License-{{cookiecutter.license.replace("-", "--")}}-blue.svg


{{cookiecutter.description}}