# [BanG_TeaM](http://telegram.me/BanG_TeaM)

# برای نصب کد زیر را در ترمینال وارد کنید
```
git clone http://github/sudoattacker/Sudoattacker021.git && cd sudoattacker021 && chmod +x launch.sh && ./launch.sh install
```

#سپس
```
cd tg && git clone http://github.com/Mohammadrezar/fix && cp fix/lua-tg.c lua-tg.c && make && cd .. && ./launch.sh

```
# سپس شماره خود را با کد کشور مورد نظر وارد کنید


# >> آموزش فعال سازی اتولانچ
# کدهای زیر را بترتیب وارد کنید
```
cd Sudoattacker021 && sed -i "s/root/$(whoami)/g" etc/pika.conf; sed -i "s_telegrambotpath_$(pwd)_g" etc/pika.conf && sudo cp etc/pika.conf /etc/init/ && chmod 777 pika && nohup ./pika &>/dev/null &
```
```
sudo start pika
```
```
screen ./pika
```
# در صورت خاموش شدن ربات برای لانچ
```
cd Sudoattacker021

screen ./pika
```

# >> آموزش زدن لانچر
# بترتیب
```
cd Sudoattacker021

tmux new-session -s script "bash steady.sh -t"
```
# درصورت خاموش شدن برای لانچ
```
cd Sudoattacker021

killall tmux

tmux new-session -s script "bash steady.sh -t"
```
# برای یوزرغیر روت لانچر توصیه میشه 

# آموزش های بیشتر در کانال ما

# برای ورود به کانال کلیک کن

# [ورود به کانال](http://telegram.me/BanG_Team)
# [کانال دوم] (http://telegram.me/BanG_TeaM_VpS)
# [@Biraqam](http://telegram.me/Biraqam) 
