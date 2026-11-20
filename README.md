# 信約錄（1894，DRS 428481349） / Xin yue lu: Transcription Dataset

《信約錄》由富善（Chauncey Goodrich，1836–1925）編寫，京都美華書局於光緒二十年（1894）刊行，共三對折葉。書中以「六信」列出六項信仰陳述，以「三約」載明立約承諾，並保留牧師與會眾問答及儀式說明，可供研究十九世紀漢語新教信條、入會盟約與術語。本資料集以哈佛燕京藏本 DRS 428481349 為底本，提供全冊 14 幅所據的 JSON、TXT、TEI 與覆核紀錄。本版為 AI 校讀稿，56 項比對中保留 8 項未解，另有一處刊記字形疑讀。人工全文二校待完成。

Xin yue lu (信約錄) is a three-bifolium tract compiled by Chauncey Goodrich (富善, 1836–1925) and printed by the Jingdu Meihua Shuju (京都美華書局) in 1894 (Guangxu 20). It sets out six articles of faith (liuxin) and three covenant vows (sanyue), and it retains the pastor–congregation dialogue and ritual directions, which makes it a source for the study of nineteenth-century Chinese Protestant creeds, membership covenants, and terminology. This dataset transcribes fourteen images from Harvard-Yenching Library DRS 428481349, including six text-bearing faces. The AI-reviewed transcription in JSON, TXT, and TEI retains 8 unresolved comparison items and one separately flagged imprint character. Full human collation is outstanding.

## 底本

富善（Chauncey Goodrich，1836–1925）著，光緒二十年（1894）京都美華書局印。哈佛燕京圖書館藏，索書號 RAREB TA 1978 8 34，DRS 428481349。 [館目](https://id.lib.harvard.edu/alma/990081336090203941/catalog) · [固定掃描](https://commons.wikimedia.org/w/index.php?title=File:Harvard_drs_428481349_%E4%BF%A1%E7%B4%84%E9%8C%84.pdf&oldid=1169961152) · [館藏 IIIF](https://iiif.lib.harvard.edu/manifests/view/drs:428481349)

原書三對折葉。固定掃描 14 幅，p003 為原刊題封，p005–p010 是六個正文面。公開 71 個歷史文字單位，包含〈六信〉、〈三約〉、原刊題封及可辨的刊記與版心。外護封題籤及館後標記保留定位。

## 資料與校讀

- data/document.json 保留逐頁逐欄文字、圖源、疑讀與缺口。
- data/text.txt 與 data/text.tei.xml 提供全文和 TEI，兩份附檔保留文字單位的對應關係。
- data/review.json 保留 56 項比對觀察、**8 項未解**的 ID 及採用的更正。初錄與隔離第二稿各自保持欄序。
- data/manifest.json 與 PACKAGE-SHA256SUMS.txt 記錄發行檔的雜湊。

Claude Opus 5.5 分別看圖完成初錄與隔離的第二稿，再對原圖覆核程式整理的 56 項比較觀察。8 項未解屬比對紀錄件數。另經原圖局部盲讀及核對，採入 p009 陰文方號「三→二」及 p010「頌公→頌」。p003 刊記末字保留「鐫／鑄」疑讀。兩稿均保存原始讀法。公開文字的 JSON、TXT、TEI 逐欄回讀，TEI 通過 P5 4.12.0 Relax NG。人工全文二校、專家審定與準確率量測待完成。

Claude Opus 5.5 produced two separate readings and checked all 56 comparison observations against the images. There are 8 unresolved comparison items. Localized blind reading and image inspection support two additional corrections, to the boxed numeral on p009 and to the composite glyph 頌 on p010. The final imprint character on p003 retains two candidates, 鐫 and 鑄. The JSON, TXT, and TEI transcriptions were read back column by column, and the TEI passed P5 4.12.0 Relax NG validation. Full human collation, expert assessment, and accuracy measurement are outstanding.

p010 的陰文「三」位於右起第三欄上方。兩份讀稿均列於頁首，引用版面位置時請對照固定原圖。p008、p010 的小字提示保留於文字及欄位說明。字級像素框尚待建立。

## 權利與引用

歷史原文及忠實轉錄按公有領域狀態提供。新增說明與可受著作權保護的編排採 CC BY 4.0。 [權利說明](LICENSE.md)

曲宸宇（Chu, Chen-Yu）。2026。信約錄（1894，DRS 428481349） / Xin yue lu: Transcription Dataset。v0.2.0。資料集。首次公開日 2026-11-20。 [固定發行](https://github.com/poplolioi11/xin-yue-lu-1894-drs-428481349/releases/tag/v0.2.0) · [ORCID](https://orcid.org/0009-0003-9738-6914) · [版本 DOI](https://doi.org/10.5281/zenodo.24393188) · [系列 DOI](https://doi.org/10.5281/zenodo.24393187)

`PACKAGE-SHA256SUMS.txt` 對應固定 v0.2.0 發行包。GitHub `main` 的引用檔與本頁另列已核的 Zenodo DOI。
