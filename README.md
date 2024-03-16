<img width="256" alt="image" src="https://github.com/zcyc/extractor/assets/9925064/9580609e-f164-4190-b6cc-8e230cb4c6a8">

# extractor

计算机软件著作权程序鉴别材料（源代码）提取器

## 打包安装

### Windows
```shell
python setup.py sdist
pip install .\dist\extractor-1.1.0.tar.gz
```

### macOS & Linux
```shell
python3 setup.py sdist
pip3 install dist/extractor-1.1.0.tar.gz
```

## 全部参数

```
Usage: extractor [OPTIONS]

Options:
  -t, --title TEXT            软件名称+版本号，默认为软件著作权程序鉴别材料生成器V1.0，此名称用于生成页眉
  -i, --indir PATH            源码所在文件夹，可以指定多个，默认为当前目录
  -e, --ext TEXT              源代码后缀，可以指定多个，默认为Python源代码
  -c, --comment-char TEXT     注释字符串，可以指定多个，默认为#、//
  --font-name TEXT            字体，默认为宋体
  --font-size FLOAT RANGE     字号，默认为五号，即10.5号
  --space-before FLOAT RANGE  段前间距，默认为0
  --space-after FLOAT RANGE   段后间距，默认为2.3
  --line-spacing FLOAT RANGE  行距，默认为固定值10.5
  --exclude PATH              需要排除的文件或路径，可以指定多个
  -o, --outfile PATH          输出文件（docx格式），默认为当前目录的code.docx
  -v, --verbose               打印调试信息
  --help                      Show this message and exit.
```

## 使用手册
[点击查看](https://github.com/zcyc/extractor/wiki)
