| # | Server | Location | protocol |ws+tls| type | Remark | Bandwidth/Quota|
|---|----------|-------------|--------|-----|-----|---------|---|
|1.1|[WannaShabuShabu](ss://eGNoYWNoYTIwLWlldGYtcG9seTEzMDU6U2xlZXB5X1MwcnJyeQ@jp.chiioi.eu.org:443/?plugin=v2ray-plugin%3btls%3bhost%3djp.chiioi.eu.org%3bpath%3d%2fv2ray)| Tokyo, JP | ss | ✓| direct|Microsoft Azure|50Mbps/15GB|
|2.1|SecretGardenGRP| Singapore, SG | ss|✓|CDN/Cloudflare/Planning to Rebuild CDN in Shanghai|DigitalOcean/Recommended(Special Days)|INF/1.5TB|
|2.2|[SecretGarden](ss://eGNoYWNoYTIwLWlldGYtcG9seTEzMDU6U2xlZWd5X1MwcnJyeQ@sg.chiioi.me:443/?plugin=v2ray-plugin%3btls%3bhost%3dsg.chiioi.me%3bpath%3d%2fgarden)| Singapore, SG |  vmess| ✓| direct|Recommended |INF/1.5TB|
|3.1|[SleepyLoMei](ss://eGNoYWNoYTIwLWlldGYtcG9seTEzMDU6U2ZlZXB5X1MwcnJyeQ@us.chiioi.eu.org:443/?plugin=v2ray-plugin%3btls%3bhost%3dus.chiioi.eu.org%3bpath%3d%2flm)| San Francisco, US  | ss| ✓  |direct| DigitalOcean/Share Quota with SecretGarden|INF/1.5TB|
|3.2|SleepyLoMeiRP| San Francisco, US  | vmess |✓| CDN/Cloudflare||INF/1.5TB|
|4.3|MickeyMouse| Sydney, AU  | trojan  ||  direct|Backup/DigitalOcean/Share Quota with SecretGarden/***使用trojan協議請注意自身數據安全***|INF/1.5TB|
|0.0|DryMincedBeef| Macau, CN  | ||Cloudflare|Mtel/Only For Test/ss/v2/trojan||

Clash格式的配置文件（二選一即可）
主文件:  https://config.chiioi.me/magicbox.yaml (Github/Cloudflare CDN)
鏡像(鏡粉唔好打禾qq): https://conf2.chiioi.me (JPEast/Cloudflare CDN)
廢置: <strike>https://jp.chiioi.eu.org/magicbox.yaml</strike>  (JPEast/direct)

---
Windows:
你可以選擇以下任一客戶端進行連接
- 使用Shadowsocks配合v2ray-plugin連接上表中的Server x.1
- 使用V2Ray core配合V2RayN或Qv2ray介面連接上表中的Server x.2
	*Qv2ray配合各QvPlugin可以連接上表的任一Server*
- 使用Trojan-Qt5連接上表中的Server x.3
- 使用Clash連接上表的任一Server（這個很麻煩我也不會用）
---
Mac OS:
你可以選擇以下任一客戶端進行連接
- 使用V2Ray core配合Qv2ray介面連接上表中的Server x.2
	*Qv2ray配合各QvPlugin可以連接上表的任一Server*
- 使用ClashX連接上表的任一Server
---
Android:
你可以選擇以下任一客戶端進行連接
- 使用Shadowsocks配合v2ray-plugin連接上表中的Server x.1
- 使用V2rayNG連接上表中的Server x.2/x.3
- 使用Clash for Android連接上表的任一Server（強推Android端貓貓client）
---
iOS:
你可以選擇以下任一客戶端進行連接
- 使用Shadowrocket連接上表的任一Server
---
