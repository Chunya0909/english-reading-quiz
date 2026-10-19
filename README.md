# English Reading Quiz Site｜英語閱讀互動學習網

這是為國中八年級設計的英文閱讀理解互動練習網站。每課分為 **Dialogue（對話）** 與 **Reading（閱讀）** 兩份教材，練習直接提取、推論、整合、批判思考與生活連結。

## 網站入口

**[開啟課程總首頁](https://chunya0909.github.io/english-reading-quiz/)**

## 課程一覽

| 單元 | 主題 | Dialogue | Reading |
|---|---|---|---|
| Unit 1 | Summer Vacation | [對話練習](https://chunya0909.github.io/english-reading-quiz/unit1/dialogue/) | [閱讀練習](https://chunya0909.github.io/english-reading-quiz/unit1/reading/) |
| Unit 2 | School Clubs | [對話練習](https://chunya0909.github.io/english-reading-quiz/unit2/dialogue/) | [閱讀練習](https://chunya0909.github.io/english-reading-quiz/unit2/reading/) |
| Unit 3 | Mystery & Dreams | [對話練習](https://chunya0909.github.io/english-reading-quiz/unit3/dialogue/) | [閱讀練習](https://chunya0909.github.io/english-reading-quiz/unit3/reading/) |
| Unit 4 | Dreams & Future Careers | [對話練習](https://chunya0909.github.io/english-reading-quiz/unit4/dialogue/) | [閱讀練習](https://chunya0909.github.io/english-reading-quiz/unit4/reading/) |
| Unit 5 | London Travel | [對話練習](https://chunya0909.github.io/english-reading-quiz/unit5/dialogue/) | [閱讀練習](https://chunya0909.github.io/english-reading-quiz/unit5/reading/) |
| Unit 6 | Christmas Shopping & Fast Fashion | [對話練習](https://chunya0909.github.io/english-reading-quiz/unit6/dialogue/) | [閱讀練習](https://chunya0909.github.io/english-reading-quiz/unit6/reading/) |

> 上列連結依照專案的預期資料夾結構編排。若個別單元尚未部署完成，請先確認對應的 `index.html` 已上傳。

## 練習特色

- PIRLS 四層次閱讀理解：直接提取、直接推論、詮釋整合、比較評估。
- 選擇題提供即時答題回饋、提示與閱讀證據。
- 開放式題目鼓勵批判思考與個人生活連結。
- 各單元使用不同的主題配色，適合課堂與自主練習。

## 網站檔案結構

```text
english-reading-quiz/
├── index.html                # 全站總首頁
├── README.md                 # 本說明文件
├── unit1/
│   ├── dialogue/index.html
│   └── reading/index.html
├── unit2/
│   ├── dialogue/index.html
│   └── reading/index.html
├── unit3/
│   ├── dialogue/index.html
│   └── reading/index.html
├── unit4/
│   ├── dialogue/index.html
│   └── reading/index.html
├── unit5/
│   ├── dialogue/index.html
│   └── reading/index.html
└── unit6/
    ├── dialogue/index.html
    └── reading/index.html
```

## 新增課程的方法

1. 在儲存庫建立 `unit7/dialogue/index.html` 與 `unit7/reading/index.html`（以 Unit 7 為例）。
2. 修改**最外層** `index.html`，新增 Unit 7 的課程卡片與兩個連結。
3. 更新本 `README.md` 的課程表與檔案結構。
4. 在 GitHub 提交（Commit changes），等待 GitHub Pages 部署完成後檢查連結。

## GitHub Pages 部署

在 GitHub 儲存庫的 **Settings → Pages** 中，選擇 **Deploy from a branch**，分支為 `main`、資料夾為 `/ (root)`。

本網站用於英語閱讀教學與練習。
