Azure 檔案同步代理程式的更新會定期發行，以新增功能並解決任何找到的問題。 建議啟用 Microsoft Update，以取得我們所發行的所有 Azure 檔案同步代理程式更新。 話雖如此，我們了解某些組織會想要嚴格控制並測試更新。 若要使用舊版 Azure 檔案同步代理程式進行部署：

- 在最初發行新的主要版本之後三個月，儲存體同步服務會允許使用舊的主要版本。 例如，在發行版本 2.\* 之後三個月，儲存體同步服務會支援版本 1.\*。
- 過了三個月後，儲存體同步服務會透過與其同步群組同步，開始封鎖使用過期版本的已註冊伺服器。
- 在使用舊的主要版本的三個月內，所有 Bug 修正只會套用至目前的主要版本。

> [!Note]  
> 如果您使用的 Azure 檔案同步版本將在三個月內過期，我們會透過 Azure 入口網站中的快顯通知來通知您。