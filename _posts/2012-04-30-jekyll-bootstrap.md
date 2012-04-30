---
layout: page
title: githubページでjekyll bootstrapを使う
tagline: github jekyll
---
githubページにjekyll bootstrapをインストールして使ってみる

[Blogging with Jekyll Tutorial | Jekyll-Bootstrap](http://jekyllbootstrap.com/)

上記ページにgithubのusernameを入れればそのままコピペで使える。

    $ git clone https://github.com/plusjade/jekyll-bootstrap.git e-luck.github.com
    $ cd e-luck.github.com
    $ git remote set-url origin git@github.com:e-luck/e-luck.github.com.git
    $ git push origin master

このまま5分から10分ほど待つと、githubからページの用意が出来ました的なNotificationが届けば自分のgithubページで確認できる。

あとはThemeを変更。[http://themes.jekyllbootstrap.com/]で気になったやつのInstall Themeボタンを押すと、rakeコマンドのコードが表示されるので実行してmasterに反映。
