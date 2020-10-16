---
theme: "black"
transition: "default"
---

# はじめての wasm

# はじめての Bolero

@amderbar

---

Web フロントエンド開発といえば…

---

- React
- Vue
- Angular
- etc...

---

どれも結局 JS でしょ？

---

おもしろくない

---

[【増枠】フロントエンド LT 会 vol.1 -2020 夏祭り- #frontendlt](https://rakus.connpass.com/event/183881/)（2020 年 8 月 26 日開催）

naito さん

「[Blazor Web Assembly (C#) を触ってみた](https://www.slideshare.net/nnt7/blazor-web-assembly-c-238269520?ref=https://rakus.connpass.com/event/183881/presentation/)」

---

Blazor とは…？

- .NET（C#）を使って SPA 開発ができるフレームワーク
- WebAssembly (wasm) にコンパイルされる

---

おもしろそう

---

だが待ってほしい

---

F# ならきっともっとたのしい

---

![Bolero トップページのキャプチャ](fsbolero.io/hero.png)
https://fsbolero.io

---

![Bolero 説明のキャプチャ](fsbolero.io/description.png)
https://fsbolero.io

---

サンプルを動かしてみる

---

```powershell
PS C:\..> dotnet new -i Bolero.Templates

.NET Core 3.1 へようこそ!
---------------------
SDK バージョン: 3.1.402
    :
    (省略)
    :
PS C:\..> dotnet new bolero-app -o MyApp
The template "Bolero Hosted Application" was created successfully.
```

---

```powershell
PS C:\..> cd MyApp && dotnet run -p src/MyApp.Server
    :
    (省略)
    :
Now listening on: http://localhost:5000
Now listening on: https://localhost:5001
Application started. Press Ctrl+C to shut down.
```

---

![Bolero サンプルスクショ](bolero_application_sample.png)

---

Bolero （wasm）ではじめてのアプリ！

---

# 以上
