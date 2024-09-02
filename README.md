# Turntable Discover Starter
This repo contains a FastAPI (python) and React (create-react-app) skeleton.

## Installation 
```
Install a python env manager (we like uv)
# On macOS and Linux.
$ curl -LsSf https://astral.sh/uv/install.sh | sh

# On Windows.
$ powershell -c "irm https://astral.sh/uv/install.ps1 | iex"

# With pip.
$ pip install uv

# Check node is installed
# node --version
```

## Run Backend
```
cd backend

uv venv

source .venv/bin/activate

uv pip install -r requirements.txt

python main.py
```

## Run Frontend
```
cd frontend

npm install

npm start
```

