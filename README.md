# かくれんぼのルール

かくれんぼのルールを管理したリポジトリです。以下の運用方針に従って、適切にルールの運用を行ってください。

## ルール改善のポリシー

かくれんぼのルール改善を行うに際して、必ず下記のポリシーに目を通すようにお願いします。ポリシーに大きく反する改善は基本的に認めないこととします。

```
1. 基本ルールは「かくれんぼ（缶蹴り）」から逸脱しないこと
2. 参加者が理解しやすいこと
3. 運営者が運用しやすいこと
4. 基本的にはルールを変えないこと
```

### 1. 基本ルールは「かくれんぼ（缶蹴り）」から逸脱しないこと

そもそもかくれんぼと言いつつ缶蹴りを進めている我々は何なのか、というところは置いておき笑

ポイントが付かない基礎ルールは「かくれんぼ（缶蹴り）」から逸脱したくないなぁというのが豊川の気持ちです。

一番気にしているところとしては、ルール改変の結果「かくれんぼ」ではないものが出来上がり、それを「世界に持っていった」とて本末転倒で目的を果たしていないことになってしまうからです。もちろん、世界に持っていくのにあらゆる手段は使うんだけど、広まらないからと言って「ルールを変更する」という手段は基本取らないスタンスで行きたいと思います。

### 2. 参加者が理解しやすいこと

かくれんぼを世界に持っていくに当たって外せないのは参加者です。その参加者がわかりにくいルールは基本的には作らない用に心がけたいです。

何がわかりやすくて、何がわかりにくいかの線引は難しいけど、多分運営チーム内で話した時に「？」が浮かんだら疑うくらいな気持ちがいいのかもしれないっすね。

### 3. 運営者が運用しやすいこと

参加者も大事なんですが、運営者も同じくらい大事です。今後の話になりますが、他県展開をしていく中で自分ら以外の運営者を作っていかなければなりません。運営者なくしてかくれんぼの普及は無いので。

そうなった時に「参加者が理解しやすこと」と同様に、運営者が混乱するようなルールは避けたいと考えています。

### 4. 基本的にはルールを変えないこと

もはや矛盾の塊なんだけど、よっぽど致命的な問題に直面しない限りルールは変えなくてもいいんじゃない？と考えています。特に運営サイドが一方的に「こうなんじゃないか？」と早とちりをして、それに対して無意味なルール変更が走ることは避けたいです。

かくれんぼに限らず、プログラミングとかもそうだけど、当然ながら初期のものの方が一番シンプルです。そこにアレヤコレヤとエッセンスを織り交ぜることでスパゲッティになってしまう。

っということもあり、昨日最後に話したけど「課題に即して、できる限り小さく」ルールを変更できたらなぁと考えてます。

## 改善の方法

まず大前提、ルール変更の提案は誰が行ってもOKとします。ただし、`master`ブランチに直接的にルールの変更を反映させることは禁止とします。

```
1. feature/xx(ルール変更内容に即した名前)でブランチを切る
2. ルールの該当箇所を変更する
3. プルリクエストを作成する
4. レビューによりApproveされれば変更をマージする
```
