OpenAlex API tutorialのoa-percentage出力用Jupyter notebook公開ページ  
https://github.com/ourresearch/openalex-api-tutorials/blob/main/notebooks/institutions/oa-percentage.ipynb  
  
コードの修正点  
211行目: if group['key']==\"true\":\n", => if group['key_display_name']==\"true\":\n",  
参考: https://github.com/ourresearch/openalex-api-tutorials/pull/11/commits/bee0bce07cd06d6f55615db8c25de9ce69926a45  
  
修正を反映し、RORを九州大学に変更、出版年の範囲指定を変更したコード  
oa-percentage-01.ipynb  

Google Colabでoa-percentage-01.ipynbを実行するURL  
https://colab.research.google.com/github/ashikita/openalex-api-notebook/blob/main/oa-percentage-01.ipynb  

参考: topic  
https://github.com/ourresearch/openalex-topic-classification/tree/main?tab=readme-ov-file  
OpenAlex_topic_mapping_table  
https://docs.google.com/spreadsheets/d/1v-MAq64x4YjhO7RWcB-yrKV5D_2vOOsxl4u6GBKEXY8/edit?gid=983250122#gid=983250122  
