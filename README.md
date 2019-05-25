<H1>Project：Fund-Investment-Strategy </H1>

以財務模型為基礎，開發五組策略且最好的策略績效高於benchmark 90%。

<H2>Project Flow Chart</H2>

*   策略流程圖
![image](https://github.com/Martin8202/Lunch-recommendation-system/blob/master/Modle%20Flow%20chart.jpg)

<H2>Data</H2>

1.訓練資料集：氣溫、雨量、濕度、用餐時段、星期幾、餐廳經緯度、愛評網評分、使用者評分、使用者過去用餐結果

<H2>File Description</H2>

* Data：<br>
    1.外部資料檔：氣溫、雨量、濕度、用餐時段、星期幾
    2.歷史資料檔：餐廳經緯度、愛評網評分、使用者評分、使用者過去用餐結果
* collect_code：<br>
    1.透過爬蟲或API蒐集外部資料之程式(R)
* shiny：<br>
    1.以shiny呈現之程式檔(R)
* RandomForest.R：<br>
    1.以隨機森林模型建立推薦餐廳
    
<H2>Some Example</H2>

*   推薦系統D
![image](https://github.com/Martin8202/Lunch-recommendation-system/blob/master/recommandation%20system_new.png)


 