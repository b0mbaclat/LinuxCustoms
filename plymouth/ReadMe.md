# Rickroll Plymouth Theme 
---

## 📸 Preview
---
<img width="498" height="398" alt="image" src="https://github.com/user-attachments/assets/c706bde3-e92d-4b55-afe1-ef22594c4d0c" />
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
