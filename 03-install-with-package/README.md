# install with wheel

## create virtual env

```shell
python3 -m venv .
source bin/activate
```

## get package archive

get the download link from [peewee Download files · PyPI](https://pypi.org/project/peewee/#files)

```shell
curl -O https://files.pythonhosted.org/packages/8c/dc/e3e45fcbf8ce8b3ba63e87ef8ef972fcf5e30048b4dffd21697fd86d4cdd/peewee-3.5.0.tar.gz
```

### see what's in archive

```shell
$ tar xzf peewee-3.5.0.tar.gz
$ tree -L 1 peewee-3.5.0
peewee-3.5.0
├── CHANGELOG.md
├── LICENSE
├── PKG-INFO
├── README.rst
├── TODO.rst
├── docs
├── examples
├── peewee.py
├── playhouse
├── pwiz.py
├── runtests.py
└── setup.py
```

almost the same things as in [peewee repo](https://github.com/coleifer/peewee)

## installing from local archive

```shell
pip install peewee-3.5.0.tar.gz
```
