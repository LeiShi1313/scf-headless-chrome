<p align="center">
    <h2 align="center">腾讯云函数无头浏览器</h2>
</p>

<p align="center"><a href="http://serverless.com/">Serverless</a>+<a href="https://cloud.tencent.com/product/scf">云函数</a>+ <a href="https://chromium.googlesource.com/chromium/src/+/lkgr/headless/README.md">无头Chrome</a>+<a href="https://selenium-python.readthedocs.io/">Selenium</a>=运行在腾讯云函数上的无头浏览器</p>


## 如何运行

```
git clone https://github.com/LeiShi1313/scf-headless-chrome.git
cd scf-headless-chrome
https://github.com/LeiShi1313/scf-headless-chrome/releases/download/v1.0.0/headless-chromium-tencent
npm install
pip install -r requirements.txt -t .
sls deploy
```
按照命令行提示登录然后就可以了, :tada::tada::tada:
