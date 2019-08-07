# Tumult Hype Pro

## 製作補間動畫

按照以下步驟創建一個移動3秒鐘的元素動畫：

1. Click the Record button to turn on recording
2. 單擊 `Record` 按鈕開啟錄製
   
   ![printscreen](/images/7.png)

3. 選擇要設置動畫的元素
4. 將時間光標向右移動並停在3秒刻度標記處
5. 將元素拖到新位置，或調整元素大小。



## 設定 Document 透明背景

在 `Document` 面板中，勾選 `Make background transparent` 設定：

![printscreen](/images/2.png)



## 符合 RWD

在 `Scene` 面板中，點擊 `Add New Layout...`，新增 Responsive Layout：

![printscreen](/images/4.png)

> [Demo](./src/rwd/rwd.html)
>
> tumult-hype-3-exercise/src/rwd



## 調整 Breakpoint

**step 1**：在左側面板中，選擇想要調整的 Layout

![printscreen](/images/5.png)

**step 2**：在 `Scene` 面板中，調整的 Breakpoint 的數值：

![printscreen](/images/6.png)



## 符合 Full Screen

在 `Scene` 面板中，勾選 `scale` 設定：

![printscreen](/images/3.png)

> [Demo](./src/fullscreen/fullscreen.html)
> 
> tumult-hype-3-exercise/src/fullscreen



## 匯出檔案

- **HYPE-###.full.min.js** — Tumult Hype 運行時主要的文檔。包含整個運行時，包括 IE6-8 所需的 JavaScript，以達到兼容性。

- **HYPE-###.thin.min.js** — 現代瀏覽器使用的 Tumult Hype 運行時主要的文檔。

- **HYPE-###.waypoints.min.js** — 使用 Viewport 操作時包含的文檔。

- **documentName_hype_generated_script.js** — 特定於文檔的數據，用於定義文檔的所有場景，時間軸，元素和動畫。

- **PIE.htc** — Internet Explorer 的 HTML 組件，用於在 Internet Explorer 6 到 8 中，提高瀏覽器的兼容性。 有關詳細信息，請參閱 [css3pie.com](http://css3pie.com/)。

- **poster.jpg / png / gif** - Hype 中捕獲的可 optional poster image。 查看 [poster image](https://tumult.com/hype/documentation/#poster-images)以獲取更多信息。

- **blank.gif** — 一個特殊的圖像，可以改進Internet Explorer 6 到 8中的透明 GIF 渲染。

- **cache.manifest** — 列舉文檔的資源以進行離線緩存。僅在 `Document inspector` 面板中啟用 `Create Offline Application Cache` 選項時才會出現。

    ![Document inspector](/images/1.png)

- **####-restorable.plist** — 文檔恢復文件，可用於從導出的內容中恢復原始的 Hype 文檔。有關恢復的詳細信息，請參閱[Document Recovery](https://tumult.com/hype/documentation/#document-recovery) 部分。




## Resource

- [The Tumult Youtube channel](https://www.youtube.com/user/TumultHype/videos)

- [Tutorials 官方教學影片](https://tumult.com/hype/tutorials/)

- [Tumult Hype Documentation 說明文件](https://tumult.com/hype/documentation/)