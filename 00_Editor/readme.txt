//==============================================================================
//
// readmeファイル [readme.txt]
// Author : Tanaka Kota
//
// 最終更新日 : 2023/09/05
//==============================================================================

◇readme.txt
最初に知っていただきたい情報を記載しております。

//----------------------------------------------------------------------------
◆作品について◆
//----------------------------------------------------------------------------

◆作品名		 : tool_effect[エディター]
◇使用言語		 : C++
◇SDK	  		 : DirectX9
◇使用ライブラリ : nlohmann(json), imgui
◇開発期間		 : 2023/04～

◆動作確認済み環境◆
Windows10

◆こだわった点◆
ImGuiを使用して、簡単に自身が想像していたパーティクルを作りやすくしました。
タグを設定し、そのタグ内で複数のパーティクルデータを操作するようにした事で
より要素を盛りやすく、演出面を強化できるようにした所をこだわりました。

また、このエディタは今も制作中であり、テスト中ではありますが、
物理演算や音を付与したいと考えています。

//----------------------------------------------------------------------------

◆作品名		 : tool_stage[エディター]
◇使用言語		 : C++
◇SDK	  		 : DirectX9
◇使用ライブラリ : nlohmann(json), imgui
◇開発期間		 : 2023/07～

◆動作確認済み環境◆
Windows10

◆操作方法◆
Enter	 - オブジェクト設置
Ctrl + C - 選択したオブジェクトのコピー
Ctrl + V - コピーしたオブジェクトを貼り付け

◆こだわった点◆
こちらもImGuiを使用しており、既存の機能をカスタムしてオブジェクトの位置などのデータを
操作しやすくしました。
また、右クリックで簡単にオブジェクトを選択するという部分もこだわりました。

//----------------------------------------------------------------------------

◆作品名		 : チーム制作ベータ版[ゲーム]
◇使用言語		 : C++
◇SDK	  		 : DirectX9
◇開発期間		 : 2023/05～

◆動作確認済み環境◆
Windows10

◆操作方法◆
Enter	 - 決定
Space	 - 鉱石堀り、攻撃
WASD	 - 移動

◆こだわった点◆
現在開発中のゲームです。
このゲーム内のパーティクルなどで上記２つのツールを使用しています。