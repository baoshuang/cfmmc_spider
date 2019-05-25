# cfmmc_spider

###自动识别验证码登录[期货保证金监控中心](https://investorservice.cfmmc.com/)爬取数据


使用tesseract识别码

安装tesseract-ocr环境
```
sudo apt-get install g++
sudo apt-get install autoconf automake libtool
sudo apt-get install pkg-config
sudo apt-get install libpng-dev
sudo apt-get install libjpeg8-dev
sudo apt-get install libtiff5-dev
sudo apt-get install zlib1g-dev
git clone git@github.com:DanBloomberg/leptonica.git
cd leptonica
./autogen.sh
./configure
make
make install
sudo apt-get install tesseract-ocr
```
安装pytesseract
```
pip install pytesseract
```