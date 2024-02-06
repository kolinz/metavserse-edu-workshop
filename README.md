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
9. 画面指示に従って操作していく。Windows環境の場合は、Visual Studio Communityのインストールも必要になる。しばらくすると「Visual Studio Installer」が起動するので、Visual Studio Communityをインストールする。
10. 「Visual Studioにサインイン」が表示される。「後で行う。」をクリック。Visual Studio自体は閉じてかまわない。
11. 「Unity Hub」の画面に、「Unity 2021.3.21」が表示され、「Install Complete」と表示される。「Unity 2021.3.21」をクリックすると、下図のように表示される。「WebGL Build Support」が入っていればOK。下図は、Windows環境の場合。

![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/456a5543-20c5-40d8-a12f-d3cce5c4e0d1)
#### Step2-3.Spatialクリエイターツールキットを含むスターターテンプレートのダウンロード
1. Webブラウザで、https://docs.spatial.io/installation にアクセス。
2. Starter Template下の「Click here to download the starter template.」をクリックする。
3. 「spatial-unity-starter-template-main.zip」のダウンロードを開始する。
#### Step2-4.Spatialクリエイターツールキットを含むスターターテンプレートのインポート
1. ダウンロードした「spatial-unity-starter-template-main.zip」を任意の場所に展開（解凍）する。ドキュメント（書類）フォルダなど、覚えやすい場所が良い。
2. 「spatial-unity-starter-template-main」が展開される。
3. Unity Hubの画面に切り替える。
4. 「Projects」の画面で、「Add」をクリック。
5. 展開（解凍）した「spatial-unity-starter-template-main」フォルダを選び、ダブルクリック。
6. 「Open」をクリック。
7. 「Unity Package Manager」により、Spatialクリエイターツールキットを含むスターターテンプレートのインポートが始まる。
8. Unityが起動する。
9. 「Upgrade to latest version?」のメッセージが表示される。メッセージに「A new veersion of Spatial SDK is available.Would you like to upgrade now ?」と表示されている場合は、「Yes」をクリック。
11. 「Upgrade successful」を表示されるので、「OK」をクリック。
12. 「Unity Editor Update Check」の画面が表示された場合は、「Check for Updates」のチェックを外す。その後、「Skip new version」をクリック。
13. Spatialクリエイターツールキットを含むスターターテンプレートがUnityのプロジェクトとなり、Unityで作業ができるようになる。

以後、作業を行う際にはUnity Hubの「Projects」で、「spatial-unity-starter-template-main」をクリックすれば、Spatial向けのUnity作業ができるようになる。
#### Step2-5.サンプルプロジェクトを使ったSpatialクリエイターツールキットの動作確認
ゴルフカートを運転できるサンプルプロジェクトを使って、動作確認をします。ゴルフカートを運転できるサンプルプロジェクトをもとに、運転する自動車を変更したり、建物を追加して運転しながら観光するようなコンテンツに発展させても良いでしょう。
![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/9e57f63d-78ad-4909-b7a4-2116c9f72e43)

##### Step2-5-1.ゴルフカートドライビングの起動
1. 画面左下の「Project」タブで、「Assets」下の「Examples」をクリック。
2. 「Sapce_GolfCourse_Driving」をダブルクリック。
3. 「Scenes」をダブルクリック。
4. 立方体のようなアイコンの「GolfCouseDriving.unity」をダブルクリック。
5. 「GolfCouseDriving」のScene（シーン）が表示される。シーンでゲーム画面を作ったりする。
6. 画面右上の「Test Active Scene」をクリック。
7. 初回は、「Sandbox upload failed」が表示される。「OK」をクリック。Spatialの認証が必要であるが、認証が行われていないために表示される。
8. 「Spatial Portal」の画面がUnity内に表示される。
9. 「Get Login Token」をクリック。
10. Webブラウザが起動し、Spatialのアカウント画面が表示される。
11. 「Your Account」画面に「Creator Toolkit Access Token」と表示されている場所で、「Copy to Clipboard」をクリック。
12. Unityの画面に戻り、「Spatial Portal」内の「Paste Login Token」をクリック。
13. 「Spatial Portal」内に「Logged In」と表示される。
14. Unityの画面内の「Spatial Portal」を閉じる。「X」を押す。
15. 画面右上の「Test Active Scene」をクリック。
16. 検証環境である「Spatial sandbox」が起動する。

![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/3c1f4d57-1241-409b-9d9c-fcc5221fade4)

##### Step2-5-2.ゴルフカートドライビングをSpatial sandboxで操作してみる
- アバターを操作して、ゴルフカートの運転手席の側（そば）に移動します。「Drive」と表示されるので「F」キーを押すと運転が可能になる。
- 「W」キーで前進、「S」キーで後退。
- 「W」キーを押しながら「A」キーで左折、「D」キーで右折。「W」キーの代わりに「S」キーを押しながらであれば、「A」キーで左バック、「D」キーで右バック。
- 運転を終える時は、「Exit」と表示されている状態で「F」キーを押す。運転手席に移動すれば「Drive」と表示され、「F」キーを押すことで運転が可能になる。
- 運転手席以外では、「Sit」と表示されている状態で「F」キーを押すことで席に座ることができる。
- 自動車から離れた場合は、再び自動車の運転手席付近で「Drive」が表示されるので、「F」キーを押すことで運転ができる。

![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/ba9cd8fb-b8d2-48d6-ae8f-b702e6ac6e56)

##### Step2-5-3.ゴルフカートドライビングをSpatial sandboxを閉じる
Webbブラウザで、Spatial sandboxのタブを閉じます。

### Step3. Unity Aseet Storeの利用とアセットインポート
Gaz 66というミリタリートラックの例に、Unityアセットストアから探し、インポートするまでの手順です。Unityアセットストア経由で、建物なども入手できます。
#### Step3-1. Unityアセットストアの利用とインポート
1. Webブラウザで、Unityアセットストアにアクセスします。https://assetstore.unity.com/ja?locale=ja-JP
2. Unityアセットストアから、各種素材を入手することができます。いろいろと検索してみましょう。
3. 「Gaz 66」で検索します。表示されたアセットをクリックします。直接アクセスしたい場合は、https://assetstore.unity.com/packages/3d/vehicles/land/gaz-66-91665 にアクセスしてください。
4. 「Add to My Assets」をクリックします。
5. Unity IDでUnityアセットストアにログインしていない場合は、ログインを求められるのでログインします。
6. ログイン後、「Add to My Assets」をクリックします。
7. 「Terms of Service（利用規約）」が表示されるので、「Accept」をクリックします。もとの画面に戻るまで待ちます。
8. 画面右上のハートマークのアイコンの左隣にある「My Assets」のアイコンをクリックします。
9. 「My Assets」画面が表示されます。
10. 「Gaz 66」の行で、「Open in Unity」をクリックします。
11. 「Unity Editorを開く」をクリックします。
12. Unity画面内で「Package Manager」が表示されます。
13. 「Package Manager」内で「Gaz 66」をクリックします。その後、右下の「Download」をクリックします。「Download」が「Re-Download」に表示が変わります。
14. 「Re-Download」の左隣に表示されている「Import」をクリックします。
15. 画面右側に「Import Unity Package」として「Gaz 66」モデル情報が表示されます。右下の「Import」をクリックします。
16. 「Package Manager」を閉じます。
17. 画面左下の「Project」タブで、「Assets」下の「Package」をクリック。
18. 「Gaz 66」と書かれたフォルダをダブルクリック。
19. 「Gaz 66」のモデル（GAZ-66.fbx）を、ゴルフカートの隣にドラッグ&ドロップ。例として下図のように配置。

![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/89e7dd5f-39fd-473c-973e-2de5a337b9dc)
#### Step3-2. モデルのテクスチャ（視覚的効果を与えるための動画や画像ファイル）変更
1. 上の図のような状態から始めます。
2. 「Mterials」フォルダをダブルクリック。
3. 「GZ-66」のマテリアル（GAZ-66.mat）をクリック。
4. 画面右側の「Inspector」タブに「GAZ-66(Materials)」が表示される。
![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/c6794dcd-e2fd-490e-83f2-972a02fbcd57)
5. 「Shader」の「Standard（Specular setup)」をクリックし、「Universal Render Pipeline」下の「Lit」をクリック。
6. 「Shader」が「Universal Render Pipeline/Lit」になる。
![image](https://github.com/kolinz/metavserse-edu-workshop/assets/16685896/c19aa766-1864-46b7-8d59-1547043a2462)
#### Step3-3.Spatial Sandboxで動作確認
画面右上の「Test Active Scene」をクリックし、検証環境のSpatial Sandboxで動作を確認します。この時点では、トラックはゴルフカートの横に置かれているだけで運転はできません。
