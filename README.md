# egsim-client

Client code to test / showcase eGSIM.

Create your virtual environment (this repo is tested under Python 3.9.7) and install:

```
pip install --upgrade pip setuptolls
pip install notebook
pip install matplotlib
```
Note: the `requests` package should be already shipped with `notebook`. If not the case `pip install requests`.


With the virtual env activated, cd into `notebook` and then:

``` 
jupyter notebook
```


To convert a notebook to HTML from the command line (inside the `notebook` directory)
use `nbconvert`, e.g.:
```
jupyter nbconvert --to html APIv2.0_test_flatfile.ipynb
```