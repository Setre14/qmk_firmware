```
python3 -m pip install --user qmk
qmk setup
qmk config user.keyboard=splitkb/kyria
qmk config user.keymap=setre14
```

```
cd keyboards/splitkb/kyria/keymaps/setre14
qmk c2json -kb splitkb/kyria -km setre14 -o keymap.json keymap.c 
```
