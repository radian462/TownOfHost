# Town Of Host

[![TownOfHost-Title](./Images/TownOfHost-Title.png)](https://youtu.be/IGguGyq_F-c)

<p align="center"><a href="https://github.com/tukasa0001/TownOfHost/releases/"><img src="https://badgen.net/github/release/tukasa0001/TownOfHost"></a></p>

## この Mod について

この Mod は非公式のものであり、この Mod の開発に関して Among Us の開発元である"Innersloth"は一切関与していません。<br>
この Mod の問題などに関して公式に問い合わせないでください。<br>

[![Discord](./Images/TownOfHost-Discord.png)](https://discord.gg/W5ug6hXB9V)

## リリース

**最新版は[こちら](https://github.com/tukasa0001/TownOfHost/releases/latest)**

過去バージョンは[こちら](https://github.com/tukasa0001/TownOfHost/releases)

## 特徴

この Mod はホストのクライアントに導入するだけで動作し、他のクライアントの Mod の導入/未導入及び端末の種類に関係なく動作します。<br>
また、カスタムサーバーを利用した Mod と違い、URL やファイル編集などによるサーバー追加も不要なため、ホスト以外のプレイヤーは Town Of Host を導入したホストの部屋に参加するだけで追加役職を楽しむことができます。<br>

しかし、以下の制限が発生することにご注意ください。<br>

- ホストが途中抜けをするなどの要因でホストが変更された場合、追加役職に関する処理が正常に動作しない可能性がある。
- 特殊役職を使用した場合、その特殊役職の設定を書き換える。(例 : 通気口のクールダウンをなくすなど)

なお、ホスト以外のプレイヤーがこの Mod を導入した状態でプレイすると、以下のような変更が行われます。<br>

- 特殊役職独自の開始画面の表示
- 特殊役職の正常な勝利画面の表示
- 設定項目の追加
- その他

## 機能
### ホットキー

#### 全クライアント
| キー        | 機能                                                              | 使えるシーン |
| ----------- | ----------------------------------------------------------------- | ------------ |
| `Tab`       | オプション一覧のページ送り                                        | ロビー       |
| `Ctrl`+`F1` | ログをデスクトップに出力                                          | どこでも     |
| `F11`       | 解像度を変更<br>480x270 → 640x360 → 800x450 → 1280x720 → 1600x900 | どこでも     |
| `Ctrl`+`C`  | 文章をコピー                                                      | チャット     |
| `Ctrl`+`V`  | 文章を貼り付け                                                    | チャット     |
| `Ctrl`+`X`  | 文章を切り取り                                                    | チャット     |

#### ホストのみ
| キー                | 機能                         | 使えるシーン     |
| ------------------- | ---------------------------- | ---------------- |
| `Shift`+`L`+`Enter` | 廃村                         | ゲーム内         |
| `Shift`+`M`+`Enter` | ミーティングをスキップで終了 | ゲーム内         |
| `Ctrl`+`N`          | 有効な役職の説明を表示       | ロビー&ゲーム内  |
| `C`                 | ゲーム開始を中断             | カウントダウン中 |
| `Shift`             | ゲームを即開始               | カウントダウン中 |

### チャットコマンド
チャットコマンドはチャットで入力して使用できるコマンドです。
| コマンド                                    | 機能                                                |
| ------------------------------------------- | --------------------------------------------------- |
| /winner<br>/win                             | 勝者を表示                                          |
| /lastresult<br>/l                           | 試合結果を表示                                      |
| /now<br>/n                                  | 現在の設定を表示                                    |
| /rename <名前><br>/r <名前>                 | 名前を変更                                          |
| /dis <crewmate/impostor>                    | 試合をクルーメイト/インポスターの切断として終了する |
| /template <タグ><br>/t <タグ>               | タグに対応した定型文を表示                          |
| /messagewait <秒><br>/mw <秒>               | メッセージの表示間隔の秒数を設定                    |
| /help<br>/h                                 | コマンドの説明を表示                                |
| /help roles <役職><br>/help r <役職>        | 役職の説明を表示                                    |
| /help attributes <属性><br>/help att <属性> | 属性の説明を表示                                    |
| /help modes <モード><br>/help m <モード>    | モードの説明を表示                                  |
| /help now<br>/help n                        | 有効な設定の説明を表示                              |

## 役職

| インポスター陣営                                                                     | クルーメイト陣営                                                           | 第三陣営                                                                   |
| ------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [BountyHunter/バウンティハンター](#BountyHunterバウンティハンター)                   | [Bait/ベイト](#Baitベイト)                                                 | [Arsonist/アーソニスト](#Arsonistアーソニスト)                             |
| [Evil Watcher/イビルウォッチャー](#Watcherウォッチャー)                              | [Dictator/ディクテーター](#Dictatorディクテーター)                         | [Egoist/エゴイスト](#Egoistエゴイスト)                                     |
| [FireWorks/花火職人](#FireWorks花火職人)                                             | [Doctor/ドクター](#Doctorドクター)                                         | [Executioner/エクスキューショナー](#Executionerエクスキューショナー)       |
| [Mare/メアー](#Mareメアー)                                                           | [Lighter/ライター](#Lighterライター)                                       | [Jester/ジェスター](#Jesterジェスター)                                     |
| [Puppeteer/パペッティア](#Puppeteerパペッティア)                                     | [Mayor/メイヤー](#Mayorメイヤー)                                           | [Lovers/恋人](#Lovers恋人)                                                 |
| [SerialKiller/シリアルキラー](#SerialKillerシリアルキラー)                           | [Nice Watcher/ナイスウォッチャー](#Watcherウォッチャー)                    | [Opportunist/オポチュニスト](#Opportunistオポチュニスト)                   |
| [ShapeMaster/シェイプマスター](#ShapeMasterシェイプマスター)                         | [SabotageMaster/サボタージュマスター](#SabotageMasterサボタージュマスター) | [Terrorist/テロリスト](#Terroristテロリスト)                               |
| [Sniper/スナイパー](#Sniperスナイパー)                                               | [Sheriff/シェリフ](#Sheriffシェリフ)                                       | [SchrodingerCat/シュレディンガーの猫](#SchrodingerCatシュレディンガーの猫) |
| [TimeThief/タイムシーフ](#TimeThiefタイムシーフ)                                     | [Snitch/スニッチ](#Snitchスニッチ)                                         |                                                                            |
| [Vampire/ヴァンパイア](#Vampireヴァンパイア)                                         | [SpeedBooster/スピードブースター](#SpeedBoosterスピードブースター)         |                                                                            |
| [Warlock/ウォーロック](#Warlockウォーロック)                                         | [Trapper/トラッパー](#Trapperトラッパー)                                   |                                                                            |
| [Witch/魔女](#Witch魔女)                                                             |                                                                            |                                                                            |
| [Mafia/マフィア](#Mafiaマフィア)                                                     |                                                                            |                                                                            |
| [Madmate/マッドメイト](#Madmateマッドメイト)                                         |                                                                            |                                                                            |
| [MadGuardian/マッドガーディアン](#MadGuardianマッドガーディアン)                     |                                                                            |                                                                            |
| [MadSnitch/マッドスニッチ](#MadSnitchマッドスニッチ)                                 |                                                                            |                                                                            |
| [SidekickMadmate/サイドキックマッドメイト](#SidekickMadmateサイドキックマッドメイト) |                                                                            |                                                                            |

### BountyHunter/バウンティハンター

陣営 : インポスター<br>
判定 : インポスター<br>

表示されたターゲットをキルした場合、次のキルクールがとても短くなります。<br>
ターゲットではないプレイヤーをキルした場合は、キルクールが伸びてしまいます。<br>
<!--また、設定でキルクールを 2.5 秒に設定する必要があります。<br>-->
ターゲットは一定時間ごとに変更されます。<br>

#### 設定

| 設定名                                                          |
| --------------------------------------------------------------- |
| バウンティハンターのターゲットが変わる時間(s)                   |
| バウンティハンターがターゲットをキルした後のクールダウン(s)     |
| バウンティハンターがターゲット以外をキルした時のクールダウン(s) |
| バウンティハンター以外のキルクールダウン(s)                     |

### FireWorks/花火職人

陣営 : インポスター<br>
判定 : シェイプシフター<br>

花火の爆破によって大量キル出来る役職です。<br>
最大3個の花火をシェイプシフトのタイミングで設置出来ます。<br>
すべての花火を設置したら、最後のインポスターとなった時にシェイプシフトのタイミングで一斉起爆します。<br>
花火を設置し始めてから爆破するまでキル出来ません。<br>
自身が爆破に巻き込まれても全滅させることが出来た場合は勝利となります。

#### 設定

| 設定名         |
| -------------- |
| 花火の所持数   |
| 花火の爆発半径 |

### Mare/メアー

陣営 : インポスター<br>
判定 : インポスター<br>

停電時以外にキルをすることができませんが、キルクールが半分になります。<br>
停電中にのみ移動速度も上昇しますが、自分の名前が赤く表示されます。<br>

### Puppeteer/パペッティア

陣営 : インポスター<br>
判定 : インポスター<br>

キルした対象に、対象が次に近づいたクルーをキルさせます。<br>
対象がキルした相手がキルされた瞬間に発動するものであった場合、対象にその効果が反映されます。<br>
普通のキルを行うことはできません。<br>

### SerialKiller/シリアルキラー

陣営 : インポスター<br>
判定 : シェイプシフター<br>

キルクールが短いインポスターです。<br>
その代わり、時間が来るまでにキルをしないと自爆してしまいます。<br>

#### 設定

| 設定名                          |
| ------------------------------- |
| シリアルキラーのキルクール(s)   |
| シリアルキラーが自爆する時間(s) |

### ShapeMaster/シェイプマスター

陣営 : インポスター<br>
判定 : シェイプシフター<br>

シェイプマスターは変身後のクールダウンを無視し、再度変身することができます。<br>
通常では 10 秒しか変身できませんが、設定によって変身継続時間を変更することができます。<br>

#### 設定

| 設定名                            |
| --------------------------------- |
| シェイプマスターの変身可能時間(s) |

### Sniper/スナイパー

陣営 : インポスター<br>
判定 : シェイプシフター<br>

遠距離射撃が可能な役職です。<br>
シェイプシフトした地点から解除した地点への延長線上にいる対象をキルします。<br>
射線上のクルーには射撃音が聞こえます。<br>
弾丸を打ち切るまで通常キルは出来ません。<br>

精密射撃モードOFF<BR>
![off](https://user-images.githubusercontent.com/96226646/172194283-5482db76-faab-4185-9898-ac741b132112.png)<br>
精密射撃モードON<BR>
![on](https://user-images.githubusercontent.com/96226646/172194317-6c47b711-a870-4ec0-9062-2abbf953418b.png)<br>

#### 設定

| 設定名                   |
| ------------------------ |
| スナイパーの所持弾数     |
| スナイパー精密射撃モード |

### TimeThief/タイムシーフ

陣営 : インポスター<br>
判定 : インポスター<br>

プレイヤーをキルすると、会議時間が減少します。<br>
タイムシーフが追放または殺されると、失われた会議時間が戻ってきます。<br>

#### 設定

| 設定名              |
| ------------------- |
| 減少する会議時間(s) |
| 投票時間の下限(s)   |

### Vampire/ヴァンパイア

陣営 : インポスター<br>
判定 : インポスター<br>

キルボタンを押してから一定時間経って実際にキルが発生する役職です。<br>
キルをしたときのテレポートは発生しません。<br>
また、キルボタンを押してから設定された時間が経つまでに会議が始まるとその瞬間にキルが発生します。<br>
しかし、[ベイト](#Bait/ベイト)をキルした場合のみ通常のキルとなり、強制的に通報させられます。<br>

#### 設定

| 設定名                          |
| ------------------------------- |
| ヴァンパイアのキルまでの時間(s) |

### Warlock/ウォーロック

陣営 : インポスター<br>
判定 : シェイプシフター<br>

ウォーロックが変身する前にキルすると相手に呪いがかかります。<br>
そして次変身すると、呪った人に一番近い人が死にます。<br>
呪いキルの成功または会議を挟むと呪いはリセットされます。<br>

### Witch/魔女

陣営 : インポスター<br>
判定 : インポスター<br>

キルボタンを押すとキルモードとスペルモードが入れ替わり、スペルモードの時にキルボタンを押すとその対象に魔術をかけることができる役職です <br>
魔術をかけられたプレイヤーには会議で特殊なマークが付き、その会議中に魔女を追放できなければ死亡してしまいます。<br>

### Mafia/マフィア

陣営 : インポスター<br>
判定 : シェイプシフター<br>

初期状態で通気口やサボタージュ、変身は可能ですが、キルをすることはできません。<br>
マフィアではないインポスターが全員死亡すると、マフィアもキルすることができるようになります。<br>
キルができない状態でもキルボタンはありますが、キルをすることはできません。<br>
キルが可能になった後でも変身は継続して行うことができます。<br>

### Madmate/マッドメイト

陣営 : インポスター<br>
判定 : エンジニア<br>

インポスター陣営に属しますが、マッドメイトからはインポスターが誰なのかはわかりません。<br>
インポスターからもマッドメイトが誰なのかはわかりません。<br>
キルやサボタージュはできませんが、通気口に入ることができます。<br>

### MadGuardian/マッドガーディアン

陣営 : インポスター<br>
判定 : クルーメイト<br>

インポスター陣営に属しますが、マッドガーディアンからはインポスターが誰なのかはわかりません。<br>
インポスターからもマッドガーディアンが誰なのかはわかりません。<br>
しかし、自身のタスクを全て完了させるとキルされなくなります。<br>
キルやサボタージュはできず、通気口に入ることもできません。<br>

#### 設定

| 設定名                                                   |
| -------------------------------------------------------- |
| マッドガーディアンが自身の割れたバリアを見ることができる |

### MadSnitch/マッドスニッチ

陣営 : インポスター<br>
判定 : クルーメイトorエンジニア<br>

インポスター陣営に属しますが、マッドスニッチからはインポスターが誰なのかはわかりません。<br>
インポスターからもマッドスニッチが誰なのかはわかりません。<br>
タスクを全て完了させるとマッドスニッチからインポスターを認識できるようになります。<br>

#### 設定

| 設定名                         |
| ------------------------------ |
| マッドスニッチがベントを使える |
| マッドスニッチのタスク数       |

### SidekickMadmate/サイドキックマッドメイト

陣営 : インポスター<br>
判定 : 変化前の役職<br>

この役職はシェイプシフトの能力を持つ役職がシェイプシフトした際に作られます。<br>
インポスター陣営に属しますが、サイドキックマッドメイトからはインポスターが誰なのかはわかりません。<br>
インポスターからもサイドキックマッドメイトが誰なのかはわかりません。<br>


また、マッドメイト系役職共通の設定があります。

| 設定名                                         |
| ---------------------------------------------- |
| マッドメイト系役職が停電を直すことができる     |
| マッドメイト系役職が通信障害を直すことができる |
| マッドメイト系役職の視界がインポスターと同じ   |
| マッドメイト系役職のベントクールダウン         |
| マッドメイト系役職のベント内での最大時間       |

### Watcher/ウォッチャー

陣営 : インポスター or クルーメイト<br>
判定 : インポスター or クルーメイト<br>

ウォッチャーは会議中に全員の投票先を見ることができます。<br>

#### 設定

| 設定名                          |
| ------------------------------- |
| イビルウォッチャーになる確率(%) |

### AssassinAndMarin/アサシンとマーリン

陣営 : インポスター, クルーメイト<br>
判定 : インポスター, クルーメイト<br>

#### アサシン

陣営 : インポスター<br>
判定 : インポスター<br>
追加勝利条件 : 「アサシン会議」でマーリンを当てる<br>

- インポスター陣営に新しい勝利条件を追加する役職です。<br>
マーリンと対になる役職です。<br>
アサシンがキル及び追放されかけると、「アサシン会議」が開かれます。<br>
アサシン会議は、アサシンがプレイヤーを一人指名するまで終わることはありません。<br>
プレイヤーの指名方法はチャットです。クイックチャットでプレイヤー名を選択すると良いです。<br>
アサシン会議でアサシンは吊られます。<br>
アサシン会議後は通常通り試合続行です。<br>
#### マーリン

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

- インポスター全員が始めからわかる役職です。<br>
アサシンと対になる役職です。<br>
アサシン会議でアサシンに指名されると無条件敗北です。<br>
タスクはありません。

### Bait/ベイト

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

キルされたときに、自分をキルしたプレイヤーに強制的に自分の死体を通報させることができる役職です。<br>

### Dictator/ディクテーター

陣営 ：クルーメイト<br>
判定 ：クルーメイト<br>

会議中に誰かに投票をすると、会議を強制終了させて投票先を吊る事ができます。<br>
投票したタイミングでディクテーターは死亡します。<br>

### Doctor/ドクター

陣営 : クルーメイト<br>
判定 : 科学者<br>

ドクターはプレイヤーの死因を知ることができ、遠隔でバイタルをみることができます。<br>

#### 設定
| 設定名                                                       |
| ------------------------------------------------------------ |
| ドクターがタスクを終わらせたときにセットされるバイタルの秒数 |

### Lighter/ライター

陣営 ：クルーメイト<br>
判定 ：クルーメイト<br>

タスクを完了させると、自分の視界が広がり、停電の視界減少の影響を受けなくなります。<br>

### Mayor/メイヤー

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

メイヤーは票を複数持っており、まとめて一人のプレイヤーまたはスキップに入れることができます。<br>

#### 設定

| 設定名                                 |
| -------------------------------------- |
| メイヤーの追加投票数                   |
| メイヤーがポータブルボタンを持っている |
| メイヤーが使えるボタンの回数           |

### SabotageMaster/サボタージュマスター

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

サボタージュマスターはサボタージュを早く直すことができます。
原子炉メルトダウンや酸素妨害、MIRA HQ の通信妨害は片方を修理すれば両方が直ります。<br>
停電は 1 箇所のレバーに触れると全て直ります。<br>
Polus や The Airship のドアを開けるとその部屋の全てのドアが開きます。<br>

#### 設定

| 設定名                                                                         |
| ------------------------------------------------------------------------------ |
| サボタージュマスターがサボタージュに対して能力を使用できる回数(ドア閉鎖は除く) |
| サボタージュマスターが 1 度に複数のドアを開けることを許可する                  |
| サボタージュマスターが原子炉メルトダウンに対して能力を使える                   |
| サボタージュマスターが酸素妨害に対して能力を使える                             |
| サボタージュマスターが MIRA HQ の通信妨害に対して能力を使える                  |
| サボタージュマスターが停電に対して能力を使える                                 |

### Sheriff/シェリフ

陣営 : クルーメイト<br>
判定 : インポスター(ホストのみクルーメイト)<br>

シェリフは人外をキルすることができます。<br>
しかし、クルーメイトをキルした場合、自分が死亡してしまいます。<br>
タスクはありません。<br>

#### 設定

| 設定名                                                              |
| ------------------------------------------------------------------- |
| シェリフが[アーソニスト](#Arsonist/アーソニスト)をキルできる        |
| シェリフが[マッドメイト](#Madmate/マッドメイト)をキルできる         |
| シェリフが[ジェスター](#Jester/ジェスター)をキルできる              |
| シェリフが[テロリスト](#Terrorist/テロリスト)をキルできる           |
| シェリフが[オポチュニスト](#Opportunist/オポチュニスト)をキルできる |
| シェリフが[エゴイスト](#Egoist/エゴイスト)をキルできる              |
| シェリフがクルーをそのままキルできる                                |
| シェリフのキル可能回数                                              |

### Snitch/スニッチ

陣営 : クルーメイト<br>
判定 : クルーメイト<br>

スニッチはタスクを完了させるとキル可能人外の名前の色が変化し、矢印で方角がわかります。<br>
しかし、スニッチのタスクが少なくなると人外に通知されます。

#### 設定

| 設定名                                       |
| -------------------------------------------- |
| 矢印の色で陣営がわかる                       |
| 第三陣営のキル可能役職を見つけることが出来る |

### SpeedBooster/スピードブースター

陣営 ：クルーメイト<br>
判定 ：クルーメイト<br>

タスクを完了させると、生存しているランダムなプレイヤーの速度を上げさせます。<br>

#### 設定

| 設定名                 |
| ---------------------- |
| スピードアップ時の速さ |

### Trapper/トラッパー

陣営 ：クルーメイト<br>
判定 ：クルーメイト<br>

キルされると、キルした人を数秒間移動不可にします。<br>

#### 設定

| 設定名           |
| ---------------- |
| 移動を封じる時間 |

### Arsonist/アーソニスト

陣営 : 第三<br>
判定 : インポスター<br>
勝利条件 : 生存者全員にオイルをかけること

キルボタンを押して、一定時間近くに居ると、相手にオイルが塗れます。<br>
生存者全員にオイルを塗り、ベントに入ると単独勝利します。それ以外では敗北します。<br>

#### 設定

| 設定名                   |
| ------------------------ |
| 塗りつけるのに必要な時間 |
| 塗るためのクールダウン   |

### Egoist/エゴイスト

陣営 : 第三<br>
判定 : シェイプシフター<br>
勝利条件 : インポスター全滅後、インポスターの勝利条件を達成する<br>

インポスターはエゴイストを認識しています。<br>
エゴイストもインポスターを認識しています。<br>
インポスターとエゴイストは切りあうことができません。<br>
他のインポスターが全滅すると勝利します。<br>
エゴイストが勝利するとインポスターは敗北となります。<br>

敗北条件は以下の通りです。<br>

1.エゴイストが死亡する<br> 2.味方が残っている状態でインポスター勝利をする<br> 3.他の第三陣営が勝利する<br>

### Executioner/エクスキューショナー

陣営 : 第三<br>
判定 : クルーメイト<br>
勝利条件 : ターゲットが投票で追放されること<br>

ターゲットに対してこちらからのみ視認できるダイヤのマークがついています。<br>
投票でダイヤが付いている人を追放すれば単独勝利します。<br>
対象がキルされた場合は役職が変化します。<br>
ターゲットがジェスターの場合は追加勝利します。<br>

#### 設定

| 設定名                                             |
| -------------------------------------------------- |
| ｴｸｽｷｭｰｼｮﾅｰがインポスターもターゲットにできる       |
| ｴｸｽｷｭｰｼｮﾅｰのターゲットがキルされた後に変化する役職 |

### Jester/ジェスター

陣営 : 第三<br>
判定 : クルーメイト<br>
勝利条件 : 投票で追放されること。<br>

投票で追放されたときに単独勝利となる第三陣営の役職です。<br>
追放されずにゲームが終了するか、キルされると敗北となります。<br>

### Opportunist/オポチュニスト

陣営 : 第三<br>
判定 : クルーメイト<br>
勝利条件 : いずれかの陣営が勝利したときに生き残っていること。<br>

ゲーム終了時に生き残っていれば追加勝利となる第三陣営の役職です。<br>
タスクはありません。<br>

### SchrodingerCat/シュレディンガーの猫

陣営 : 第三<br>
判定 : クルーメイト<br>
勝利条件 : なし<br>

デフォルトでは勝利条件を持たず、条件を満たすと初めて勝利条件を持ちます。<br>

1.インポスターにキルされるとキルを防いでインポスター陣営となる<br> 2.シェリフにキルされるとキルを防いでクルー陣営となる<br> 3.第三陣営にキルされるとキルを防いで第三陣営となる<br> 4.追放された場合は役職が変化せず、そのまま勝利条件が変わらず死亡する<br> 5.ウォーロックの能力でキルされると、そのまま勝利条件が変わらず死亡する<br> 6.自殺系キル(ヴァンパイア除く)でキルされると、そのまま勝利条件が変わらず死亡する<br>

また、全シュレディンガーの猫共通でタスクがありません。

#### 設定

| 設定名                                           |
| ------------------------------------------------ |
| 役職変化前であれば、クルー陣営と勝利できる       |
| シュレディンガーの猫が吊られた際、陣営が変化する |

### Terrorist/テロリスト

陣営 : 第三<br>
判定 : エンジニア<br>
勝利条件 : 全てのタスクを完了させた状態で死亡すること。<br>

自身のタスクを全て完了させた状態で死亡したときに単独勝利となる第三陣営の役職です。<br>
タスクを完了させずに死亡したり、死亡しないまま試合が終了すると敗北となります。<br>

## 属性

### LastImpostor/ラストインポスター

最後のインポスターに付与される属性です。<br>
ヴァンパイア、バウンティハンター、シリアルキラーには付与されません。<br>

| 設定名                         |
| ------------------------------ |
| ラストインポスターのキルクール |

### Lovers/恋人

陣営 : 第三<br>
判定 : -<br>
勝利条件 : 恋人が2人共生き残っている状態で試合が終了すること。全クルーのタスク終了時は生き残っていても敗北。<br>

全プレイヤーの中から2人配役されます。(他の役職に重複)<br>
クルー陣営のタスクを持つ役職が恋人になった場合、タスクはなくなります。<br>
お互いの名前の後ろにハートマークが付きます。<br>
片方が死んだらもう片方も後追いで死亡します。<br>
投票で恋人が死んだ場合はもう片方も死亡し、通報不可能の死体になります。<br>

役職重複例：<br>
・テロリスト恋人:タスク持ち、タスク完了して死亡すればテロリストとして勝利。<br>
・マッドスニッチ恋人：タスク持ち、タスク完了すればインポスターが分かる。<br>
・スニッチ恋人：タスク無し、インポスターが分からないままになる。<br>
・シェリフ恋人：通常通りインポスター等をキルことが出来る。重複元の役職によってキルできるかどうか決まる。(インポスター恋人 キル可能.クルーメイト恋人 キル不可能)<br>
・オポチュニスト恋人：生き残れば勝利。<br>
・ジェスター恋人：ジェスター恋人が追放されればジェスターとして勝利。恋人が投票で追放された場合はジェスター恋人は敗北。<br>
・ベイト恋人：恋人がキルされてベイト恋人が後追い死亡した時は、恋人がベイト恋人を即通報を行う。<br>

## SabotageTimeControl/サボタージュの時間制御

一部サボタージュの制限時間を変更することができます。

| 設定名                         |
| ------------------------------ |
| ポーラスのリアクター制限時間   |
| エアシップのリアクター制限時間 |
## モード

### DisableTasks/タスクを無効化する

特定のタスクを無効化することができます。<br>

| 設定名                             |
| ---------------------------------- |
| 原子炉起動タスクを無効化する       |
| 医務室のスキャンタスクを無効化する |
| カードタスクを無効化する           |
| 金庫タスクを無効化する             |
| ダウンロードタスクを無効化する     |

### HideAndSeek/かくれんぼモード

#### クルーメイト陣営(青色)勝利条件

全てのタスクを完了させること。<br>
※幽霊のタスクはカウントされません。<br>

#### インポスター陣営(赤色)勝利条件

全てのクルーメイトをキルすること。<br>
※クルーメイトとインポスターが同数であってもクルーメイトが全滅していないと試合は終わりません。<br>

#### 狐(紫色)勝利条件

トロールを除くいずれかの陣営が勝利したときに生き残っていること。<br>

#### トロール(緑色)勝利条件

インポスターにキルされること。<br>

#### 禁止事項

・サボタージュ<br>
・アドミン<br>
・カメラ<br>
・幽霊が生存者に位置情報を伝える行為<br>
・待ち伏せ(クルーメイトのタスク勝利が不可能となる可能性があるため。)<br>

#### できないこと

・死体の通報<br>
・緊急会議ボタン<br>
・サボタージュ<br>

#### 設定

| 設定名                     |
| -------------------------- |
| ドア閉鎖を許可する         |
| インポスターの待機時間(秒) |
| 装飾品を禁止する           |
| 通気口の使用を禁止する     |

### NoGameEnd

#### クルーメイト陣営勝利条件

なし<br>

#### インポスター陣営勝利条件

なし<br>

#### 禁止事項

なし<br>

#### できないこと

ホストの SHIFT+L+Enter 以外でのゲーム終了。<br>

勝利判定が存在しないデバッグ用のモードです。<br>

### RandomMapsMode/ランダムマップモード

ランダムにマップが変わるモードです。<br>

#### 設定

| 設定名             |
| ------------------ |
| The Skeld を追加   |
| MIRA HQ を追加     |
| Polus を追加       |
| The Airship を追加 |

### SyncButtonMode/ボタン回数同期モード

プレイヤー全員のボタン回数が同期されているモードです。<br>

#### 設定

| 設定名                 |
| ---------------------- |
| 合計ボタン使用可能回数 |

## OtherSettings/その他の設定

| 設定名     |
| ---------- |
| スキップ時 |
| 無投票時   |

#### クライアント設定

## Hide Game Codes/コード隠し

有効化することで、ロビーコードを非表示にすることができます。

コンフィグファイル(BepInEx\config\com.emptybottle.townofhost.cfg)の`Hide Game Code Name`を書き換えることによって、HideCodes を有効にしたときに好きな文字を表示させることができます。
また、`Hide Game Code Color`を書き換えることによって文字の色も好きなように変更できます。

## Force Japanese/強制日本語化

有効化することで言語設定にかかわらず、メニューを強制的に日本語にします。

## Japanese Role Name/役職名日本語化

有効化することで、役職名を日本語で表示させることができます。
クライアントの言語を英語にしている場合、`Force Japanese`を有効にしていないとこの設定は意味のないものとなります。

## 参考など

[バウンティーハンター](#BountyHunter/バンティーハンター)や[マフィア](#Mafia/マフィア)、[ヴァンパイア](#Vampire/ヴァンパイア)、[魔女](#Witch/魔女)、[ベイト](#Bait/ベイト)、[メイヤー](#Mayor/メイヤー)、[シェリフ](#Sheriff/シェリフ)、[スニッチ](#Snitch/スニッチ)、[ライター](#Lighter/ライター)の役職と Mod の作成方法の参考 : https://github.com/Eisbison/TheOtherRoles<br>
[オポチュニスト](#Opportunist/オポチュニスト)、[ウォッチャー](#Watcher/ウォッチャー)の役職 : https://github.com/yukinogatari/TheOtherRoles-GM<br>
[シュレディンガーの猫](#SchrodingerCat/シュレディンガーの猫)の役職 : https://github.com/haoming37/TheOtherRoles-GM-Haoming<br>
[ドクター](#Doctor/ドクター) の役職 : https://github.com/Dolly1016/Nebula<br>
[アサシンとマーリン](#AssassinAndMarin/アサシンとマーリン) のアイデア元 : [Extreme Roles](https://github.com/yukieiji/ExtremeRoles)<br>
[ジェスター](#Jester/ジェスター)(てるてる)と[マッドメイト](#Madmate/マッドメイト)の役職 : https://au.libhalt.net<br>
[テロリスト](#Terrorist/テロリスト)(Trickstar + Joker) : https://github.com/MengTube/Foolers-Mod<br>

作者の Twitter : https://twitter.com/XenonBottle<br>
