### Git 指令
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
