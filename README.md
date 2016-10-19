# 2016-illo-rst

[![Documentation Status](https://readthedocs.org/projects/2016-illo-rst/badge/?version=latest)](http://2016-illo-rst.readthedocs.io/en/latest/?badge=latest)
                
Use a virtualenv, install sphinx and stuff. Then edit `conf.py` to uncomment ['.rst','.md'] so sphinx will render both .rst and .md

```
  source activate py35
  pip install sphinx
  pip install sphinxcontrib-images
  pip install recommonmark
  vi conf.py
  # local copy of index.html
  make html
  # do this before pushing to github so you don't have to deal with all the _build files
  make clean
  ```
  
Import github repo to readthedocs to make sphinx pages publi on the web.
  
[https://readthedocs.org/](https://readthedocs.org/)
