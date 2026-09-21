# listening-agent — 輿情監控專員（Agent 版）

claude.ai/code 選這個 repo（或本機 `claude`）→ 說「這週的評論在 inbox，幫我判讀」→ 判讀表、嚴重負評告警稿、每則回覆草稿、給行銷經理的週報、待釐清、可轉發好評寫到 `outbox/` → 看完說「好，發下去」。

公司、人物、評論皆虛構。**demo 完歸零**：`inbox/*.done` 改回 `.txt`、清 `outbox/`、`data/輿情池.csv` 換回 `data/輿情池_原始.csv`、log 只留表頭。
