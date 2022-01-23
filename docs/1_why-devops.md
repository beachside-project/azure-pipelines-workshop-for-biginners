# 1. なぜ Azure Pipelines による CI/CD か

## ⚡ DevOps とパイプラインによる自動化の意義

ここでは、なぜ DevOps や Azure pipelines での自動化に取り組むのかを改めて見つめなおして、その価値を再確認します。

### DevOps とは

以下の Microsoft Learn のユニットをベースに解説します。

- [(ユニット2/5) DevOps とは](https://docs.microsoft.com/ja-jp/learn/modules/get-started-with-devops/2-what-is-devops)

### 補足

このユニットの補足として、[DevOps Research and Assessment (DORA)](https://cloud.google.com/blog/products/devops-sre/the-2019-accelerate-state-of-devops-elite-performance-productivity-and-scaling) の6年に及ぶリサーチによると、CI/CD の導入により4つの指標が向上する結果が出ています。

| 指標 | 概要 |
|---|----|
| Deployment Frequency | いかに頻繁に正常に安全に本番環境へデプロイすることができるかです。 |
| Lead Time for Changes | コミットから本番環境へリリースするまでのリードタイムです。言い換えると、顧客に価値を提供を届けるまでの時間で、新しい価値を素早く提供できることは競合他社の差別化の要因になります。 |
| Change Failure Rate | 本番環境へのデプロイが失敗した割合です。自動化が成熟するにつれ失敗率も低下していきます。 |
| Time to Restore Service | 本番環境でインシデントが起きた際に、復旧できるまでの時間です。|


## ⚡ Azure Pipelines での自動化

Azure pipelines を使った自動化は、

- ビルドの自動化
- テストの自動化
- デプロイの自動化
- プラットフォームのプロビジョニング

などが考えられますが、今回のワークショップではビルド、テスト、そしてデプロイの自動化にフォーカスします。


## 🎉 Congraturations

お疲れ様でした🎉。このモジュールでは、なぜ DevOps、そしてパイプラインを使うかの意義を確認しました。

次のモジュールでは、Azure Pipelines の基本的な構造やシンタックスについて説明します。

<br>

---

[次へ: 2. Azure Pipelines で最初に知っておきたいこと](./2_azure-pipelines-fundamental.md)

[README へ戻る](../README.md)
