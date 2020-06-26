# Virtual environment

We will make a virtualenv called `myvenv`. The general command will be in the format:

```command-line
$ python3 -m venv myvenv
```

Start your virtual environment by running:

```command-line
$ source myvenv/bin/activate
```

Remember to replace `myvenv` with your chosen virtualenv name!

> NOTE: sometimes source might not be available. In those cases try doing this instead:

```command-line
$ . myvenv/bin/activate
```

## Requirements

First create a `requirements.txt` file inside of the project folder. In this file, add the requirements:

For example:

```
Django~=2.2.4
```

### Installing requirements

Now, run `pip install -r requirements.txt` to install the requirements.
