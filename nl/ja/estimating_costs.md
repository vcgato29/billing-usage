---

copyright:

  years: 2015, 2018

lastupdated: "2018-06-14"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}

# コストの計算方法
{: #cost}

さまざまな方法を使用して、アプリをビルドしてホストするための {{site.data.keyword.Bluemix}} の Platform as a Service (PaaS) リソースと Infrastructure as a Service (IaaS) リソースの使用コストを見積もることができます。
{:shortdesc}

以下の方法を使用して、コストを判別できます。
* [料金カリキュレーター ![外部リンク・アイコン](../icons/launch-glyph.svg)](https://console.bluemix.net/pricing/){: new_window} を使用して、使用するプラットフォーム・リソースとインフラストラクチャー・リソースの合計コストを見積もります。
* {{site.data.keyword.Bluemix_notm}} {{site.data.keyword.pricing_sheet}} にあるコスト見積もりツールを使用して、アプリのサイズに基づくコストのおおまかな見積もりを表示します。
* 「料金」ページにある「費用計算」を使用して、ユーザーが入力したランタイムとサービスの使用量に基づくアプリの正確な価格を表示します。
* コストを手動で計算します。

## 料金カリキュレーターの使用
{: #pricing-calculator}

購入する前に、料金カリキュレーターを使用して、プラットフォーム・リソースと多数のインフラストラクチャー・リソースのコストを見積もることができます。
料金カリキュレーターは以下の機能を備えています。
  * 現時点では米国ドル (USD) 通貨単位で提供されているコスト見積もり。
  * 現時点では**「コンピュート」**と**「コンテナー」**のカテゴリーに使用可能なインフラストラクチャー・リソースの見積もり。
  * 現時点では割引を含んでいないリソースのコスト見積もり。
  * コストの見積もりは、プランニング目的で提供されています。

1. 料金カリキュレーターには、以下のいずれかの方法でアクセスします。
  * [「料金」ページ![外部リンク・アイコン](../icons/launch-glyph.svg)](https://www.ibm.com/cloud/pricing){: new_window} で、ソリューションの探索セクションから**「カリキュレーターを使用する」**をクリックします。
  * 現在、{{site.data.keyword.Bluemix_notm}} にログインしていない場合は、[{{site.data.keyword.Bluemix_notm}} ホーム・ページ ![外部リンク・アイコン](../icons/launch-glyph.svg)](https://console.bluemix.net/) から、**「料金」**をクリックします。
2. **「インフラストラクチャー」**または**「プラットフォーム」**のリストから、価格を照会するリソースのカテゴリーを選択します。 カテゴリー内の選択したリソースが表示され、特定のリソースのカテゴリーを検索することもできます。
3. カテゴリー内のリソースを選択して、その説明を表示します。 一部のリソースには、複数のオプションがあります。 例えば、**「インフラストラクチャー」**>**「コンピュート」**>**「ベア・メタル・サーバー」**を選択した場合は、サーバーのリストから選択できます。
4. 追加するリソースの数量を選択します。
5. **「見積もりに追加」**をクリックします。
6. 見積もるものが追加されるまで、**「インフラストラクチャー」**と**「プラットフォーム」**のカテゴリーからリソースの追加を続けます。 **「見積もり」**パネルに、追加したリソース、各リソースの価格、および合計価格が表示されます。
7. オプションで、リソースのリストがまとまったら**「見積もり」**パネルでその情報の PDF を作成するには、**「PDF のダウンロード」**をクリックします。PDF の作成目的として、例えば、価格を照会しているリソースを購入前に検討することや、リソースを購入する際のガイドとして使用することなどが考えられます。


プラットフォーム・リソースのみの価格を照会している場合は、米国ドル (USD) 以外の通貨単位での見積もりを表示するために、**「クラシック・カリキュレーターをお探しですか? (Looking for the Classic Calculator?)」**をクリックできます。 クラシック・カリキュレーターは、インフラストラクチャー・リソースを含んでいません。
{: tip}

### プラットフォーム・リソースに対するクラシック・カリキュレーターの使用
{: #calculator}

米国ドル (USD) 以外の通貨単位でプラットフォーム・リソースのコストを計算するには、クラシック・カリキュレーターを使用します。 クラシック・カリキュレーターは、インフラストラクチャー・リソースの価格見積もりを提供しません。

1. {{site.data.keyword.Bluemix_notm}} {{site.data.keyword.pricing_sheet}} にアクセスします。
2. 使用するすべてのワークロード・セクションをサポートするために、「インフラストラクチャー」内のいずれかのオプションを選択します。

計算器を使用するには、インスタンス数やプッシュ通知数など、リストされたリソースの予想される月々の使用量を入力します。 計算器は、入力に対する価格を即時に表示します。 計算器は、月々のコストではなく、年間のコストを表示するように調整することもできます。

## 手動でのコスト計算
{: #manual}

{{site.data.keyword.Bluemix_notm}} コストをご自身で見積もると、{{site.data.keyword.Bluemix_notm}} コストがどのように計算されるかを詳しく理解することができます。 ランタイムの価格および使用されるサービスの価格を考慮することにより、{{site.data.keyword.Bluemix_notm}} を使用してアプリケーションを構築しホストする場合の総額を計算することができます。 ランタイムとサービスの価格は時折変動するため、総額を計算する際には、{{site.data.keyword.Bluemix_notm}} 価格設定シートで最新情報を参照する必要があります。

## サポートされているお支払い通貨

次の表に、使用可能なお支払い通貨のリストを示します。

|ISO 4217 コード| 通貨|
|-------------|---------|
|AUD |	  オーストラリア・ドル|
|BRL |	  ブラジル・リアル|
|CAD |	  カナダ・ドル|
|CHF |	  スイス・フラン|
|DKK |	  デンマーク・クローネ|
|EUR |	  ユーロ|
|GBP |	  スターリング・ポンド|
|INR |	  インド・ルピー|
|JPY |	  日本円|
|KRW |	  韓国ウォン|
|NOK |	  ノルウェー・クローネ|
|NZD |	  ニュージーランド・ドル|
|SEK |	  スウェーデン・クローネ|
|USD |    米国ドル|
|ZAR |	  南アフリカ共和国ランド|
{:caption="表 1. サポートされている通貨" caption-side="top"}

{{site.data.keyword.Bluemix_notm}} アカウントと SoftLayer アカウントをリンクした場合、米国ドル (USD) 単位のみの請求書を 1 通受け取ることになります。 詳しくは『[リンクされたアカウントの統合請求](/docs/account/linking_accounts.html)』を参照してください。
{: tip}
