# ![image](https://github.com/user-attachments/assets/68be11aa-30c5-46c3-a658-77cc419a8612)

# FORTYTWO

# ÖNCE SUNUCUMUZU HAZIRLAYALIM
```
sudo apt update
sudo apt install screen
```
```
sudo apt update
sudo apt install unzip
```

# KURULUMUMUZA BAŞLIYORUZ
```
mkdir -p ~/Fortytwo && cd ~/Fortytwo
```
```
curl -L -o fortytwo-console-app.zip https://github.com/Fortytwo-Network/fortytwo-console-app/archive/refs/heads/main.zip
unzip fortytwo-console-app.zip
```
SCREEN AÇALIM
```
screen -S fortytwo
```
```
cd fortytwo-console-app-main
chmod +x linux.sh && ./linux.sh
```
### Burada size bir soru soracak. 
```
İlk defa kuracaksanız 1 i seçin. Arkasında size davet kodunuzu soracak. onu girdikten sonra size cüzdan adresinizi ve mnemoniclerini verecek. KAYDETMEYİ UNUTMAYIN !!!
Eğer daha önce kurduğunuz nodunuzu kaydetmek istiyorsanız 2 yi seçin. Size anımsatıcılarınız soracak. Onu girince cüzdanınızı import etmiş olacaksınız.
```
### Yüklemeyi bitirince size tekrar bir soru soracak
```
Hangi modeli çalıştırmak istediğinizi soracak. Dilediğiniz birini seçin. Herhangi bir fikriniz yoksa 0'ı seçebilirsiniz
```
# Artık loglarınız akmaya başlayacak
# Explorerdan cüzdan adresinizle nodunuzu kontrol edebilirsiniz.
https://testnet.monadexplorer.com/address/



