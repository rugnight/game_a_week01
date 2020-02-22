Welcome to the game_a_week01 wiki!


## gitconfig設定

```
git config --global core.autoCRLF false
```

## net.rugnight.rc サブモジュール設定

```
mkdir Submodules
cd Submodules
git submodule add git@github.com:rugnight/net.rugnight.git
git add .
git commit -m "submodule追加"
git push
```

```.json
{
  "dependencies": {
    "net.rugnight.rc": "file:../Submodules/net.rugnight/Assets/Rc",
    "com.unity.2d.sprite": "1.0.0",
    "com.unity.2d.tilemap": "1.0.0",
```
