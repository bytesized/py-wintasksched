# py-wintasksched
Python interface to the Windows Task Scheduler

## Packaging

If `hatch` isn't already installed, install it `python3 -m pip install hatch`

Then, from the root of the repository, run `hatch build`

The output will be placed in the `dist` directory.

To install the resulting package, you can install the wheel file. For example:
```
python3 -m pip install dist/wintasksched-0.1.0-py3-none-any.whl
```
You may want to do this from a virtual environment, especially if you are testing/developing.

## To do

* Implement `add_task`
* Implement `remove_task`
* Implement `task_exists`
* Command line handling
* Documentation
* Tests
* Linting
* Add GPL language to the command line help
