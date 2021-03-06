---

copyright:

  years: 2017, 2018

lastupdated: "2017-11-10"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# {{site.data.keyword.Bluemix_notm}} でのアクセス管理
{: #cloudaccess}

## アクセス管理とは

アクセス管理によって、どのユーザーがアカウント内のリソースを表示、作成、使用、および管理できるのかを制御することができます。 アクセスを認可するために、役割を割り当てることができます。役割は、プラットフォーム管理タスクの実行およびアカウント・リソースへのアクセスを行うためのアクセス・レベルをユーザーに許可します。

{{site.data.keyword.Bluemix_notm}} でのアクセス管理の方法は、アクセス権限を割り当てたいリソースのタイプによって異なります。 {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) は、{{site.data.keyword.Bluemix_notm}} プラットフォーム全体で一環してリソースを管理するためのアクセス管理システムです。 {{site.data.keyword.Bluemix_notm}} インフラストラクチャー・リソースおよび Cloud Foundry リソースは、Cloud IAM を使用して管理されません。 これらのリソース・タイプには独自のアクセス管理システムがあります。 複数のリソース・タイプを組み合わせて使用する場合は、各タイプを別々に管理します。 インフラストラクチャー・リソースへのアクセス権限を割り当てるには、SoftLayer アカウント内で許可を設定します。 Cloud Foundry リソースへのアクセス権限を割り当てるには、コンソールの「ID およびアクセス」セクションで「Cloud Foundry を使用した割り当て (Assign by using Cloud Foundry)」オプションを使用します。

## アクセス管理を行う許可を持っているユーザー

アカウント所有者は、アカウント内のすべてのリソースへのアクセス権限を管理できます。 また、すべてのサービスに対する管理者役割をアカウント内のユーザーに割り当てることによって、プラットフォーム・リソースへのアクセス権限の管理タスクを委任することもできます。

アカウント内に Cloud Foundry サービスがある場合、他のユーザーに組織またはスペースの管理者役割を割り当てることができます。そうすると、そのユーザーは、管理する組織またはスペース内のインスタンスにアクセスできるよう、ユーザーを追加して Cloud Foundry ユーザー役割を割り当てることができるようになります。


## アクセス管理の開始方法

**「管理」** &gt; **「セキュリティー」** &gt; **「ID およびアクセス」**と進みます。次に、アカウント内のユーザーに関するアクセス管理を始めるため、**「ユーザー」** を選択します。 まず、リストからユーザーを選択します。 管理する許可のあるアクセス管理オプションのみが表示されます。 例えば、アカウント所有者でなく、組織またはスペースの管理者でもない場合、Cloud Foundry アクセスを管理するためのオプションは表示されません。

サービス ID を使用することによって、アプリおよびサービスにアクセス役割を割り当てることもできます。 **「サービス ID」**ページに移動して作業を始めます。 Cloud IAM を素早く稼働中にする方法について詳しくは、[概説チュートリアル](/docs/iam/quickstart.html#iambestpractice)で説明されているステップに従ってください。
