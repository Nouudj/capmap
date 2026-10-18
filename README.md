# CapMap

Kostenloser Video-Editor für Windows, aufgebaut wie CapCut.

Hier liegen die Updates der Desktop-App. CapMap schaut beim Start in `update.json`, ob es eine neue Version gibt, lädt sie aus `updates/` und installiert sie nach einer Rückfrage.

**Bitte `update.json` nicht von Hand ändern** – sonst bekommen alle installierten Apps ein falsches Update angezeigt. Ohne passenden Prüfwert (`sha256`) wird ein Update nie installiert.
