---
description: ※2024/11/18サービス開始予定
---

# UnivaPay連携

サービス開始予定firmeeと株式会社ユニヴァ・ペイキャストの「UnivaPay」との連携により、弁護士業務の売上管理と決済プロセスが大幅に効率化されます。

（注）ご利用にあたってはUnivaPayの審査が必要となります（詳細は[こちら](https://r-agent.upc-app.com/firmeeplan/)）。



## 主な特徴

1. **自動連携**： firmeeで登録した売上情報が**自動的にUnivaPayに反映**されます。
2. **決済リンクの自動生成**： クレジットカード決済および銀行振込用の**リンクが自動で作成**されます。
3. **簡単導入**： 弁護士業務の売上に関して、**クレジットカード決済を容易に導入**できます。
4. **効率的な売上管理**： firmee上での**売上管理が飛躍的に便利**になります。

## firmee特典

* 初期費用・月額手数料： **無料**
* 低価格： クレジットカード決済手数料が**3.20%**（2024年11月現在）



## 具体的な機能

* 事件ファイル連携： firmee内の事件ファイルに紐づく売上情報ごとに決済リンクが生成されます。
* 簡単決済プロセス:：依頼者はリンクをクリックし、所定の手続きを進めるだけで決済が完了します。
* 自動入金登録： 決済完了後、firmee上で自動的に入金日が登録されます。
* 銀行振込の自動確認： 申込ごとにユニークな口座番号が発行され、振込確認・消込が自動化されます。

## 連携の設定方法

１　[こちらのウェブサイト](https://r-agent.upc-app.com/firmeeplan/)からユニヴァ・ペイキャスト社の審査を申請します。審査はインターネットのみで完結します（審査に3〜4週間ほど要します）。\


２　審査が完了すると、「決済サービスの接続設定が完了致しました」というタイトルのメールが届きます。こちらのメールへの問い合わせなどで、以下の管理画面にログインするためのログイン情報を求めてください。

「問い合わせ例：「決済サービスの接続設定が完了致しました」とのメールを受け取りました。マーチャントコンソールへのログイン情報をご連絡ください。」

[https://merchant.univapay.com/login](https://merchant.univapay.com/login)\


３ 　UnivaPayサポートからログイン情報がメールで送られてきます。ログイン情報は以下のようなメールアドレスとパスワードとなります。\


管理画面ログイン情報

ログインID：ご登録のメールアドレス

パスワード：XXXXXXXXXXX



４　管理画面にログインし、マーチャントコンソールからUnivaPayの設定を完了させます。設定の方法は以下のとおりです。なお、登録の際には、シークレットコードとトークンを必ず別ファイルなどに保存してください。

（１）サイドバーにある「アプリトークン」をクリックし、次に新規作成ボタンをクリックします。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcCVZ8xOKLytJ45siwfQb7g2K6EbYZRYkORbQCYZFlchFliXUvoAI9XhuN5N7yHIf9E0gJFscAJn9eAh8eQhcMT5uuDddb2GRE4ThhvbM5xRUhcpUs_9dViEMoM-Sj-TJJrkfnP?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



（２）アプリトークンの追加画面で以下のように設定します

* 「利用店舗を指定する」にチェックを付け、店舗を選択します。店舗は多くの場合、ユーザー様ご自身の弁護士名となっています。
* 「モード」で「本番」をクリックします
* 「ドメイン」の追加ボタンをクリックし、表示された欄にfirmee.comと入力します
* 最後に「作成」ボタンをクリックします\

*

    <figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeW2tsBenhEtK0z6S9AKJ_83eRBwlyo8KFIGmTJCQMabanO5N5tGYap3zYIQGGwLuBLfb8ZoqqzX3j1vRHufEyr_6WdDyhApJHPKmikbw3wm0LVpy9UXWTKGxwH405kh3XnTuCedg?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



（３）トークンとシークレットが表示されるので、シークレットは保存しておいてください。

\


（４）サイドバーにある「店舗」をクリックします。\


<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXe7omWwP4WszKbuSRL2XTHw1Zzq9t91WTJWQAVwtMtZiKcVQ42FtxdiOikjQn7UmlsHTudCMUh16d4GL38EC0hhFmlblfmKdn5PAAJAhYwtCRpplf37rO_ruko8Gj-_qOckmlVe?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

（５）先ほど選択した店舗名をクリックします。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdyK2hr7PsIDAOGfrlXu0cGdZ7YuaDI-eIXq17HNjE0bxOLq6nsZXMzy0B_ikNKU_7echSxeHuUFaZr9-qdMCQ-MWfVu-wuYZx-_bvrgk58yuycR7LIkttMfnT-SzoHrPyRkKjz?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

（６）決済フォーム→リンクフォーム設定に遷移します

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdr5-nyelkVk05j23DuL4h2hnUBgnq1Pb11L-vVGX8O7L5Audw_o1HNiI0MuvzIWP7wxOJByJsdrWG0_P3OthI5S0BcvHhB5f4oRkCY5Ssb7_mQZKz6DjYQXgHfglBIgwpnARHNSg?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

（７）作成をクリックします。設定画面が表示されますので、「アプリトークンID」欄で先程作成したアプリトークンを選択してください。下のスクリーンショットではデモ環境のため（テスト）と表示されていますが、（本番）となっているアプリトークンをご選択ください。

次に、ご希望の設定を登録して保存します。初期設定としては、「決済方法」で「クレジットカード」と「銀行振込」を登録し、「お客様情報」として「名前を必須にする」と「カナを必須にする」ことをお勧めします。その他の情報はご希望に応じて変更してください。登録後に変更することも可能です。最後にスクロールダウンし画面下の「保存」ボタンをクリックしてください。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfHo0MUFt2ovT4tihq8s5XabaR8ybnNAnU2yQvSTqtNPC7M01WwoX35WAZEhl_-SehckcwiBDn-I4tuQ5VSbiFO0LOdYQS_cng-7amQ3Yi6vOjJTJyYNzWChj9eoHCupKd_ZuTVDg?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



５  続いてfirmee側の設定をします。

（１）ログインした状態で、画面右上の歯車ボタン→プロフィールを開きます。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXctYp5KS84NMIFRKP5p1NLM2F1cvJSq0nbYrlrDVnxdHGhoPDmlv8aoln9qlhJgQz1MktL9tijmysgjgT-AqdhXNAWMEwYoeMMpyjV7cAkLJx-j-F249mIffr5srBBqHchB4QvHLA?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

（２）　「外部システム連携」の「UnivaPay（決済システム）連携」をクリックします。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcy_cSZVGlLpf45kkuVJ8YZwibxDHLD_zsUWFWz3mCVvNkei1C7S2DD7MByfoqh2F0v9w3Zdc__Tfov2zdr-2JAz6RrikUU3NFtYWyAIySJP2GRcExyJaAh44OXWDCLmVUPsCsInA?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

（３）改めてUnivapayのマーチャント・コンソールの

管理画面（[https://merchant.univapay.com/login](https://merchant.univapay.com/login)）を開いて、店舗→決済フォーム→リンクフォーム設定→URLコード と進んでください。設定画面が表示されますので以下のように設定してください

* 金額は空欄にしておいてください
* CVV認証はカード裏の3\~4桁の数字認証です。デフォルトで選択されており、そのままにすることをおすすめします
* クレジットカードによる分割払いを認める場合は分割払い欄にチェックを入れてください\


最後に、画面下に表示されているURLをコピーしてください。コピーに際しては、「URL」の右側のコピーアイコンからコピーするようご注意ください。

（注）現在「定期課金」やその他のオプションには対応していません。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeVKYGoRf_flwj9ZQN2of0lLtT7I7oQspWjeq0RPzw60AW2x6fjwoxP41ZhJeBi4bvuh1-_62i_HLyRrD6_w8xm46HQk9F0hj8k2RNeFxNtPFWoDaoVaDhgsIuxgdzXhyxvokVfyQ?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

\


（４）firmeeの画面に戻り、リンクフォームURL欄に取得したURLを貼り付け、登録するをクリックします。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd-lgzYL2TX7gpRfjBcDEAdegusl1NqURkC_87F16WieKAYmlKyjXkQUAby1nuDWN1kT6Ev9xCfw2dJddXtBqA_dJdKTWkxFGAx7nVeKCWHpGlurEpu8zrwMIQ2MpsOHm-M-Z-ufg?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



（５）firmeeのページをそのままにして、改めてUnivaPayの管理画面に戻ります。サイドバーの「ウェブフック」をクリックして、「新規作成」ボタンをクリックします。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfiGoz0NZhUnSJANAM-CnPJBbv9uHBy3HsaUmq7FXJ50R3LxAeoRSBC_d8YnmoUoIwKxqfox6jF5boqzEv4-fF-a_o1R35w0ZbYL7_eLzQQ8I9NoZBCmh0km9pwCp9xQo-p6uKm?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



（６）URL欄に　[https://app.firmee.com/payments/webhook](https://app.firmee.com/payments/webhook)　と入力し、【課金情報／ステータスの更新】と【課金】にチェックを入れ、「作成」ボタンをクリックします。このウェブフック設定により、決済が完了した際にfirmeeに通知が送られ、入金日が自動的に登録されます。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcyVB45qk32NUbNfMR3bh3hqqpv75g0bG0gMe_BEGMG9nCliGhhRPWnUn7o5fbMvD6BOAIbos4GidBOCOhVYnem0Bd81Yc_Yr23bGHp_lMRTx-qCXR2VvQEyJfKPHrXbdATYwQFeA?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

\


以上で連携は完了です。



## 使い方



１　firmee内で、売り上げを設定したい事件の詳細ページから新規→売上を選択します。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdRe07tMOom7Hs523y7uy6lRJLJMi2NH3WpDSs1VQ7VWVPvKozwgcTJXKbueRIFMVa6Feb18K6PFmeth81m7_Cm5OXr3k_bbbbKmNjHOich0cPmr-e8WxZL_4AVj8nc_J15Z3cgHH0gu2hhIHquapdOxhM?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



２　売上を登録します。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXe01dSoylvdlylGoockskhaRt1FZfTzgWTQMMGuj0SWKPG87u1cnWzVIc1HWinlv-aIvmpp-Ueiv-Bl4FGCKOrciT9zJtILrV2JTJy0TQ6rasA5aSoWahGrq9m95A-fpPcINf0AwMaxt4NTIatNMcmhMKzP?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



３　登録した売上の詳細ページから、「UnivaPay支払リンク作成」をクリックします。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXf3mkI5ZY4wHcuXNPHxDqTIDdlZVoBF8p6AHJQ3H7E7vUriVaYTTFIKTDHFFURoPTR-fJQNQBSf0hWzdq0qkg6qEBEgNY3gWTG8aMQt-tq5jvb-S2AJLj8sVdUeqoqNKSyqNlPENprSMkCpsECF6_LOhe6q?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

４　支払い用リンクが作成されます。こちらを依頼者に送付してください。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcXY5B9PL0RS9yOyk-M3J5v274X8lUrPLJ6sYsxGUsCAX7nqSLfG5YjeghGT98VNM6qATkoJALOfzsmKuCddInshj732ICZQVvMm3IFLlyRWZbYRTlCIzQd9ctNVBf3EO-sQQWIHBmbrYIEZsMZLqqffbmz?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



５　依頼者がリンクをクリックすると、支払い方法の選択画面が表示されます。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXc9QiKZd_hwzlP7WUWrr0aOuwwH9CUQPo9blW3HYFX6vStv_8DEaUlM6FEL2JqL1V4mclTzJglQURi_Llr03_dWr-VvJJJF582gLHcYcNWHp3gJ5ZHXu6ahG6YXFPVQPlnbxJb0pM8qAXrRYO3kx62Ckn26?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



６　カード決済を選択すると、カード情報の登録フォームが表示されます。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcTKaEN0SW8SQpuFYRapEUVZmm_QRRf7IObKeymR0DklfisgDjKri3Kn_hCoOc699CSjE_hlKK4YANXLDZQtfUMSWcioWr9s5va-LQIkjIscdvZaH-EDVdCtazxsPmXVNCrnB7evWl1VNGu8H27LIAtOZc?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>



７　銀行振込を選択すると、ユーザー情報の登録画面が表示されたのち、振込先銀行情報が登録されます。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXerSkm8Wah12ktapoJy02k6FXpHSzf23s4DhsWV8Sp5kYsiaavBZfmfsjOZh4fhStqt_DjGppI5i025T46Ft15oNO7bCXH6VCPd-q4MfwB6bxzPdmlwgdh3oiw85JwAVKATnKbtCotwQUkpL5U8Ssq96Td2?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

８　依頼者によってカード決済が完了するか、銀行振込が実際になされると、firmee内の当該売上情報に「入金日」が登録されます。なお、作成日が登録されていない場合には、URL作成日が「作成日」として登録されます。

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfS5XbZ60_d98shoTPZRZW4UcFNQCA1JupY2Yot3lDyZel-yZN2VfG3SHuGa18rQWiWFgL12uMqGEObBTI7yCTSVjjgjbL75ljMYlqFt9yKe9z_Qm7CN-Re6JbbWvpNIA2yIywIUB46EwC11edU7la7wcE?key=fE_DWkJXP5uB7d6mPgj6ig" alt=""><figcaption></figcaption></figure>

\
\
\
firmee連携特典として、圧倒的低価格でクレジットカード利用を導入できます。お気軽にご活用ください。\


\


\


