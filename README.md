# How to start project

```
-- run nix
nix-shell

-- run pdm
pdm init

-- build pdm
pdm build

-- run project
pdm run main.py

-- if want install new dependencies
pdm add polars

-- if want to build in prod
pip install ../../dist/cari.whl file

-- simulate prod
source ./venv/bin/activate

```