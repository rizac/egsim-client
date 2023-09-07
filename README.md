# egsim-client
Client code to test / showcase eGSIM

Create your virtual environment (this repo is tested under Python 3.9.7)

With the virtual env activated, cd into `notebook` and then:

``` 
jupyter notebook
```

Required packages:
```
pip install notebook   # which should also include the requests package
pip install matplotlib
```

Note: to convert to HTML from the command line (inside the `notebook` directory):
`jupyter nbconvert --to html APIv2.0_test_flatfile.ipynb`
