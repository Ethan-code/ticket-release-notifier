# ticket-release-notifier
起因：因為在搶票時並沒有如願搶到票券，只能碰運氣撿不定時清票釋出的票券，但不希望一直人工檢查票券網站是否釋出票券。

目標：透過這個程式自動檢驗訂票網站，定期使用爬蟲檢驗訂票網址，並且在清票時發出提醒通知人員進一歩去買票。

## Todo
- [ ] 找出分辨網站有票券與無票券時的條件
- [ ] 確保不會因為重複查詢被網頁阻擋
- [ ] 使用 C# 爬蟲檢查訂票頁面是否有票券釋出
- [ ] 將項目架在 Heroku 上，呼叫 API 進行通知
- [ ] 通知採用 Line Notify 機器人提醒
