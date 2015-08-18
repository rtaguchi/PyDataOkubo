# Frequency Analysis - 頻度分析
---
ここではテキストマイニングの初歩として、特定の文章に含まれる単語の出現頻度を分析します。  

## とても簡単な頻度分析
まず、最初の一歩として文章を単語に分割し、各単語の出現数を数えてみます。  
対象はローカルファイルに保存された英語の文章とします。    

[サンプル](https://github.com/uurotanli/PyDataOkubo/blob/master/01.FrequensyAnalysis/01.simpleAnalysis.ipynb)

## Webスクレイピングして頻度分析
分析対象の文章をいちいちファイルで用意するのは面倒です。  
そこで分析対象とする文章をWebサイトから取ってこられるようにしましょう。  

Webスクレイピングには様々な方法がありますが、ここでは「Beautiful Soup」というライブラリを使用します。  
「Beautiful Soup」の解説は[こちらのサイト](http://kondou.com/BS4/)を参考にして下さい。

サンプル（作成中）
