# Panjara yo'llari

Kombinatorika uchun vizualizatsiya: koordinata panjarasida A nuqtadan B nuqtaga
faqat o'ngga (→) va yuqoriga (↑) yurib nechta usulda borish mumkinligini ko'rsatadi.

**Ishga tushirish:** `index.html` faylini brauzerda oching (server yoki o'rnatish shart emas).

## Imkoniyatlar

- **Harakat rejimi**: «Faqat → va ↑» (B nuqta A dan chapda/pastda bo'lsa — 0 yo'l) yoki «B tomonga».
- A va B nuqtalarni panjarani bosib yoki koordinatalarni kiritib tanlash (istalgan yo'nalishda).
- Har bir tugunda A dan shu tugungacha bo'lgan yo'llar soni (chapdagi + pastdagi qoidasi).
- Formula bosqichma-bosqich: `C(n+m, n) = (n+m)! / (n!·m!)`.
- **Orqali o'tadigan nuqta** P: `(A→P) · (P→B)` ko'paytma qoidasi.
- **Kirish mumkin bo'lmagan nuqtalar**: panjarani bosib yoki koordinata kiritib belgilash; bitta nuqta bo'lsa `C(n+m,n) − (A→X)·(X→B)` ko'rsatiladi, ko'p bo'lsa dinamik hisoblanadi.
- Yo'llarni bittalab ko'rish (◀ ▶), tasodifiy yo'l va barcha yo'llarni ketma-ket animatsiya.
- Issiqlik xaritasi: har bir tugundan qancha yo'l o'tadi.
- Paskal uchburchagi bilan bog'liqlik: `n+m`-qatorning `n`-elementi.
