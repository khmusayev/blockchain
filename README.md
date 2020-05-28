**Activate the virtual environment**
```
source blockchain-env/bin/activate
```

**Install all packages**
```
conda install --yes --file requirements.txt
```

**Run the tests**
```
python -m pytest backend/tests
```

**Run the application and the api**
```
python3 -m backend.app
```

**Run a peer instance**
```
set PEER=TRUE && python -m backend.app
```