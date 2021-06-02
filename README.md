./git config --global user.email 838680559@qq.com
git config --global user.name "isfannojinfan"
git config --global url."https://github.com.cnpmjs.org/".insteadOf "https://github.com/"
git checkout -b develop
git branch -a
git add .
git commit -m "finished markdown"
git checkout main
git merge develop
git push origin main
