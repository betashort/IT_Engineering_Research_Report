# Python

## パッケージ管理

### uv

https://docs.astral.sh/uv/#highlights

#### インストール

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

#### 仮想環境

```
uv venv
```

#### VSCodeでJupyterNotebookを使う
```
uv pip install ipython
ipython kernel install --user --name={name}
```


