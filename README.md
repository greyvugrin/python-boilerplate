### Setup

You only need to run the following once.

```
sudo easy_install pip
pip install virtualenv
virtualenv .

# To enter virtual env
source bin/activate
# To install packages
pip install -r requirements.txt
# To exit virtualenv
deactivate
```

## Adding packages

Follows [this guide](https://www.kennethreitz.org/essays/a-better-pip-workflow).

To add a package, add a new line to *requirements-to-freeze.txt*.

Then

- `pip install -r requirements-to-freeze.txt --upgrade`
- `pip freeze > requirements.txt`

