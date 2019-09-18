# PyVeryStream

Python wrapper for [verystream.com API](https://api.verystream.com/ "Verystream API")

## Install

``` bash

    $ pip install git+https://github.com/odysseusmax/PyVeryStream.git
```


## Usage


All `API` features are implemented.

**Retrieve account info**

``` python

    from verystream import Verystream

    vs = Verystream('login', 'key')

    account_info = vs.account_info()
    print(account_info)
```


**Upload file**

``` python

    from verystream import Verystream

    vs = Verystream('login', 'key')

    uploaded_file_info = vs.upload_file('/home/username/file.txt')
    print(uploaded_file_info)
 ```


**Retrieve file info**

``` python

    from verystream import Verystream

    vs = Verystream('login', 'key')

    # Random file id.
    file_id = 'YMTqhQAuzVX'

    file_info = vs.file_info(file_id)
    print(file_info)
```

## Documentation


Documentation is not available currently.

## Note


Forked from [PyOpenLoad](https://github.com/mohan3d/PyOpenload) and adapted to work with Verystream API
