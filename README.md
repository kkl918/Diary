# Setting

jyputer設定主題:  

(1)pip install --upgrade jupyterthemes

(2)jt -l (查看所有主題名稱)

(3)jt -t chesterish (設定成黑色主題)

# Win 10 快速開啟PowerShell
-> shift + 右鍵 <-

# SSH in Ubuntu 
1. sudo apt-get install openssh-server
2. sudo service ssh status
3. sudo nano /etc/ssh/sshd_config
4. 消 root 的登入權限

這是基於安全的考量， 一般都不會設定讓 root 可以連進來， 不然，駭客就會很方便的哩 ！ 首先，打開在 /etc/ssh/sshd_config 的 SSH 設定檔，然後，找到下面這一行，把它的 yes 改成 no 之後，就把它存檔起來。＃PermitRootLogin Yes 

Read more: http://www.arthurtoday.com/2010/08/ubuntu-ssh.html#ixzz4qXJ3wKDV
