# -
nccu美食拾荒器

在使用此檔案之前須注意以下事項:
1. 下載JMapViewer的jar檔,(新增)下載jsoup.jar:附上網址:"https://jsoup.org/download", 下載sqlite-jdbc的jar檔

2. 若使用eclipse,請build path 加入 archive 再把jar檔案放進去

3.(新增)已將所有店家的圖片scrap至src中的image folder,是放到sql需要使用的

4.(新增)image folder 內含 駱駝.PNG,且修改mainapp的icon,頭像駱駝已經可以顯示

5.(新增)foodlist放置所有的Node(一個一個店家的節點),詳述請看Node class 內有節點有的詳細資料型態

6.(新增)基本上我把所有的東西包裝到foodlist內,裡面有一個 method:GetAllNodes(),可以利用node拿到我所有爬取的資料
