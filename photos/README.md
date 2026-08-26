# Custom element artwork

Drop hand-made images for elements here, then register them in `LOCAL_PHOTOS`
inside `index.html`:

```js
const LOCAL_PHOTOS = {
  86: "photos/rn.jpg",   // Radon
  104: "photos/rf.jpg",  // Rutherfordium
};
```

- Key = atomic number, value = file path relative to `index.html`.
- Local artwork takes priority over Wikipedia photos; if the file fails to
  load, the app automatically falls back to Wikipedia.
- Suggested specs: roughly square, ~640px or larger, JPG or PNG, dark
  background fits the theme best.

Elements that currently have **no Wikipedia photo** (perfect candidates):

72 Hf · 86 Rn · 87 Fr · 96 Cm · 100 Fm · 101 Md · 102 No · 103 Lr ·
104 Rf · 105 Db · 106 Sg · 107 Bh · 108 Hs · 109 Mt · 110 Ds · 111 Rg ·
112 Cn · 113 Nh · 114 Fl · 115 Mc · 116 Lv · 117 Ts · 118 Og
