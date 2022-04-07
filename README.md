# GitHelloCh3
練習上傳

### 練習上傳用

- 指令
```
git remote add origin https://github.com/lolmuta/GitHelloCh3.git
git branch -M main	
git push -u origin main
```
- 在下這個指令時，可能會出錯
```
git push -u origin main
```
> remote: Permission to lolmuta/GitHelloCh3.git denied to chigaYi.
fatal: unable to access 'https://github.com/lolmuta/GitHelloCh3.git/': The requested URL returned error: 403


- 解法
  - 到下面的地方，找到github 並將之刪除後，重新在下1次指令，這樣git會觸發認證機制，就可以上傳成功
![image](https://user-images.githubusercontent.com/19727471/162150736-bf6db287-0f34-4615-ae2d-dd9eb9a9f3d4.png)
