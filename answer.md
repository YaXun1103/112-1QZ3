# 第3次隨堂-隨堂-QZ3
>
>學號：111111109
><br />
>姓名：張雅薰
><br />
>作業撰寫時間：20 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2023/12/08
>
## 說明程式與內容
先fork老師的倉庫並clone
```git
 git clone
```
按照投影片練習並完成動畫:更改 div 的背景顏色和位置 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .firstDiv{
            width: 220px;
            height: 220px;
            border: 1px solid red;
        }
        .secondDiv{
            width: 20px;
            height: 20px;
            background-color: red;
            position: relative;
            animation-name: example;
            animation-duration: 4s;
            animation-iteration-count: infinite;
        }
        @keyframes example{
            0%{
                background-color: rgb(201, 157, 237);
                left: 0px;
            }
            50%{
                background-color: rgb(27, 27, 88);
                left: 200px;
            }
            100%{
                background-color:  rgb(201, 157, 237);
                left: 0px;
            }
            }

    </style>
</head>
<body>
    <div class="firstDiv">
        <div class="secondDiv"></div>
    </div>
       
</body>
</html>
```
推上github
```git
git add 
git commit 
git push
```

## 個人認為完成作業須具備觀念
1.HTML 結構了解 HTML 標籤的運用，瞭解如何建立基本的網頁結構。<br />
2.CSS 基本樣式設定： 具備對於 CSS 屬性的基本認識。<br />
3.CSS 動畫效果： 學會使用 CSS 中的 @keyframes 規則，理解動畫效果的基本運作原理，例如動畫名稱、持續時間等屬性。<br />
4.基本的 Git 操作：fork 別人的倉庫、clone 倉庫到本地、add、commit、push 等基本的 Git 操作。

