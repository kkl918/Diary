# md 換行
句尾兩個空格=換行

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
4. cancel login of root<br /> 
   sudo vim /etc/ssh/sshd_config <br /> 
     (1)#PermitRootLogin Yes <br /> 
     (2)Port 1137 -> optional 
5. /etc/hosts.allow sshd:192.168.1.88:allow -> optional<br /> 
   /etc/hosts.deny  sshd:all:deny -> optional
6. sudo /etc/init.d/ssh restart
Read more: http://www.arthurtoday.com/2010/08/ubuntu-ssh.html#ixzz4qXJ3wKDV

# GIT
1. sudo apt install git
2. git config --global user.name "Your Name"
3. git config --global user.email "youremail@domain.com"

# vim .vimrc
set nu  
set ai  
set tabstop=4  
set shiftwidth=4  
inoremap ( ()<Esc>i  
inoremap " ""<Esc>i  
inoremap ' ''<Esc>i  
inoremap [ []<Esc>i  
inoremap { {}<Esc>i  
inoremap {<CR> {<CR>}<Esc>ko  
inoremap {{ {}<ESC>i  
filetype indent on  

# notepad tab makes python error
Chinese UI : 設定 -> 使用者設定 -> 程式語言 -> 打勾"以空格取代"  
Englisg UI : setting -> pregerences -> language -> mark "replace by space"  
