# Hv2ray [![HitCount](http://hits.dwyl.io/lhy0403/Hv2ray.svg)](http://hits.dwyl.io/lhy0403/Hv2ray)

TODO: 使用 Qt 的跨平台 v2ray 客户端

[![Language grade: C/C++](https://img.shields.io/lgtm/grade/cpp/g/lhy0403/Hv2ray.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/lhy0403/Hv2ray/context:cpp)

[![Total alerts](https://img.shields.io/lgtm/alerts/g/lhy0403/Hv2ray.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/lhy0403/Hv2ray/alerts/)

Linux 构建:
[![Build Status](https://travis-ci.com/lhy0403/Hv2ray.svg?branch=master)](https://travis-ci.com/lhy0403/Hv2ray)

Windows 构建:
[![Build status](https://ci.appveyor.com/api/projects/status/ml51d2s41pqmfgme?svg=true)](https://ci.appveyor.com/project/lhy0403/hv2ray)

Mac OS 构建: 
\[WIP]

# 鸣谢
[@aliyuchang33](https://github.com/aliyuchang33) - Original Author, who initially created this project and gives idea of using Qt to implement.

## 项目依赖包
### Linux
- Qt >= 5
- Python3.5 | 3.6 | 3.7
### Windows 
- Qt = 5
- Python 3.7

## 编译
### Linux
```bash
git clone https://github.com/lhy0403/Hv2ray && cd Hv2ray
mkdir build && cd build
qmake ./
make
```
### Windows
`目前没有稳定的构建方案，请参考 AppVeyor.yml 需要 python3.7 和 Qt Creator`

## License

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
