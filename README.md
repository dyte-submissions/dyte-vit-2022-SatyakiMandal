# Dyte Task: CLI Tool

* The CLI tool has been made in Python
* There is no necessary installation step.
* Simply, clone the repository and you are good to go.
* All Python packages, required by the program, will get automatically installed/updated as required.
* Arguments for the CLI:

positional arguments: 
* .csv filename

optional arguments:
*  -h, --help     -> show this help message and exit
*  -u, --update   -> update version

required arguments:
*  -b, --branch   -> brance name of Github Repository
*  -v, --version  -> specify the required version
  

## Syntaxes
How to run the tool:

* open the terminal
* *python dyte.py <filename.csv> -h* or *python dyte.py <filename.csv> --help* for help
  * Example:    *python dyte.py test.csv -h* or *python dyte.py test.csv --help*
 
* *python dyte.py <filename.csv> -b <branch name> -v <version niumber>* or *python dyte.py <filename.csv> --branch <branch name> --version <version number>* for specifying tehe branch on which we need to check for versions, the version nyumber and in turn print the required table.
  * Example:    *python dyte.py test.csv -b main -v 0.23.0* or *python dyte.py test.csv --branch main --version 0.23.0*

* *python dyte.py <filename.csv> -b <branch name> -v <version niumber> -u* or *python dyte.py <filename.csv> --branch <branch name> --version <version number> --update* for specifying tehe branch on which we need to check for versions and the required pull request link, and in turn print the required table.
  * Example:    *python dyte.py test.csv -b main -v 0.23.0 -u* or *python dyte.py test.csv -b main -v 0.23.0 --update*
 

## Test cases:
 
* python dyte.py test.csv -h
* python dyte.py test.csv -b main -v 0.23.0
* python dyte.py test.csv -b main -v 0.23.0 -u
 
