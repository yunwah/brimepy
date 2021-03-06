# BrimePy
Asynchronous python wrapper for the [Brime API](https://documenter.getpostman.com/view/11546462/TzCHBAQ8).

## Installation
```
$ python setup.py install
```

## Documentation
There is no documentation currently outside the API script.

## Usage
```python
from brimepy import API

brime = API('client_auth')
json = await brime.users()
await brime.close()
```

## Pre-requisites
These are the following requirements to get setup with BrimePy.
- Python 3.6+ (3.5+ should work, not tested)
- `aiohttp` library
Can be installed via `pip` or `requirements.txt`.