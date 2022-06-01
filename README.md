# Dyte Task: CLI Tool

* The CLI tool has been made in Python
* There is no necessary installation step.
* Simply, clone the repository and you are good to go.
* All Python packages, required by the program, will get automatically installed/updated as required.
* Arguments for the CLI:
  *  positional arguments: .csv filename
  *  optional arguments:
  *  -h, --help      show this help message and exit
  *  -b , --branch   brance name of Github Repository
  *  -u, --update    Update Version

## Syntaxes
How to run the tool:

* open the terminal
* *python dyte.py <filename.csv> -h* or *python dyte.py <filename.csv> --help* for help
* *python dyte.py <filename.csv> -b <branch name>* or *python dyte.py <filename.csv> --branch <branch name>* for specifying tehe branch on which we need to check for versions and in turn print the required table.
* *python dyte.py <filename.csv> -b <branch name> -u* or *python dyte.py <filename.csv> --branch <branch name> --update* for specifying tehe branch on which we need to check for versions and the required pull request link, and in turn print the required table.
