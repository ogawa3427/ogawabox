### README (取扱説明書?)
#### ogawabox  

This package helps you flee from typing too long cord to set up new emvironent.  

このパッケージはいちいち新しい環境ごとにツールをインストールする手間を削減、
具体的にはネットからコピペできない環境で
長いコマンドを手打ちする苦行からあなたを解放できるようにするものです。  

This pack is developing for now.  
このパッケージは発展途上であります  

各環境にローカライズしてお使いください。  
Please fix some files to run correctoly at your enviroment.  

***
## Caution　注意  

You can get **NO WARRANTY**  
because this package is being developped ONLY to earn my skils to write shellskripts.  
このパッケージに**保証はありませんので自己責任**での利用をお願いいたします。  
私のShell使いとしての能力を得るために作っているものです

If you cannot take responsiblity for your attempt,  
or if you cannot talk wheather ogawabox is hurmful or not  
please refrain from using ogawabox.  
このパッケージを使用したことで発生するかもしれないあらゆる  
(司法レベルでの常識は別にして)不利益について責任を取れない方、  
または含まれるスクリプトが有害であるか否かを判断できない方は  
このパッケージの使用を控えてください  
***

### How to install インストール方法

#### step0  
gitを使える(技術的に/信念的に) ⇒ Step1A  

gitは嫌だ ⇒ Step1B  

gitってなにか知らない && 管理者がgit cloneを許可している ⇒ Step1C  

#### Step1A  
コマンドラインに
```git clone https://github.com/Ogawa949698/ogawabox.git```  
2へ  

#### Step1B  
```wget``` (準備中)  
```unzip``` (準備中)  
```cd ~/ogawabox```  
```chmod +x getstarted.sh```  
2へ  

#### Step1C    
コマンドラインに  
``` sudo apt update```   
```sudo apt upgrade```  
```sudo apt install git```  
成功したら  
```git clone https://github.com/Ogawa949698/ogawabox.git```  
2へ  

#### Step2
```./getstarted.sh```  

---

### 内容物 products  
ogawabox  
|-meta  
||-aup.sh releasenote.txtへの追記とgithubにogawabox/の全ファイルpushを対話形式で支援します  
||        This adds text to releasenote.txt  
||        and pushes all files in ogawabox/ to github   automaticaly using a dialogue.  
||-releasenote.txt バージョン番号、日時、要約、詳細が記録されています  
|                 Ver.No, date, summary, article will be given.  
|-aboutwsl.txt wslでUbuntuを導入する際のおぼえ書き  
               Tips to install Ubuntu in wsl  
|-prepkotoriman.sh コマンドひとつで install kotoriotoko* by ONE command  
|-rmbox.sh OgawaboXをまるごとバージョンアップしたい時にだけ使うデータはすべて消える  
| To prepare replacing an old ogawabox without your data  
|         