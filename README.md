<p align="center">
    <h2 align="center">Headless Chrome on SCF&nbsp;&nbsp;</h2>
</p>

<p align="center">
    <a href="https://github.com/LeiShi1313/scf-headless-chrome/blob/master/README_CN.md">中文文档</a>
</p>

<p align="center">Headless chrome running on tencent serverless cloud function</p>
<p align="center">with <a href="http://serverless.com/">Serverless</a>, <a href="https://cloud.tencent.com/product/scf">Tencent SCF</a>, <a href="https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md">Headless Chrome</a> and <a href="https://selenium-python.readthedocs.io/">Selenium</a>!</p>

## How to run this project

```
git clone https://github.com/LeiShi1313/scf-headless-chrome.git
cd scf-headless-chrome
wget -O chromedriver/headless-chromium-tencent https://github.com/LeiShi1313/scf-headless-chrome/releases/download/v1.0.0/headless-chromium-tencent
npm install
pip install -r requirements.txt -t .
sls deploy
```
and that's it, :tada::tada::tada:
