.. vim: foldmarker=[[[,]]]:foldmethod=marker

pip ansible role default variables
==================================

.. contents:: Sections
   :local:

pip management
--------------

.. envvar:: pip_proxy

   pip proxy address

::

  pip_proxy: false


Example:

.. code:: yaml

   pip_proxy: artifactory.yourdomain.com





.. envvar:: pip_proxy_url

   pip proxy index url

::

  pip_proxy_url: false


Example:

.. code::yaml

   pip_proxy_url: http://artifactory.yourdomain.com/artifactory/api/pypi/MyPyPi/simple




