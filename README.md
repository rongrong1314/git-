### 首次提交：  
>>>git init  
>>>git add .  
>>>git commit -m 'name'  
>>>git remote add origin + net  
>>>git stash 如果同步出错先执行该语句   
>>>git pull --rebase origin master  同步  
>>>git push -u origin master  
### 更新提交：
>>>git status  
>>>git add .  
>>>git status  
>>>git commit -m 'name'  
>>>git push -u origin master  
### readme添加图片：
>>>输入images/创建文件夹以及文件  
>>>点击Upload files导入图片  
>>>复制图片路径  
>>>在相应文件夹下生成README.md  
>>>在README中输入“!+[image]+(路径)”  
### 错误使用https：
>>>git remote -v  
>>>git remote rm origin  
>>>git remote add origin + ssh  
>>>git push origin master  
### git 错误导致文件删除  
>>>git rebase --abort  
