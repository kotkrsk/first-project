/// Установить настройку
git config --global user.name "User Namovich" 
git config --global user.email username@yandex.ru
///
Показать конфиги
cat ~/.gitconfig 
git config --list 
///
/////Begin
cd first-project/
git init
git status

touch файлики
git add --all // добавить все файлики в реп
git add . # добавить всю текущую папку


cat ~/.ssh/id_ed25519.pub //добавить в github
ssh -T git@github.com //test github

git remote add origin git@github.com:kotkrsk/first-project.git //связать репозитории
git remote -v
