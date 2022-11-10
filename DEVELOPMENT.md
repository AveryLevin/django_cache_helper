# Create Release

1. `rm -rf dist`
1. Update version in `cache_helper/__init__.py`
1. `pip install -r dev_requirements.txt`
1. `python -m build`
1. `twine upload dist/*`
