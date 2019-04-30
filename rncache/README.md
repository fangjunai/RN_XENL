#### rncache 用于iOS编译失败，使用项目内置的依赖进行C++等文件编译

###### 其中 boost_1_63_0.tar.gz 97MB文件较大，github无法上传，本地可自行下载，下载完成，执行 npm run ios-install-after-max 即可

```shell

$ cd rncache && wget -c "https://netix.dl.sourceforge.net/project/boost/boost/1.63.0/boost_1_63_0.tar.gz" -O boost_1_63_0.tar.gz.max


$ shasum ./boost_1_63_0.tar.gz.max
2cecf1848a813de55e5770f324f084c568abca0a ./boost_1_63_0.tar.gz.max

```
