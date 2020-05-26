**Activate the virtual environment++
```
source blockchain-env/bin/activate
```

**Install all packages**
```
conda install --yes --file requirements.txt
```

**Run the tests**
```
python3 -m pytest backend/tests
```