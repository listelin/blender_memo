# blenderでMMDのモーフを追加する

* 前提:blenderにmmd_toolsがインストールされていること

1. MMDモデルを読み込む  
![picture 1](image/addmorph-2022-07-19-223520.png)  

2. モーフツールから＋を押して新しいMMDモーフを追加

![picture 2](image/addmorph-2022-07-19-224015.png)  

3. ダブルクリックして名前を変更

![picture 3](image/addmorph-2022-07-19-224237.png)  

4. モデルのメッシュを選択して、プロパティの緑の逆三角にあるblenderのシェイプキーに同じ名前のモーフを追加

![picture 4](image/addmorph-2022-07-19-224340.png)  

5. モーフの数値を1.0にした後、メッシュを修正する（ここではスカルプトのグラブブラシで修正している）
![picture 6](image/addmorph-2022-07-19-225245.png)  


https://user-images.githubusercontent.com/44924233/180204606-2d446b7b-ca03-4110-8170-4d6ec7eedf40.mp4


* 参考：材質（メッシュ）を分離しなくても、ブラシ＞自動マスク：トポロジーをチェックするとトポロジー的につながっている部分のみ修正できる

![picture 5](image/addmorph-2022-07-19-224957.png)  

6. MMDモデルをエクスポートする

![picture 7](image/addmorph-2022-07-19-225546.png)  
