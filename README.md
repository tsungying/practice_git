# Git 指令
* 瞭解目前已加進來的遠端儲存庫名稱。註：show 可省略
```
git remote show
```
* 加上 ```-v``` 參數，將會在名稱後方顯示其URL：
```
git remote -v
```
* 如何移除已加進來的遠端儲存庫
```
git remote remove origin
```
* 停止追蹤某檔案

先將該檔案加入.gitignore中，再執行
```
git rm --cached filename
```
* ##### push 專案到遠端倉庫存放

1. 先在想要的遠端倉庫上建立新倉庫

2. 再把代碼 push 到新倉庫的路徑
3. origin 可以用其他單字替換

Ex：git remote add origin https://github.com/tsungying/senqi.git
```
git remote add origin git@bitbucket.org:<username>/toy_app.git
```
* 第一次 push 到遠端倉庫時要記得加 ```-u```
```
git push -u origin master
```
* How to get ssh public key ?
```
cat ~/.ssh/id_rsa.pub
```
* 如何編輯最後一次的 commit 內容
```
git commit --amend
```
