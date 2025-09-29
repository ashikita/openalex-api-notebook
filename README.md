# Jupyter NotebookによるOpenAlex APIを用いた論文のオープンアクセス（OA）情報の取得と可視化

## 概要
  
OpenAlex API tutorialで公開されている以下のJupyter notebookをオリジナルとして修正版を公開  

Monitoring Open Access publications for a given institution  
https://github.com/ourresearch/openalex-api-tutorials/blob/main/notebooks/institutions/oa-percentage.ipynb  
  
### コードの変更点

オリジナルのnotebookに対する以下の[修正リクエスト](https://github.com/ourresearch/openalex-api-tutorials/pull/11/commits/bee0bce07cd06d6f55615db8c25de9ce69926a45)を反映(211行目)  

```markdown
```diff
- if group['key'] == "true":
+ if group['key_display_name'] == "true":
```
  
### 公開ファイル

- [oa-percentage-01.ipynb](https://github.com/ashikita/openalex-api-notebook/blob/main/oa-percentage-01.ipynb)  
オリジナルに上記の修正を反映し、RORを九州大学に変更し、フィルタリングの要素に領域(domain)や分野(field)、出版年の範囲指定を追加したNotebook  

- [oa-percentage-02.ipynb](https://github.com/ashikita/openalex-api-notebook/blob/main/oa-percentage-02.ipynb)  
分析対象の要素をis_oaからoa_statusに変更したNotebook  


## 実行方法 

次のボタンをクリックすればNotebookをGoogle Colab上で実行可能  

- oa-percentage-01.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashikita/openalex-api-notebook/blob/main/oa-percentage-01.ipynb)

- oa-percentage-02.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashikita/openalex-api-notebook/blob/main/oa-percentage-02.ipynb)

## 参考資料

フィルタリング設定の参照先  
- [Filter works](https://docs.openalex.org/api-entities/works/filter-works)
- [openalex-topic-classification](https://github.com/ourresearch/openalex-topic-classification/tree/main?tab=readme-ov-file)  
- [OpenAlex topic mapping table](https://docs.google.com/spreadsheets/d/1v-MAq64x4YjhO7RWcB-yrKV5D_2vOOsxl4u6GBKEXY8/edit?gid=983250122#gid=983250122)  
