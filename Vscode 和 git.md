# Vscode 和 git

## 1.设置不上传文件夹

> 创建.gitignore
>
> 复制不上传文件夹的相对路径，粘贴至文件，并将所有的\更换为/，在开头添加/

 ## 2.问题

> **No configured push destination.**
>
> > git remote add origin https:*//github.com/xxxxx/xxxxx.git* 
> >
> > git push -u origin master

---

> src refspec master does not match any
>
> 

---

> OpenSSL SSL_read: Connection was reset, errno 10054
>
> > git config --global http.sslVerify "false"

> Failed to connect to github.com port 443: Timed out
>
> > 关闭代理

## 3. 流程

更改--暂存--提交暂存--推送

