![](https://img.shields.io/badge/Python-3.11.3-blue)
# DataScience_FEA
 
### データサイエンス期末課題のソースコード  

#### ノートブックの概要
- `CropArea.ipynb`  
　第1次産業就業者数と田畑の面積をプロットしたコード
- `BirthRate.ipynb`  
　出生数と就業人数，有配偶率の関係を重回帰分析しようとしたコード  ~~（考察しづらかったのでボツ）~~
- `Cost.ipynb`  
　教育費と各種消費で重回帰分析したコード

#### データの取得元

| 取得元 | 概要 | 該当ファイル名 |
| :--: | :--: | :--: |
| [人口動態調査（e-Stat）](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00450011&tstat=000001028897&cycle=8&tclass1=000001053122&tclass2=000001053130&result_page=1&tclass3val=0&metadata=1&data=1)  | 第1次産業就業者のデータ | `population_2000.csv`<br>`population_2005.csv`<br>`population_2010.csv`<br>`population_2015.csv`<br>`population_2020.csv`|
| [作物統計調査（e-Stat）](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00500215&tstat=000001013427&cycle=0&tclass1=000001032270&tclass2=000001034721&tclass3val=0)  | 田畑面積のデータ | `CropArea_Data.xls` |
| [労働力調査 / 基本集計　全都道府県 地域別 年次（e-Stat）](https://www.e-stat.go.jp/stat-search/database?page=1&layout=datalist&stat_infid=000032045605&statdisp_id=0003009700)  | 年齢階層別の就業者数データ | `FEH_00200531_230720133248.xlsx`<br>`FEH_00200531_230720133159.xlsx` |
| [社会・人口統計体系（e-Stat）](https://www.e-stat.go.jp/regional-statistics/ssdsview)  | 有配偶率のデータ<br>出生数のデータ | `FEI_PREF_230720160448.xlsx`<br>`FEI_PREF_230721113206.xlsx` |
| [SSDSE（教育用標準データセット）（独立行政法人統計センター）](https://www.nstac.go.jp/use/literacy/ssdse/)  | 各種消費データ | `SSDSE-B-2023.xlsx` |