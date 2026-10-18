# Potato Open Sauce Project
<img src="https://camo.githubusercontent.com/57783bb263751a394634f2ad78d566f546beb11b1e15e3ed0808cf2a63ff2bbd/68747470733a2f2f696d6775722e636f6d2f5364754431766a2e6a7067">
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
        lunch potato_device-user
        brunch device
```

# enjoy potato
