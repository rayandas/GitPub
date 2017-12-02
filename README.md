# GitPub - Python library to interact with github's public API
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


## Getting started!
Follow up these instructions if you want to see it in action up and running on your machine.

### <em>System Requirements</em>:
<br>------------------
* [pytest](http://doc.pytest.org/en/latest/): Uses __pytest__ as the unit-testing framework. Install using <code>pip install pytest</code>.
* [requests](https://pypi.python.org/pypi/requests/2.11.1): Uses __requests__ for interacting with the various api urls.
* And of course Python3 (https://www.python.org/downloads/release/python-363/): The bread-butter!


### <em>Few Final Steps</em>:
<br>
<i>Step 1:</i>__Load Github Profile & Public Repo details of a user__: Loading a github profile just needs a _username_ to startwith. Here is a small demo with _username_ [__demfier__](https://github.com/Demfier).<br>
<br>
<i>Step 2:</i>Type the following commands in python shell:

```python
import gitpub

username = 'test' # there goes your username, inside ' '
profile = gitpub.Profile()
profile.load_gh_profile(username)  # loads profile details of `username`
profile.get_public_repos()  # loads all the public repo details of `username`
```
<br>
<i>Step 3:</i>__Run Tests__: Just run the command<code>py.test -v</code> to see the test results.
   and you're done!!
<br>


## Contribution
Want to contribute? Awesome, we always wanted a larger development base.Jump into  [contribution instructions](CONTRIBUTING.md) for further instructions.

# LICENSE
The MIT License (MIT) 2017 - [Gaurav Sahu](https://github.com/demfier). Please have a look at the LICENSE.txt for more details.
