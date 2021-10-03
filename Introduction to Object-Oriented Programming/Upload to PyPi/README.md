# Commands
```
cd 5_exercise_upload_to_pypi

python setup.py sdist

pip install twine
```

## Commands to upload to the PyPi test repository
```
twine upload --repository-url https://test.pypi.org/legacy/ dist/*

pip install --index-url https://test.pypi.org/simple/ [package-name]
```

## Command to upload to the PyPi repository
```
twine upload dist/*

pip install [package-name]
```