# git常用命令
> Create by sandy on 2019-06-14 15:21:07            
> Recently revised in 2019-06-14 15:21:17    
   
## 1.常用指令
| 指令 | 含义 |   
| :---: | :---: |   
| git init | 初始化 |   
| git add README.md | 添加某一个文件 | 
| git add . | 添加所有文件 |
| git commit -m "first commit" | 提交文件,并给出提交内容的描述 |
| git remote add origin [url] | 设置仓库的别名为origin, 这里"url"用自己仓库的url|
| git push origin master | 提交到仓库主分支 |
| git remote rm origin | 删除远程仓库别名origin |

## 2.git给远程库添加多个地址
* 增加第一个地址: `git remote add origin <url1>`
* 然后增加第二个地址: `git remote set-url --add origin <url2>`
* 增加第三个地址: `git remote set-url --add origin <url3>`
