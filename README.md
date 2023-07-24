## How to start

The project uses Poetry for dependencies management and packaging.
If you do not have Poetry installed, you can run the `boostrap.ps1` script.
This will install Python and Poetry as configured in `scoopfile.json`.

```powershell
Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope CurrentUser -Force
.\bootstrap.ps1
```

To install all dependencies in a virtual environment, type:

```shell
poetry install --with=dev --with=docs
```

For those using [VS Code](https://code.visualstudio.com/) there are tasks defined for the most common commands:

- install dependencies
- generate documentation

See the `.vscode/tasks.json` for more details.
