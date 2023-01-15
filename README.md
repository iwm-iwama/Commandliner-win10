【実行に必要なファイル】

	iwm_Commandliner.exe
	Microsoft(R) .NET Framework 4.8.1 ランタイム
		https://dotnet.microsoft.com/ja-jp/download/dotnet-framework/thank-you/net481-web-installer

【このプログラムについて】

	コマンド出力されたテキスト結果を、ビジュアル的に加工するために作成されました。
	ワンオフで使用するデータを作成するのに適しています。
	（繰り返し使用する場合、一連の処理をコマンドファイルとして保存することも可能です。）

	少し複雑ですが、「指定したURLから画像ファイルを抽出しダウンロードする」といったことも可能です。
	(例)
		(1) #wread マクロを使用して、URLからソースファイルをダウンロードする。
		(2) #extract マクロを使用して、画像ファイルのURLを抽出する。
		(3) #streamdl マクロを使用して、画像ファイルをダウンロードする。

【Windows Defender 誤検出メモ】

	[20220810-20220815] Ver.4.4における誤検出例
		セキュリティインテリジェンスのバージョン: 1.373.80.0
			Trojan:Script/Wacatac.B!ml
		セキュリティインテリジェンスのバージョン: 1.373.326.0
			Trojan:Script/Wacatac.H!ml
		セキュリティインテリジェンスのバージョン: 1.373.336.0
			Trojan:Win32/AgentTesla!ml

	[20220815-]
		セキュリティインテリジェンスのバージョン: 1.373.374.0 以降 誤検出なし
