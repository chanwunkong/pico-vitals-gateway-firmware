# pico-vitals-gateway-firmware

Pico Vitals Gateway 韌體發布用 repo（OTA 自動更新用，不含原始碼）。

裝置透過 GitHub Releases API 查詢最新 release 的 tag_name，並下載對應的
`pico_gateway_ota.bin` asset 寫入 flash 試跑（TBYB）。
