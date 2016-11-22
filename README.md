This is my conky configuration inspired from BunsenLabs Linux conky

<center>
<img src="https://github.com/farazaulia/conkyrc/blob/master/conky.png">
</center>

# Features
* Sysinfo
* CPU info
* Memory info
* File System info
* Shortcut Keys

# Installations

#### 1. Install conky

```bash
sudo apt-get install conky
```

#### 2. Clone this repo

```bash
sudo git clone https://github.com/farazaulia/conkyrc.git ~/.conky
```

#### 3. Create link

```bash
sudo ln -S ~/.conky/conkyrc ~/.conkyrc
```
#### 4. Set conky to run on startup

```bash
sudo chmod +x ~/.conky/startup.sh
sudo mv ~/.conky/startup.sh /home/
```

