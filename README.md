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
1. https://www.spatial.io にアクセスし、画面右上の「LogIn」をクリックする。
2. 「Google」「Apple」「Email」「Microsoft」のいずれかをクリックしてログイン。Spatialアカウントの作成を行う。アカウント作成後、ログインした状態になる。
#### Step1-1b.既にSpatialアカウントを持っている場合
1. https://www.spatial.io にアクセスし、画面右上の「LogIn」をクリックする。
2. 「Google」「Apple」「Email」「Microsoft」のいずれかをクリックしてログイン。画面右上に、自分のアバターのアイコンが表示される。

### Step2.Spatialクリエイターツールキットセットアップ
Spatialで指定するUnityのバージョンのインストールと、Spatialクリエイターツールキットを含むスターターテンプレートによるUnityプロジェクトを立ち上げるところまで。
#### Step2-1.Unity Hubの用意
既にUnity Hubをインストール済みの場合は、Step2-2へ。
##### Step2-1-1.Unity Hubのインストール
1. https://unity.com/ja/pricing#plans-student-and-hobbyist にアクセス。個人利用の無料版を使うので、「個人」の「始める」をクリック。
2. 「Unity Hub」をダウンロードする。ほとんどの人は、「Windows用ダウンロード」または「Mac用ダウンロード」をクリックするはず。UbuntuなどLinux関係は「Linux用ダウンロード」をクリック。
3. ダウンロードしたファイルを使い、Unity Hubをインストール。画面の指示に従ってインストール作業を実施。インストール完了後、Unity Hubを起動。
4. 「Welcome to Unity Hub」が表示される。
##### Step2-1-2.Unity IDの作成
1. 「Create Account」をクリックする。
2. 「Create a Unity ID」が表示される。画面指示に従ってUnity IDを作成する。メールアドレス、パスワード、ユーザー名、フルネーム、各種利用規約へのチェック、私はロボットではありませんにチェックし、「Create a Unity ID」をクリックする。
3. 「Confirm your Email」が表示される。
4. 「Confirm your email address」という件名のメールが届くので、メール本文中のLink to confirm emailをクリックする。
5. 「Need to verify to continue」が表示される。私はロボットではありませんにチェックを入れ、「Verify」をクリックする。
6. 「Confirm your Email」が表示されている画面に戻り、「Continue」をクリックする。
7. 「My Account Settings」が表示される。これで、Unity IDは作成できた。
##### Step2-1-3.Unity IDを持っている、または作成後
1. 「Unity Hub」の画面で「Sign in」をクリックする。
2. Webブラウザで、このサイトは、Unity Hubを開こうとしていますと表示されるので、「開く」をクリックする。
3. 「Install Unity Editor」が表示される。Spatial指定のバージョンのUnityをインストールするため、画面右下の「Skip installation」をクリックする。
4. 「No activate licences」が表示されているはず。表示されている場合は、「Manage licences」をクリックする。
5. 「Licences」画面となる。「Add」をクリック。
6. 「Get a free personal licences」をクリック。
7. 「Agree and get personal edition licence」をクリック。
8. 「Licences」画面に、「Personal」が追加される。これで無料利用ができる。
#### Step2-2. Spatial指定の「Unity 2021.3.21」のインストール
1. Webブラウザで、https://unity.com/releases/editor/archive にアクセスする。
2. 「Unity 2021.X」タブをクリック
3. 「2021.3.21」を探す
4. 「Unity 2021.3.21」の行で、「Unity Hub」をクリック。
5. 「Unity Hubを開く」をクリック
6. 「Add Module」の「WebGL Build Support」を忘れずにチェックする
7. 「Continue」をクリック
8. 画面指示に従って、「I have read and agree with the above terms and conditions」にチェックを入れて、「Install」ボタンをクリック。
9. 画面指示に従って操作していく。Windows環境では、Visual Studioのインストールが必要になる。これもパソコンに表示される指示に従って操作が必要。
10. 「Unity Hub」の画面に、「Unity 2021.3.21」が表示され、「Install Complete」と表示される。「Unity 2021.3.21」をクリックすると、下図のように表示される。「WebGL Build Support」が入っていればOK。下図は、Windows環境の場合。

![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/456a5543-20c5-40d8-a12f-d3cce5c4e0d1)
#### Step2-3.Spatialクリエイターツールキットを含むスターターテンプレートのダウンロード
1. Webブラウザで、https://docs.spatial.io/installation にアクセス。
2. Starter Template下の「Click here to download the starter template.」をクリックする。
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
#### Step2-5.サンプルプロジェクトを使ったSpatialクリエイターツールキットの動作確認
ゴルフカートを運転できるサンプルプロジェクトを使って、動作確認をします。ゴルフカートを運転できるサンプルプロジェクトをもとに、運転する自動車を変更したり、建物を追加して運転しながら観光するようなコンテンツに発展させても良いでしょう。
##### Step2-5-1.ゴルフカートドライビングの起動
1. 画面左下の「Project」タブで、「Assets」下の「Examples」をダブルクリック。
2. 「Sapce_GolfCourse_Driving」をダブルクリック。
3. 「Scenes」をダブルクリック。
4. 立方体のようなアイコンの「GolfCouseDriving.unity」をダブルクリック。
5. 「GolfCouseDriving」のScene（シーン）が表示される。シーンでゲーム画面を作ったりする。
6. 画面右上の「Test Active Scene」をクリック。
7. 初回は、「Sandbox upload failed」が表示される。「OK」をクリック。Spatialの認証が必要であるが、認証が行われていないために表示される。
8. 「Spatial Portal」の画面がUnity内に表示される。
9. 「Get Login Token」をクリック。
10. Webブラウザが起動し、Spatialのアカウント画面が表示される。
11. 「Creator Toolkit Access Token」と表示されている場所で、「Copy to Clipboard」をクリック。
12. Unityの画面に戻り、「Spatial Portal」内の「Paste Login Token」をクリック。
13. 「Spatial Portal」内に「Logged In」と表示される。
14. Unityの画面内の「Spatial Portal」を閉じる。「X」を押す。
15. 画面右上の「Test Active Scene」をクリック。
16. 検証環境である「Spatial sandbox」が起動する。

![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/3c1f4d57-1241-409b-9d9c-fcc5221fade4)

##### Step2-5-2.ゴルフカートドライビングをSpatial sandboxで操作してみる
- アバターを操作して、ゴルフカートの側（そば）に移動します。「Drive」と表示されるので「F」キーを押すと運転手席に座ります。
- 「W」キーで前進、「S」キーで後退です。
- 「W」キーを押しながら「A」キーで左折、「D」キーで右折ができます。「W」キーの代わりに「S」キーを押しながらであれば、「A」キーで左バック、「D」キーで右バックができます。
- 運転を終える時は、「F」キーを押します。
- 再び運転するときは「Sit」が表示されていれば「F」キーを押せば、運転を再開できます。
- 自動車から離れた場合は、再び自動車の近くで「Drive」が表示されるので、「F」キーを押すことで運転ができます。

![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/ba9cd8fb-b8d2-48d6-ae8f-b702e6ac6e56)

##### Step2-5-3.ゴルフカートドライビングをSpatial sandboxを閉じる
Webbブラウザで、Spatial sandboxのタブを閉じます。

### Step3. Unity Aseet Storeの利用とアセットインポート
1. Webブラウザで、Unityアセットストアにアクセスします。https://assetstore.unity.com/ja?locale=ja-JP
2. 

