# install from GitHub

## create virtual env

```shell
python3 -m venv .
source bin/activate
```

## install

```shell
$ pip install git+https://github.com/felixonmars/ydcv.git
pip install git+https://github.com/felixonmars/ydcv.git
Collecting git+https://github.com/felixonmars/ydcv.git
  Cloning https://github.com/felixonmars/ydcv.git to /private/var/folders/78/cczt63ls3t1dh7kxy8d7m2z40000gn/T/pip-c4teijq7-build
Installing collected packages: ydcv
  Running setup.py install for ydcv ... done
Successfully installed ydcv-0.6.dev1+g2ef0712
```

```shell
$pip install -e git+https://github.com/felixonmars/ydcv.git#egg=ydcv
Obtaining ydcv from git+https://github.com/felixonmars/ydcv.git#egg=ydcv
  Cloning https://github.com/felixonmars/ydcv.git to ./src/ydcv
Installing collected packages: ydcv
  Running setup.py develop for ydcv
Successfully installed ydcv
```

with `-e`, project will be download to `./src`, code can be edited, and will take effect next time.
