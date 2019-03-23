# github-orb
Pyton repo

## Static:

```
pip install git+https://github.com/[repo owner]/[repo]@[branch name]
```

## Dynamic:

```
pip install requests
```

```
from github_com.kennethreitz import requests

assert requests.get('https://github.com/nvbn/import_from_github_com').status_code == 200
```

```
pip install import_from_github_com
```

Reference: (https://github.com/nvbn/import_from_github_com)[https://github.com/nvbn/import_from_github_com]

