# Rickroll Plymouth Theme 
---

## 📸 Preview
---
<div class="tenor-gif-embed" data-postid="19905507" data-share-method="host" data-aspect-ratio="1.25" data-width="100%">
  <a href="https://tenor.com/view/rick-gif-19905507">Rick Sticker</a>from <a href="https://tenor.com/search/rick-stickers">Rick Stickers</a>
</div> 
<script type="text/javascript" async src="https://tenor.com/embed.js"></script>
<!-- Yeah it looks like that bitch --!>

## 📦 Installation

### 1. Clone this repo
```
git clone https://github.com/b0mbaclat/rickroll-plymouth.git
cd rickroll-plymouth
```

### 2. Copy theme into Plymouth directory
```
sudo cp -r rickroll /usr/share/plymouth/themes/
```


### 3. Set the theme
```
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/rickroll/rickroll.plymouth 100
sudo update-alternatives --config default.plymouth
```

Select **rick-roll** from the list.

### 4. Update initramfs
```
sudo update-initramfs -u
```


### 5. Reboot
