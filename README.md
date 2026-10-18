# Potato Open Sauce Project
<img src="https://raw.githubusercontent.com/PotatoProject/manifest/frico-release/XDAThread/main.png">
Haters gonna hate, potatoes gonna potate!

# j-staging1 (Android 16)
Tastier than ever!

### Repo init ###
```bash
        repo init -u https://github.com/Alromine95/posp_manifest.git -b j-staging1
```

### Repo sync ###
```bash
        repo sync -c -j$(nproc) --force-sync --no-clone-bundle --no-tags
```

### Build ###
```bash
	. build/envsetup.sh
        lunch posp_device-user
        brunch device
```

# enjoy potato
