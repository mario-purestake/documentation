# チュートリアルと使用例

ここでは私たちのチュートリアルをリストし、あなたが最も簡単で最速の方法で実行するのをサポートするために、様々な例を示します。

## チュートリアル



## SubQueryのサンプルプロジェクト

| 例                                                                                             | 説明                                                                  | トピック                                                                   |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| [extrinsic-finalized-block](https://github.com/subquery/tutorials-extrinsic-finalised-blocks) | ハッシュで問い合わせることができるように、外部テーブルをインデックス化する。                              | __ブロックハンドラ__ 関数の最も単純な例                                                 |
| [block-timestamp](https://github.com/subquery/tutorials-block-timestamp)                      | 最終ブロックのインデックスタイムスタンプを設定する。                                          | 別のシンプルな __コールハンドラ__ 関数                                                 |
| [validator-threshold](https://github.com/subquery/tutorials-validator-threshold)              | インデックスは、バリデータを選択するために必要な最小ステーキング量を指定します。                            | より複雑な __ブロックハンドラ__ 関数は __外部関数__ を `@polkadot/api` で追加のオンチェーンデータを取得します。 |
| [sum-reward](https://github.com/subquery/tutorials-sum-reward)                                | 確定したブロックのイベントから、ステーキングボンド、リワード、スラッシュをインデックス化します。                    | より複雑な __イベントハンドラ__ で __1対多__の リレーションシップを持ちます。                          |
| [entity-relation](https://github.com/subquery/tutorials-entity-relations)                     | アカウント間の残高転送のインデックス化、また、ユーティリティバッチすべてのインデックスは、外部呼び出しの内容を見つけることができます。 | __1対多__ と __多対多__ のリレーションシップと複雑な __外部ハンドリング__                          |
| [kitty](https://github.com/subquery/tutorials-kitty-chain)                                    | 掛金の記録をインデックス化します。                                                   | 複雑な __コールハンドラ__ と __イベントハンドラ__、 __カスタムチェーン__からインデックス付けされたデータ           |