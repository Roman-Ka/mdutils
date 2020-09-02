# The main title

Some text

## Title 1

1. The versioning scheme we use is [SemVer](http://semver.org/).
2. Increase the version number in `mdutils/doc/source/config.py` file.
3. Increase the version number in `mdutils/setup.py` file.
4. Increate the version number to `.github_changelog_generator` file.
5. Run `github_changelog_generator -u didix21 -p mdutils`.
6. Run `python setup.py sdist --formats=gztar,zip`.
7. Upload package to pypi: `twine upload dist/*`.

### Subtitle 1.1

### Subtitle 1.2

Here is some text that has # symbols. #test #noregrets ##

## Title 2

Some more random text

### Subtitle 2.1