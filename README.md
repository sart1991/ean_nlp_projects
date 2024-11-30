# Getting started
1. Create virtual env
``` bash
uv venv --seed --python 3.10.15
```

2. Activate virtual env
``` bash
source ./.venv/bin/activate
```

3. Install dependencies
``` bash
uv pip install -r requirements.txt
```

# Update dependencies
1. After installing using:
``` bash
uv pip install PACKAGE
```

2. Freeze requirements
``` bash
uv pip freeze | uv pip compile - -o requirements.txt
```