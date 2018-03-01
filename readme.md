
This is a batch script for windows to give you a visual indication that [pipenv](https://github.com/pypa/pipenv) is in a shell.

Instructions:

1. Download the pvshell.cmd file and put it anywhere you like.
2. Then add the pvshell.cmd location to you path (you may need to restart your computer).
2. When in your python project folder, run `pvshell` and it will prepend your current prompt with `(pipenv shell)` and run pipenv shell internally.
3. Use `exit` like normal to exit pipenv shell. Your prompt will change back to what it was before.


Here are some discussions about adding this natively to pipenv:
* https://github.com/pypa/pipenv/issues/1509
* https://github.com/pypa/pipenv/issues/1046
* https://github.com/pypa/pipenv/issues/1036
* https://github.com/pypa/pipenv/issues/880
