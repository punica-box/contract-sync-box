# contract-sync-box

A box came from TC SHENZHEN Hackathon 2018. This box is contributed by [includeleec](https://github.com/includeleec).

## 简介

基于 `Python` 开发的一个同步本体智能合约的小工具。

## 快速上手

- 运行程序

```shell
virtualenv --no-site-packages venv

.\venv\Scripts\activate

pip install -r requirements.txt

python ont_block_sync.py
```

- 创建可执行文件

```shell
cd src

pyinstaller -F --i ont.ico ont_block_sync.py
```