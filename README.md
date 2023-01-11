# Health_project
health智“囊”微信小程序开发

远程仓库的搭建

$ git init -b dev

Initialized empty Git repository in D:/Project/Health_project/.git/

$ git status

On branch dev

$ git add .

warning: LF will be replaced by CRLF in project.config.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in project.private.config.json.
The file will have its original line endings in your working directory

$ git config --global core.autocrlf true

$ git add .

$ git commit -m 'codes'

[dev (root-commit) 64c7572] codes
 114 files changed, 1712 insertions(+)
 create mode 100644 app.js
 create mode 100644 app.json
 create mode 100644 app.wxss
 create mode 100644 pages/account/account.js
 create mode 100644 pages/account/account.json
 create mode 100644 pages/account/account.wxml
 create mode 100644 pages/account/account.wxss
 create mode 100644 pages/imgs/aboutUs.png
 create mode 100644 pages/imgs/account.png
 create mode 100644 pages/imgs/account1.png
 create mode 100644 pages/imgs/agree.png
 create mode 100644 pages/imgs/backMoney.png
 create mode 100644 pages/imgs/buy.png
 create mode 100644 pages/imgs/car.png
 create mode 100644 pages/imgs/code.png
 create mode 100644 pages/imgs/code2.png
 create mode 100644 pages/imgs/disagree.png
 create mode 100644 pages/imgs/dotted.png
 create mode 100644 pages/imgs/envelop.png
 create mode 100644 pages/imgs/frwWord.png
 create mode 100644 pages/imgs/frwlogo.png
 create mode 100644 pages/imgs/gift.png
 create mode 100644 pages/imgs/give.png
 create mode 100644 pages/imgs/home.png
 create mode 100644 pages/imgs/home1.png
 create mode 100644 pages/imgs/idcard.png
 create mode 100644 pages/imgs/info.png
 create mode 100644 pages/imgs/invest.png
 create mode 100644 pages/imgs/invest1.png
 create mode 100644 pages/imgs/investPic1.png
 create mode 100644 pages/imgs/investPic11.png
 create mode 100644 pages/imgs/investPic2.png
 create mode 100644 pages/imgs/investPic22.png
 create mode 100644 pages/imgs/investTit.png
 create mode 100644 pages/imgs/line.png
 create mode 100644 pages/imgs/money.png
 create mode 100644 pages/imgs/more.png
 create mode 100644 pages/imgs/more1.png
 create mode 100644 pages/imgs/myinvest.png
 create mode 100644 pages/imgs/notice.png
 create mode 100644 pages/imgs/people.png
 create mode 100644 pages/imgs/phoneCode.png
 create mode 100644 pages/imgs/projectLine1.png
 create mode 100644 pages/imgs/protect.png
 create mode 100644 pages/imgs/ready.png
 create mode 100644 pages/imgs/recommend.png
 create mode 100644 pages/imgs/record.png
 create mode 100644 pages/imgs/reset.png
 create mode 100644 pages/imgs/right.png
 create mode 100644 pages/imgs/seePass.png
 create mode 100644 pages/imgs/send.png
 create mode 100644 pages/imgs/star.png
 create mode 100644 pages/index/index.js
 create mode 100644 pages/index/index.json
 create mode 100644 pages/index/index.wxml
 create mode 100644 pages/index/index.wxss
 create mode 100644 pages/index/noticeInfo.js
 create mode 100644 pages/index/noticeInfo.json
 create mode 100644 pages/index/noticeInfo.wxml
 create mode 100644 pages/index/noticeInfo.wxss
 create mode 100644 pages/index_img/img01.jpg
 create mode 100644 pages/index_img/img02.jpg
 create mode 100644 pages/index_img/img03.jpg
 create mode 100644 pages/investment/invest.js
 create mode 100644 pages/investment/invest.json
 create mode 100644 pages/investment/invest.wxml
 create mode 100644 pages/investment/invest.wxss
 create mode 100644 pages/more/more.js
 create mode 100644 pages/more/more.json
 create mode 100644 pages/more/more.wxml
 create mode 100644 pages/more/more.wxss
 create mode 100644 pages/moreSonPages/more1.js
 create mode 100644 pages/moreSonPages/more1.json
 create mode 100644 pages/moreSonPages/more1.wxml
 create mode 100644 pages/moreSonPages/more1.wxss
 create mode 100644 pages/moreSonPages/more2.js
 create mode 100644 pages/moreSonPages/more2.json
 create mode 100644 pages/moreSonPages/more2.wxml
 create mode 100644 pages/moreSonPages/more2.wxss
 create mode 100644 pages/moreSonPages/more3.js
 create mode 100644 pages/moreSonPages/more3.json
 create mode 100644 pages/moreSonPages/more3.wxml
 create mode 100644 pages/moreSonPages/more3.wxss
 create mode 100644 pages/moreSonPages/more4.js
 create mode 100644 pages/moreSonPages/more4.json
 create mode 100644 pages/moreSonPages/more4.wxml
 create mode 100644 pages/moreSonPages/more4.wxss
 create mode 100644 pages/projects/project1.js
 create mode 100644 pages/projects/project1.json
 create mode 100644 pages/projects/project1.wxml
 create mode 100644 pages/projects/project1.wxss
 create mode 100644 pages/projects/project2.js
 create mode 100644 pages/projects/project2.json
 create mode 100644 pages/projects/project2.wxml
 create mode 100644 pages/projects/project2.wxss
 create mode 100644 pages/projects/project3.js
 create mode 100644 pages/projects/project3.json
 create mode 100644 pages/projects/project3.wxml
 create mode 100644 pages/projects/project3.wxss
 create mode 100644 pages/projects/project4.js
 create mode 100644 pages/projects/project4.json
 create mode 100644 pages/projects/project4.wxml
 create mode 100644 pages/projects/project4.wxss
 create mode 100644 pages/user/login.js
 create mode 100644 pages/user/login.json
 create mode 100644 pages/user/login.wxml
 create mode 100644 pages/user/login.wxss
 create mode 100644 pages/user/register.js
 create mode 100644 pages/user/register.json
 create mode 100644 pages/user/register.wxml
 create mode 100644 pages/user/register.wxss
 create mode 100644 project.config.json
 create mode 100644 project.private.config.json
 create mode 100644 utils/util.js

$ git remote add health https://github.com/zgp20010421/Health_project.git

$ git push -u health dev

Enumerating objects: 116, done.
Counting objects: 100% (116/116), done.
Delta compression using up to 12 threads
Compressing objects: 100% (102/102), done.
Writing objects: 100% (116/116), 889.83 KiB | 18.54 MiB/s, done.
Total 116 (delta 12), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (12/12), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/zgp20010421/Health_project/pull/new/dev
remote:
To https://github.com/zgp20010421/Health_project.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'health/dev'.


