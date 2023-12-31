.. highlight:: shell

============
Contributing
============

Contributions are welcome, and they are greatly appreciated! Every little bit
helps, and credit will always be given.

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at https://github.com/aws/aws-msk-iam-sasl-signer-python/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the GitHub issues for bugs. Anything tagged with "bug" and "help
wanted" is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the GitHub issues for features. Anything tagged with "enhancement"
and "help wanted" is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

aws-msk-iam-sasl-signer-python could always use more documentation, whether as part of the
official aws-msk-iam-sasl-signer-python docs, in docstrings, or even on the web in blog posts,
articles, and such.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at https://github.com/aws/aws-msk-iam-sasl-signer-python/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Contributions are welcome :)

Get Started!
------------

Ready to contribute? Here's how to set up `aws-msk-iam-sasl-signer-python` for local development.

1. Fork the `aws-msk-iam-sasl-signer-python` repo on GitHub.
2. Clone your fork locally::

    $ git clone git@github.com:your_name_here/aws-msk-iam-sasl-signer-python.git

3. Install your local copy into a virtualenv. Assuming you have virtualenvwrapper installed, this is how you set up your fork for local development::

    $ mkvirtualenv aws-msk-iam-sasl-signer-python
    $ cd aws-msk-iam-sasl-signer-python/
    $ python setup.py develop

4. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

   Now you can make your changes locally.

5. When you're done making changes, include testing other Python versions with tox::

    $ python setup.py test or pytest
    $ tox

   To get tox, just pip install them into your virtualenv.

6. Commit your changes and push your branch to GitHub::

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

7. Submit a pull request through the GitHub website.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The pull request should work for Python >= 3.8, and for PyPi. Make sure that the tests pass for all supported Python versions.

Tips
----

To run a subset of tests::


    $ python -m unittest tests.test_auth_token_provider

Deploying
---------

A reminder for the maintainers on how to deploy.
Make sure all your changes are committed (including an entry in HISTORY.rst).
Then run::

$ bump2version patch # possible: major / minor / patch
$ git push
$ git push --tags

Travis will then deploy to PyPI if tests pass.

Licensing
---------

See the LICENSE - https://github.com/aws/aws-msk-iam-sasl-signer-python/blob/main/LICENSE file for our project's licensing. We will ask you to confirm the licensing of your contribution.

We may ask you to sign a Contributor License Agreement (CLA) - http://en.wikipedia.org/wiki/Contributor_License_Agreement for larger changes.
