[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tomiokario/MathPDF2MD/blob/main/MathPDF2MD.ipynb)


# 数式を含むPDFをMarkdownに変換
**概要**
- 数式と表を含むPDFをOCRしてMarkdownに変換します．
- Meta AIのNougat (Neural Optical Understanding for Academic Documents)[1,2]を使用します．
- 無料版Google Colabで実行できます[3]．

**詳細**
- 2段組みなど複雑な構造にも対応しています[1,2]．
- 図には対応していません．
- Markdownファイル出力後，Scrapbox記法のtxtファイルに変換できます．

**NougatのLicense**
- Nougat codebase is licensed under [MIT](https://opensource.org/license/mit/) [1,2].
- Nougat model weights are licensed under [CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/deed.ja) [1,2].

**参考**
1. [Nougat: Neural Optical Understanding for Academic Documents | Project page](https://facebookresearch.github.io/nougat/)
2. [facebookresearch/nougat: Implementation of Nougat Neural Optical Understanding for Academic Documents | GitHub Repository](https://github.com/facebookresearch/nougat)
3. [数式を含むPDFをOCRしてマークダウン形式に変換できる、Nougatを試す｜はまち](https://note.com/hamachi_jp/n/n7f5f35b38768)

---

# Convert PDF with mathematical expression into Markdown style
**abstract**
- It OCRs and converts PDFs containing formulas and tables to Markdown.
- It uses Nougat (Neural Optical Understanding for Academic Documents)[1,2] from Meta AI.
- It can be run on the free version of Google Colab [3].

**Details**.
- Complex structures such as double columns are supported [1,2].
- Figures are not supported.
- After outputting a Markdown file, it can be converted to a Scrapbox txt file.

**License of Nougat**
- Nougat codebase is licensed under [MIT](https://opensource.org/license/mit/) [1,2].
- Nougat model weights are licensed under [CC BY-NC](https://creativecommons.org/licenses/by-nc/4.0/deed.ja) [1,2].

**References**
1. [Nougat: Neural Optical Understanding for Academic Documents | Project page](https://facebookresearch.github.io/nougat/)
2. [facebookresearch/nougat: Implementation of Nougat Neural Optical Understanding for Academic Documents | GitHub Repository](https://github.com/facebookresearch/nougat)
3. [数式を含むPDFをOCRしてマークダウン形式に変換できる、Nougatを試す｜はまち](https://note.com/hamachi_jp/n/n7f5f35b38768)
