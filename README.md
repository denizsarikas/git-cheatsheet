# git-cheatsheet


touch git-basics.txt
-
code git-basics.txt
-
git init
-
git status //hangi branchteyim
-
git add [dosya] //dosyayı commit icin ekledim
-
git commit -m "Yeni bir dosya eklendi" // git statusten takip edildiğini bildiğimşeyleri ekleyebiliyorum
-
git log // commit history gibi
-
git add * // hepsini commit icin ekle
-
git checkout [commit numarası] | [branch] // belirli bi noktaya gecmek icin
-
git diff // değişiklikleri kismen daha detayli gormek
-
git diff --cached // stage ettiğim değişiklikleri son commitle karşılaştır
-
git commit -a -m "git add demeden bir seyler ekledim"  //add demeden direkt commit etmek
-
git checkout -b Denemelerim //Denemelerim isimli bir branch oluşturup geçmek
-
git log --oneline --graph --decorate
-
git checkout master + git merge Denemelerim //merge
-
git branch -d // silmek
-
git config --global alias.lagd "log --oneline --all --graph --decorate" //git lagd dediğimde alias olarak o kodu calistir //local user gibi secenekler var
-
git config --show-origin alias.lagd //aliasin hangi komut olduğunu gör
-
git config --get core.filemode // değeri görmek js obje gibi //localde bulamazsa globalde buldugunu gosterir
-
git config --show-origin --list // her seyi getiriyuor ve nerede oldugunu gosteriyor (global local)
-
less cat veya vimle falan acabiliriz// less /Users/deniz/.gitconfig
-
git config --unset [silmek istediğin şey  dosyaya girmeden] //oncelikle localdekini siliyor aynı değer oldugu zaman --global diye belirtmediğin surece 
-
checkout, reset, revert 

