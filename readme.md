[中文](readme_CN.md)

# NOTICE: the release is used as archive. 
Please read the descriptions of settings before raising an issue.  

# Deploy to Heroku  
Official: https://heroku.com  
Demo: https://herooneindex.herokuapp.com/  

How to Install:   
> ~~Click the button [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy) to Deploy a new app~~(`"We couldn't deploy your app because the source code violates the Salesforce Acceptable Use and External-Facing Services Policy."`)  
> Fork this project, create a heroku app, then turn to Deploy tab, deploy via connect to your github fork.   


# Deploy to Glitch  
Official: https://glitch.com/  
Demo: https://onemanager.glitch.me/  

How to Install:
> New Project -> Import form Github -> paste "https://github.com/qkqpttgf/OneManager-php", after done, Show -> In a New Window.  


# Deploy to Vercel  
Official: https://vercel.com/  
Demo: null  
Notice: 
> 1, you must wait 30-50s to make sure deploy READY after change config;  
> 2, Vercel limit 100 deploy every day.  

~~How to Install:~~
#### some thing wrong  
> ~~https://scfonedrive.github.io/Vercel/Deploy.html~~ .  


# Deploy to Tencent Serverless Cloud Function (SCF)  
Official: https://cloud.tencent.com/product/scf  
DEMO:  无  
注意：SCF新增限制，环境变量整体最大4KB，所以最多添加4个盘。  

How to Install:  
> 1，进入函数服务，上方选择地区，然后点击新建。  
> 2，输入函数名称，选择模板函数，在模糊搜索中输入onedrive，大小写随意，选择那个【获取onedrive信息.....】，点下一步，在代码界面不用动，直接点完成。  
> 3，点击触发管理，创建触发器，触发方式改成API网关触发，底下勾选启用集成响应，提交。  
> 4，在触发管理中可以看到一个 访问路径，访问它，开始安装。  

（重点：勾选集成响应）  
  
添加网盘时，SCF可能会反应不过来，不跳转到微软，导致添加失败，请不要删除这个盘，再添加一次相同标签的盘就可以了。  


# Deploy to Huawei cloud Function Graph (FG)  
Only in China  

# Deploy to Aliyun Function Compute (FC)  
Only in China  

# Deploy to Baidu Cloud Function Compute (CFC)  
Only in China  

# Deploy to Virtual Private Server (VPS)  
DEMO:  null  
How to Install:  
> 1.Start web service on your server (httpd or other), make sure you can visit it.  
> 2.Make the rewrite works, the rule is in .htaccess file, make sure any query redirect to index.php.  
> 3.Upload code.  
> 4.Change the file .data/config.php can be read&write (666 is suggested).  
> 5.View the website in chrome or other.  


# Features  
When downloading files, the program produce a direct url, visitor download files from MS OFFICE via the direct url, the server expend a few bandwidth in produce.  
When uploading files, the program produce a direct url, visitor upload files to MS OFFICE via the direct url, the server expend a few bandwidth in produce.  
The XXX_path in setting is the path in Onedrive, not in url, program will find the path in Onedrive.  
LOGO ICON: put your 'favicon.ico' in the path you showed, make sure xxxxx.com/favicon.ico can be visited.   
Program will show content of 'readme.md' & 'head.md'.  
guest up path, is a folder that the guest can upload files, but can not be list (exclude admin).  
If there is 'index.html' file, program will only show the content of 'index.html', not list the files.  
Click 'EditTime' or 'Size', the list will sort by time or size, Click 'File' can resume sort.  

# Functional files  
### favicon.ico  
put it in the showing home folder of FIRST disk (maybe not root of onedrive).  
### index.html  
show content of index.html as html.  
### head.md readme.md  
it will showed at top or bottom as markdown.  
### head.omf foot.omf  
it will showed at top or bottom as html (javascript works!).  

# A cup of coffee  
https://paypal.me/qkqpttgf  

# Chat  
Telegram Group: https://t.me/joinchat/I_RVc0bqxuxlT-d0cO7ozw  
