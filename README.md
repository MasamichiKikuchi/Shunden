■タイトル    
瞬電(しゅんでん)
--------------------------------
■作品概要説明   
近未来の東京を舞台に、暴走したアンドロイドを破壊するためアンドロイドの忍者少女を操作して夜のビル群を縦横無尽に跳びまわる忍者×居合３Dアクションです。  
ジャンプ等のアクションでギミックを攻略し、瞬電（チャージ攻撃）やクナイ等の攻撃を駆使して敵を次々をなぎ倒してステージをクリアしてゆくゲームです。
敵を連続で倒すと「コンボ」が加算され、敵から得られる報酬が増加します。  
ステージをクリアするごとに主人公をエディット可能です。敵を倒して入手したBLOOD（ゲーム内通貨）で主人公を強化できます。
--------------------------------
■作品紹介  
[瞬電_作品紹介.pptx](https://github.com/user-attachments/files/22596770/_.pptx)
--------------------------------
■ジャンル  
アクション
--------------------------------
■開発期間  
 2024/11/29～2025/03/31
-------------------------------
■開発環境：開発時に使用したツールや言語など    
 OS：Windows 10  
 言語：C/C++  
 Microsoft Visual Studio 2022  
 Dxライブラリ  
 Effekseer  
------------------------------
■開発体制  
企画：  
 井上 赳  
 新井 雄介  
プログラム：  
 駒沢 風助   
 石川 智也   
 菊池 雅道   
グラフィック：  
 秋元 優衣  
 小林 心    
 佐藤 凌    
 野間 恵佳  
 德吉 絢香   
--------------------------------
■動作環境  
Windows 10またはWindows 11
--------------------------------
■起動方法  
Releasesページhttps://github.com/MasamichiKikuchi/Shunden/releasesより実行ファイルをダウンロード  
→Syunden.ZIPを解凍  
→iAi_Project.exeを実行  
※操作説明は添付資料を参照  
--------------------------------
■終了方法  
 ホーム画面から「ゲーム終了」を選択、もしくはalt+F4で終了
--------------------------------
■プロジェクト構成（一部抜粋）  
プロジェクトデータフォルダ  
❙  
┗AppFrameフォルダ（フレームワークデータ）  
❙ ┗sourceフォルダ（スクリプトデータ　※フレームワーク部分）  
❙ ┗AppFrame.sln（Visual Studioソリューションファイル　※フレームワーク部分のみ）  
❙  
┗DxLibフォルダ（使用ライブラリデータ）  
❙  
┗iAi_Projectフォルダ  
❙ ┗iAi_Projectフォルダ  
❙ 　┗sourceフォルダ（スクリプトデータ　※プロジェクト部分）  
┗iAi_Project.sln（Visual Studioソリューションファイル　※プロジェクト全体）  
--------------------------------
■担当ファイル  
主にプレイヤーキャラクターの挙動（モーション・描画以外）や当たり判定、カメラワークの一部を担当しました。  
BulletPlayerKunai.cpp,  
BulletPlayerKunai.h,  
BulletPlayerKunaiExplosion.cpp,  
BulletPlayerKunaiExplosion.h,  
BulletPlayerKunaiWarp.cpp,  
BulletPlayerKunaiWarp.h,  
BulletPlayerMeleeWeak.cpp,  
BulletPlayerMeleeWeak.h,  
CharacterPlayer.cpp,CharacterPlayer.h,  
CharacterPlayerAttack.cpp,  
CharacterPlayerMove.cpp,  
DataList_PlayerStatus.cpp,  
DataList_PlayerStatus.h,  
EffectManualDelete_PlayerFollow_Frame.cpp,  
EffectManualDelete_PlayerFollow_Frame.h,  
EffectSelfDelete_PlayerFollow_Frame.cpp,  
EffectSelfDelete_PlayerFollow_Frame.h,  
PlayerStatusDefine.h,  
SceneStage_Camera.cpp,  
SceneUi_Crosshairs.cpp,  
--------------------------------
