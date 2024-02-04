# 実施概要
ポスター記載の「接続先情報・講義ノート」のURLは、現在表示中のGithubのコンテンツです。
![2024年2月8日メタバースゲームクリエイターワークショップちらし](https://github.com/kolinz/metavserse-edu-workshop/blob/main/leaflet-metaversecreatorworkshop-20240208.png)
# 接続先情報
## 参加方法
Zoom
### 接続先(Zoom)
荒らし防止のため、直前に公開します。
# 講義ノート
## 講義内容
| 学習項目  | 実施方法 |
| ------------- | ------------- |
| 1. メタバースプラットフォーム「Spatial」準備  | 座学。事前準備しておく。  |
| 2. Spatialクリエイターツールキットセットアップ  | 座学。事前準備しておく。  |
| 3. Unity Aseet Storeの利用とアセットインポート  | 座学。事前準備しておく。  |
| 4. 走らせる乗り物のカスタマイズ  | ハンズオン  |
| 5. 運転して走ることができるようにする設定の解説。  | ハンズオン  |
| 6. テスト環境で動作確認方法の解説  | ハンズオン  |
| 7. メタバースで公開する方法の解説  | ハンズオン  |
| 8. メタバースに画像や建物等の展示方法解説  | ハンズオン  |

## 事前準備
当日に実際に自動車がメタバース内を動くようにしたい参加者は、スムーズに進めるために以下の準備を実施して参加してください。視聴だけの場合は事前準備は不要です。

### Step1.メタバースプラットフォーム「Spatial」準備
#### Step1-1a.Spatialアカウントを持っていない場合は、メタバースゲームプラットフォームSpatialのアカウント作成が必要
1. https://www.spatial.io　にアクセスし、画面右上の「LogIn」をクリックする。
2. 「Google」「Apple」「Email」「Microsoft」のいずれかをクリックしてログイン。Spatialアカウントの作成を行う。アカウント作成後、ログインした状態になる。
#### Step1-1b.既にSpatialアカウントを持っている場合ログイン
1. https://www.spatial.io　にアクセスし、画面右上の「LogIn」をクリックする。
2. 「Google」「Apple」「Email」「Microsoft」のいずれかをクリックしてログイン。画面右上に、自分のアバターのアイコンが表示される。

### Step2.Spatialクリエイターツールキットセットアップ
Spatialで指定するUnityのバージョンのインストールと、Spatialクリエイターツールキットを含むスターターテンプレートによるUnityプロジェクトを立ち上げるところまで。
#### Step2-1. Unity Hubの用意
既にUnity Hubをインストール済みの場合は、Step2-2へ。
##### Unity Hubをインストールしていない人（Unityをまだ使っていない人）
1. https://unity.com/ja/pricing#plans-student-and-hobbyist にアクセス。個人利用の無料版を使うので、「個人」の「始める」をクリック。
2. 「Unity Hub」をダウンロードする。ほとんどの人は、「Windows用ダウンロード」または「Mac用ダウンロード」をクリックするはず。UbuntuなどLinux関係は「Linux用ダウンロード」をクリック。
3. ダウンロードしたファイルを使い、Unity Hubをインストール。画面の指示に従ってインストール作業を実施。インストール完了後、Unity Hubを起動。
5. 「Welcome to Unity Hub」画面が表示される。
##### Unity IDを持っていない場合
「Create Account」をクリックして、画面指示に従ってUnity IDを作成し、Unity Hubで、「Projects」や「Installs」といったメニューが表示される状態にする。
##### Unity IDを持っている場合
「Sign in」をクリックして、ログインする。Unity Hubで、「Projects」や「Installs」といったメニューが表示される状態にする。
#### Step2-2. Spatial指定の「Unity 2021.3.21」のインストール
1. Webブラウザで、https://unity.com/releases/editor/archive にアクセスする。
2. 「Unity 2021.X」タブをクリック
3. 「2021.3.21」を探す
4. 「Unity 2021.3.21」の行で、「Unity Hub」をクリック。
5. 「Unity Hubを開く」をクリック
6. 「Add Module」の「WebGL Build Support」を忘れずにチェックする
7. 「Continue」をクリック
8. 画面指示に従って、各種利用規約への同意などの操作を行う。チェックして「Install」ボタンをクリック。画面指示に従って操作していく。Windows環境では、Visual Studioのインストールが必要になる。これもパソコンに表示される指示に従って操作が必要。
9. 「Unity Hub」の画面に、「Unity 2021.3.21」が表示され、「Install Complete」と表示される。「Unity 2021.3.21」をクリックすると、下図のように表示される。「WebGL Build Support」が入っていればOK。下図は、Windows環境の場合。

![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/456a5543-20c5-40d8-a12f-d3cce5c4e0d1)

#### Step2-3.Spatialクリエイターツールキットを含むスターターテンプレートのダウンロード
1. Webブラウザで、https://docs.spatial.io/installation にアクセス。
2. 「Click here to download the starter template.」をクリックする。
3. 「spatial-unity-starter-template-main.zip」のダウンロードを開始する。
#### Step2-4.Spatialクリエイターツールキットを含むスターターテンプレートのインポート
1. ダウンロードした「「spatial-unity-starter-template-main.zip」を任意の場所に展開（解凍）する。ドキュメント（書類）フォルダなど、覚えやすい場所が良い。
2. 「spatial-unity-starter-template-main」が展開される。
3. Unity Hubの画面に切り替える。
4. 「Projects」の画面で、「Add」をクリック。
5. 展開（解凍）した「spatial-unity-starter-template-main」フォルダを選び、「Open」をクリック。
6. 「Unity Package Manager」により、Spatialクリエイターツールキットを含むスターターテンプレートのインポートが始まる。
7. Unityが起動する。
8. 「Upgrade to latest version?」のメッセージが表示される。
9. メッセージに「A new veersion of Spatial SDK is available...」と表示されている場合は、「Yes」をクリック。
10. 「Upgrade successful」を表示されるので、「OK」をクリック。
11. 「Unity Editor Update Check」の画面が表示された場合は、「Check for Updates」のチェックを外す。その後、「Skip new version」をクリック。
12. Unityで作業ができるようになる。

以後、Unity Hubの「Projects」で、「spatial-unity-starter-template-main」をクリックすれば、Spatial向けのUnity作業ができるようになる。

### Step3. Unity Aseet Storeの利用とアセットインポート


