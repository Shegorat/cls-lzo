# cls-lzo

**cls-lzo** is an implementation of the **LZO** compression algorithm as a CLS filter for **FreeArc**.

Based on **LZO version 2.10** from the official source:  
http://www.oberhumer.com/opensource/lzo


---

## 📦 Parameters

| Parameter | Description |
|------------|------------|
| `b=<size>` | Block size used for compression (default: `32mb`) |
| `a=<algorithm>` | LZO algorithm variant (default: `lzo1x`) |
| `l=<level>` | Compression level (depends on the selected algorithm, default: `1`) |

---

## 🧩 Algorithms and Compression Levels

| Algorithm | Levels |
|-----------|--------|
| `lzo1`  | 1, 99 |
| `lzo1a` | 1, 99 |
| `lzo1b` | 1, 2, 3, 4, 5, 6, 7, 8, 9, 99, 999 |
| `lzo1c` | 1, 2, 3, 4, 5, 6, 7, 8, 9, 99, 999 |
| `lzo1f` | 1, 999 |
| `lzo1x` | 1, 11, 12, 15, 999 |
| `lzo1y` | 1, 999 |
| `lzo1z` | 999 |
| `lzo2a` | 999 |

---

## 🧪 Example

```cmd
-m=lzo:b16mb:a=lzo1c:l=9
```

---

## Support the Project

[![Support on Patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/Shegorat)

If you find this project useful, consider supporting development on Patreon.
