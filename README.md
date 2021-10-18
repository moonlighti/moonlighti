关于GitHub的ssh登录二次回忆。



### ...或在命令行上创建一个新的存储库

echo "#moonlighti" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M main 
git remote add origin git@github.com:moonlighti/moonlighti.git
 git push - u 原产地主要



### ...或从命令行推送现有存储库

git remote add origin git@github.com:moonlighti/moonlighti.git
 git branch -M main 
git push -u origin main