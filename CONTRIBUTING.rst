Contributing
============

This projects follows the process described in the documented `Ansible Development Cycle`_.

pre-commit
----------

To help ensure high-quality contributions this repository includes a `pre-commit`_ configuration which
corrects and tests against common issues that would otherwise cause CI to fail.

Installation
^^^^^^^^^^^^

Follow the `pre-commit-instructions`_ provided with pre-commit and run ``pre-commit install`` under the repository base.

If for any reason you would like to disable the pre-commit hooks run ``pre-commit uninstall``.

Running pre-commit checks
^^^^^^^^^^^^^^^^^^^^^^^^^

You can trigger it locally with ``pre-commit run --all-files`` or even to run only for a given file ``pre-commit run --files YOUR_FILE``.


.. _Ansible Development Cycle: https://docs.ansible.com/ansible/devel/community/development_process.html
.. _pre-commit: https://pre-commit.com
.. _pre-commit-instructions: https://pre-commit.com/#install
