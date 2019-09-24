# サポートページ

技術書典7で頒布した『Microsoft AzureでつくるクロスプラットフォームAIアシスタントスキル』のサポートページです。

- [技術書典サークルページ](https://techbookfest.org/event/tbf07/circle/5069404383477760)
- [電子版ページ](https://himanago.booth.pm/items/1572343)


## サンプルコード

### 第3章：

#### 「ダイスローラー」スキル（C#＋Azure Functions版）
C# と Azure Functions による Googleアシスタント、Alexa、Clovaスキル対応スキルです。

https://github.com/himanago/dice-roller-cross-platform

#### 「ダイスローラー」スキル（XPlat.VUI版）

上記スキルを、下記ライブラリを使って開発したバージョンです。

https://github.com/himanago/dice-roller-cross-platform-with-xplat-vui

#### クロスプラットフォームライブラリ「XPlat.VUI」

Googleアシスタント、Alexa、Clovaスキルを一挙に開発できるクロスプラットフォームです。
※NuGet公開版のため、書籍掲載のものに一部機能追加・修正が施されています

https://github.com/himanago/xplat-vui


### 第5章

#### Durable Functions を用いたロングランニングなスキル（XPlat.VUI使用）

Durable Functionsを使ったクロスプラットフォーム対応スキル（数を数えるだけのシンプルなもの）。

https://github.com/himanago/xplat-vui-durable-sample

#### テキスト腹話術（Durable Functions＋無音無限ループ）

CEK.CSharp の現行バージョンでの再実装版「テキスト腹話術」です。
※LINE Developer Community内

https://github.com/line-developer-community/line-api-handbook/tree/master/chapter05/ClovaVentriloquism

### 第6章

#### Xamarin.Forms＋4アシスタント

Xamarin.Formsによるメモアプリケーションに4アシスタントとの機能共有と画面のVUI対応を施したもの。

https://github.com/himanago/xamarin-with-vui-sample

## 正誤表

### 第3章

#### 紙版P.118 / 電子版P.117（ソースコード）

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