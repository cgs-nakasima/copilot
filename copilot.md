# Visual Studio2022にCopilotを入れてみた

1. 下記リンクに沿って行えば導入はできますが、下記に画像を残しました<br>
<font color="DeepSkyBlue">
[https://learn.microsoft.com/en-us/visualstudio/ide/visual-studio-github-copilot-install-and-states?view=vs-2022#install-using-the-visual-studio-installer](https://learn.microsoft.com/en-us/visualstudio/ide/visual-studio-github-copilot-install-and-states?view=vs-2022#install-using-the-visual-studio-installer)
</font>

2. Installerを起動します<br>
![](./img/installer.png)<br>

1. 更新を押して最新にします<br>
   変更を押します<br>
![](./img/installer2.png)<br>

1. Github CopilotをONにします<br>
   (例はASP.NETとWeb開発)<br>
   変更を押します<br>
![](./img/installer3.png)<br>

1. Githubアカウントが必要なので登録します（割愛）<br>
<font color="DeepSkyBlue">
[https://github.com/](https://github.com/)
</font>

3. GithubにログインしてStart free trialボタンを押します<br>
![](./img/github.png)<br>
   
1. Visual Studioを起動します<br>
   右上のGithub Copilotボタンを押します<br>
![](./img/visualstudio.png)<br>
   ログインします（どれを押したか覚えてないです。。。）<br>
 ![](./img/login.png)<br>
  ヘルプ－Visual Studioの登録を押すと（ただの確認なので押さなくていい）アカウントが２つ入っていました<br>
  (なんか視覚情報を更新してと出てますが。。。)<br>
 ![](./img/acount.png)<br>

1. 使ってみます<br>
   * 右クリックで質問するを選択します<br>
![](./img/do.png)<br>
   * 質問を入力します<br>
![](./img/do2.png)<br>
   * 右側にコードが出てきました<br>
   * 承認を押します<br>
![](./img/do3.png)<br>
   * 左側にコードが入りました<br>
![](./img/do4.png)<br>

   複雑なコードもレスポンスよく実行できるのか気になるところです<br>

1. 制限事項<br>
   残念ながら使用制限があります、１か月持つならありですかね。。。<br>
<font color="DeepSkyBlue">
[https://docs.github.com/ja/copilot/managing-copilot/managing-copilot-as-an-individual-subscriber/about-github-copilot-free](https://docs.github.com/ja/copilot/managing-copilot/managing-copilot-as-an-individual-subscriber/about-github-copilot-free)
</font>
![](./img/seigen.png)<br>

1. 入力候補がじゃまくさいと感じる時は入力候補を有効にするをOFFにします。。。<br>
   その下のオプションで色々変えれるようです<br>
![](./img/jyama.png)
 
 1. セキュリティ<br>
    会社のソースコードとなるとセキュリティが気になるかと思います<br>
    下記に調べた方がいらっしゃいました<br>
    https://zenn.dev/miyajan/scraps/3567cee380280c<br>
    取り合えず、githubのサイトの下記がデフォルトONなのでOFFにします<br>
    そうすると自分のコードが GitHub Copilot の改善に使われることはないらしい<br>
    ![](./img/security.png)<br>
    「そもそもコードサジェストのために情報を送信する必要がある」とも書いてあります

