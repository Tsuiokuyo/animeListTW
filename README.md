# 純前端的動畫排名網頁 (https://yuriever.com/animeListTW)

簡單描述一下用到的東西  


網頁之源，沒有這個就沒有後續  
https://github.com/manami-project/anime-offline-database/  
輔助資料  
https://github.com/bangumi/Archive  
https://github.com/kawaiioverflow/arm  
https://github.com/Fribb/anime-lists  
https://github.com/varoOP/shinkrodb  


基於上述資料進行ID映射  
https://github.com/soruly/burstlink  

將映射表放入此專案的主邏輯，實際上我也是看到這個才打算寫一個前端  
https://github.com/LovEveRv/anime-rating-db  
當然，都還是需要自行修改才能使用  

搭配工具  
https://github.com/jikan-me/jikan-rest   
https://github.com/AniList/ApiV2-GraphQL-Docs  
https://github.com/bangumi/api  
https://github.com/bangumi/Archive  
https://github.com/trakt/api-help    
https://wiki.anidb.net/HTTP_API_Definition  
https://www.animenewsnetwork.com/encyclopedia/api.php  
https://developers.annict.com/docs/rest-api/v1  
https://fanarttv.docs.apiary.io/  
https://kitsu.docs.apiary.io/#  
https://notify.moe/api  

輸出結果  
https://yuriever.com/animeListTW  

非必要工具  
https://github.com/Waifu-pics/waifu-api  
https://soruly.github.io/trace.moe-api/#/  
https://github.com/101arrowz/fzstd  



實際上這個倉庫我是打算用來撈RSS，用來解決純前端網頁CORS的問題  
透過github actions撈取rss後轉成json檔存進倉庫來讀取  
https://docs.github.com/zh/actions  
