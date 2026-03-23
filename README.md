# Final_Project
Power BI Data Analytics Project: 深入分析 2007-2026 台灣潔淨能源佔比趨勢與自用發電設備之崛起。涵蓋從原始寬表 ETL 轉換至 DAX 建模與視覺化之全流程。

🚀 專案概述 (Project Overview)
本專案聚焦於台灣能源轉型的關鍵數據，透過 Power BI 分析過去近 20 年間能源結構的質變。重點探討「潔淨能源（再生能源 + 核能）」的佔比變化，以及「自用發電設備」在分散式電力系統中的成長趨勢。

🛠️ 技術棧 (Tech Stack)
數據處理： Power Query (M Language) - 執行 Unpivot 長表轉換、雜訊處理 (Trim & Filter)。

數據建模： Power BI Desktop - 建立維度模型、定義 [是否潔淨] 邏輯門檻。

分析邏輯： DAX (Data Analysis Expressions) - 計算各年度發電佔比與複合成長率。

視覺化： Stacked Area Chart (趨勢面積圖)、核帳矩陣 (Validation Matrix)。

🔍 核心分析邏輯 (Key Logic)
ETL 清洗： 排除「全國」重複加總欄位，處理「(數值)」等非結構化雜訊。

分類定義： * 潔淨能源： 再生能源 + 核能。

儲能/調度： 將「抽蓄水力」獨立標註，避免誤導發電佔比。

維度細分： 依 [經營主體]、[能源大類]、[能源細項] 進行多層次鑽取分析。

📈 預期洞察 (Expected Insights)
能源轉型轉折點： 觀察潔淨能源佔比在不同政策階段的成長斜率。

能源自主化： 分析自用發電設備（如企業太陽能、綠能設施）如何影響傳統電網結構。

趨勢預測： 透過 2007-2026 的長週期數據，視覺化台灣邁向淨零排放的實際進展。
