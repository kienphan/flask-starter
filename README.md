### Flask Starter Web Development

- You should have Python Environment before install flask-starter app
  - python3
  - virtualenv
  - pip3

> Mac OS

```bash
brew install python3
pip3 install virtualenv
```

> Ubuntu

```bash
sudo apt-get install -y python3 python3-pip python3-virtualenv
```

- Checkout Project

```bash
cd ~/your/path
git clone git@github.com:kienphan/flask-starter.git
```

- Go to inside Project and install

```bash
cd ~/your/path/flask-starter
virtualenv venv
cp .env.example .env
source .env
```

- Install Flask

```bash
pip3 install flask
```

- Execute `run.py` to run

```bash
$ python3 run.py

* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
* Restarting with stat
* Debugger is active!
* Debugger PIN: 118-513-369
```