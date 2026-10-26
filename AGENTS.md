# Website 維護入口

本機作業先讀 ../PROJECT.md 與 ../AGENTS.md。

- Remote 必須是 ShawnWeng1026/travel-itineraries；此目錄才是 Git 根目錄。
- 唯一來源是 ../working/202611_福岡_V1.9.md，不直接編輯 index.html 中的 TRIP 來變更事實。
- 本機產生與驗證工具：../working/website-tooling/build.cjs、verify.cjs。
- 從最新 main 建立 feature/*，檢查後 Commit、Push、建立 PR。不要直接修改或推送 main，不自動合併／發布。
- 合併 main 後沿用 Pages main / root 發布。不要重建 repo 或重設 Pages。
- 原稿、PROJECT 與 PDF 在本機此 repo 之外；PR 附去除私人資訊的來源變更摘要，不能聲稱這些本機檔案已受此 repo 追蹤。
- 不上傳憑證、付款資料、私人座位號、token 或 references。
