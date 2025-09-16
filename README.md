# assistant-project

echo "# assistant-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:u-orda/assistant-project.git
git push -u origin main
Есть 4 состояния в GIT: tracable, untracable, staged, modified
 
Основной идентификатор коммита — это его хеш
Таблица соответствия хеш → информация о коммите хранится в папке .git.
Git хранит всю свою служебную информацию в этой папке, в том числе и таблицу, в которой можно найти коммит по хешу


