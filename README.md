# DataScience_FEA
 
### データサイエンス期末課題のソースコード

#### ノートブックの概要
- `CropArea.ipynb`
　第1次産業就業者数と田畑の面積をプロットしたコード
- `BirthRate.ipynb`  
　出生数と就業人数，有配偶率の関係を重回帰分析しようとしたコード  ~~（どう足掻いてもVIFが高かったのでボツ）~~
- `Cost.ipynb`  
　教育費と各種消費で重回帰分析したコード

#### データの取得元
- [人口動態調査（e-Stat）](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00450011&tstat=000001028897&cycle=8&tclass1=000001053122&tclass2=000001053130&result_page=1&tclass3val=0&metadata=1&data=1)  
　第1次産業就業者のデータ
- [作物統計調査（e-Stat）](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00500215&tstat=000001013427&cycle=0&tclass1=000001032270&tclass2=000001034721&tclass3val=0)  
　田畑面積のデータ
- [労働力調査 / 基本集計　全都道府県 地域別 年次](https://www.e-stat.go.jp/stat-search/database?page=1&layout=datalist&stat_infid=000032045605&statdisp_id=0003009700)  
　年齢階層別の就業者数のデータ
- [社会・人口統計体系](https://www.e-stat.go.jp/regional-statistics/ssdsview)
　有配偶率のデータ
- [SSDSE（教育用標準データセット）（独立行政法人統計センター）](https://www.nstac.go.jp/use/literacy/ssdse/)
　各種消費データを利用するためのデータセット
