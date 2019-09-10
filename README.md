# libinit
template for the structure of python library


## Preparing
This repository is now a template repository.  
You can use this template repository for creating libraries easily, using github template feature!

1. Clone this repository and change directory to new cloned directory
```
git clone https://github.com/mzntaka0/libinit.git ${new_repo_name}
cd ${new_repo_name}
```

2. Change remote repository url (First need to create remote repository. e.g.)on Github)
```
git remote set-url origin ${new_repo_url}
```

3. Set reporitory information
```
sudo mv src/version.py.example src/version.py
vi src/version.py

-----------------------------------
# -*- coding: utf-8 -*-
"""Metadata of package."""
__version__ = ''
__title__ = ''
__description__ = ''
__url__ = ''
__author__ = ''
__author_email__ = ''
__license__ = 'Apache Software License'
```

4. Initial commit
```
git add .
git commit -m 'Initial commit'
git push -u origin master
```
