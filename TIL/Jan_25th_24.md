## ArgParse

`import argparse` is great way to passarguments to a python script from the command line. Tutorials (still need to do more of, found [here](https://docs.python.org/3/library/argparse.html) and [here](https://machinelearningmastery.com/command-line-arguments-for-your-python-script/). Things I learnt:

* argparse treats everything as strings by default, so you need to specify the `type`
* Can specify postitional arguments or named arguments (probably better). Can make them `required=True` if needed
* The argument will be named after the long name in all caps. For example the line:
  `parser.add_argument('-n','--number',required=True,help="display the square", type=int)` will result in an argument named `NUMBER`
