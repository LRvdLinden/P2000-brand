P2000 brand

Merkmateriaal van A-Alerts (a-alerts.nl).

- `banners/banner-<dienst>-apeldoorn.png`: brede banners (1200×670) voor de website en delen. Diensten: ambu, brand, pol, life, knmi, burgernet, amber, nlalert, vermistkind.
- `banners/banner-<dienst>-apeldoorn-vierkant.png`: vierkante banners (1200×1200) voor Homey en social media.
- `banners/banner-<bron>-apeldoorn-vierkant-afgerond.png`: vierkant, na afloop van Burgernet, AMBER Alert, Vermist Kind en NL-Alert.
- `banners/knmi-green-<weer>-vierkant.png`: vierkant, KNMI code groen (opgeheven) per soort weer.
- `nieuws/`: brede nieuwsbanners (1200×675) voor het tabblad Nieuws. KNMI per code en soort weer (`knmi-<code>-<weer>.png`), Burgernet, AMBER Alert, Vermist Kind en NL-Alert; `-live` met LIVEBLOG, `-afgerond` na afloop. Op de website staan ze als WebP in `website/assets/img/nieuws/` van LRvdLinden/p2000-apeldoorn.

De banners worden gemaakt met `tools/maak_nieuws_banners.js` en `tools/maak_brand_banners.js` in LRvdLinden/p2000-apeldoorn (branch `a-alerts`).
