# サポートページ

技術書典7で頒布した『Microsoft AzureでつくるクロスプラットフォームAIアシスタントスキル』のサポートページです。

- [技術書典サークルページ](https://techbookfest.org/event/tbf07/circle/5069404383477760)
- [電子版ページ](https://himanago.booth.pm/items/1572343)


## サンプルコード

### 第3章：C# ＆ Azure Functionsで思い通りにクロスプラットフォーム対応スキルを開発しよう

#### [◆「ダイスローラー」スキル（C#＋Azure Functions版）](https://github.com/himanago/dice-roller-cross-platform)

C# と Azure Functions による Googleアシスタント、Alexa、Clovaスキル対応スキルです。



#### [◆「ダイスローラー」スキル（XPlat.VUI版）](https://github.com/himanago/dice-roller-cross-platform-with-xplat-vui)

上記スキルを、下記ライブラリを使って開発したバージョンです。


#### [◆クロスプラットフォームライブラリ「XPlat.VUI」](https://github.com/himanago/xplat-vui)

Googleアシスタント、Alexa、Clovaスキルを一挙に開発できるクロスプラットフォームです。
※NuGet公開版のため、書籍掲載のものに一部機能追加・修正が施されています




### 第5章：Durable Functionsでスマートスピーカースキルの限界を超えよう

#### ◆[Durable Functions を用いたロングランニングなスキル（XPlat.VUI使用）](https://github.com/himanago/xplat-vui-durable-sample)

Durable Functionsを使ったクロスプラットフォーム対応スキル（数を数えるだけのシンプルなもの）。



#### ◆[テキスト腹話術（Durable Functions＋無音無限ループ）](https://github.com/line-developer-community/line-api-handbook/tree/master/chapter05/ClovaVentriloquism)

CEK.CSharp の現行バージョンでの再実装版「テキスト腹話術」です。
※LINE Developer Community内


### 第6章：スマートフォンアプリとVUI・クロスプラットフォーム対応

#### ◆[Xamarin.Forms＋4アシスタント](https://github.com/himanago/xamarin-with-vui-sample)

Xamarin.Formsによるメモアプリケーションに4アシスタントとの機能共有と画面のVUI対応を施したもの。


## 正誤表

### 第3章：C# ＆ Azure Functionsで思い通りにクロスプラットフォーム対応スキルを開発しよう

#### ◆紙版P.118 / 電子版P.117（ソースコード）

##### 誤

```cs
var assistant = new T2();
return services.AddScoped<T1, T2>(_ => assistant);
```

##### 正

```cs
return services.AddScoped<T1, T2>();
```

その他は後日掲載予定です。