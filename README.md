## GitPub - Python library to interact with github's public API
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

Requirements:
<br>------------------
* [pytest](http://doc.pytest.org/en/latest/): Uses __pytest__ as the unit-testing framework. Install using <code>pip install pytest</code>.
* [requests](https://pypi.python.org/pypi/requests/2.11.1): Uses __requests__ for interacting with the various api urls.

How to use:
<br>--------------
* __Load Github Profile & Public Repo details of a user__: Loading a github profile just needs a _username_ to startwith. Here is a small demo with _username_ [__demfier__](https://github.com/Demfier).<br>

Type the following commands in python shell:

```python
import gitpub

username = 'demfier'
profile = gitpub.Profile()
profile.load_gh_profile(username)  # loads profile details of `username`
profile.get_public_repos()  # loads all the public repo details of `username`
```

* __Run Tests__: Just run the command<code>py.test -v</code> to see the test results.

# Contributing
Want to contribute? Awesome, have a look at [contribution instructions](CONTRIBUTING.md).

# LICENSE
The MIT License (MIT) 2017 - [Gaurav Sahu](https://github.com/demfier). Please have a look at the LICENSE.txt for more details.
