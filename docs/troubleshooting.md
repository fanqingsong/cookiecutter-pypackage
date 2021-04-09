# Troubleshooting

<div class="note">

<div class="title">

Note

</div>

Can you help improve this file? [Edit this file][] and submit a pull
request with your improvements!

</div>

## Windows Issues

-   Some people have reported issues using git bash; try using the
    Command Terminal instead.
-   Virtual environments can sometimes be tricky on Windows. If you have
    Python 3.5 or above installed (recommended), this should get you a
    virtualenv named `myenv` created inside the current folder:

``` powershell
> c:\Python35\python -m venv myenv
```

Or:

``` powershell
> c:\Python35\python c:\Python35\Tools\Scripts\pyvenv.py myenv
```

-   Some people have reported that they have to re-activate their
    virtualenv whenever they change directory, so you should remember
    the path to the virtualenv in case you need it.

  [Edit this file]: https://github.com/zillionare/cookiecutter-pypackage/blob/master/docs/troubleshooting.md