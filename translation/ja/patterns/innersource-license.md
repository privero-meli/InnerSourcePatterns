## Title

インナーソースライセンス

## Patlet

同じ組織に属する2つの法人は、ソフトウェアのソースコードを互いに共有したいと考えていますが、法的責任や会社間の会計処理の観点からの影響を懸念しています。

**インナーソースライセンス**は、組織内でソースコードを共有するための再利用可能な法的枠組みを提供します。これにより、新しいコラボレーションの選択肢が広がり、関係する法人 の権利と義務が明確になります。

## 問題

組織内の2つ以上の法人が互いにコードを共有したい場合、条件についての合意が必要であり、多くの場合で法的契約が必要になります。プロジェクトごとにこのような契約を作成するには手間がかかり、それは共有における障壁になってしまいます。たとえば、ある法人のチームは複雑そうだからという理由で、組織内の別の法人とソースコードを共有しないことに決めるかもしれません。

共有における障壁は、組織の複数で同様のソリューションを再構築する際のサイロ化と車輪の再発明につながる可能性があります。

ソースコードを共有する時点では、共有の価値を確実に予測することはできません。共有の活動に(使用条件の交渉などの)多大な労力が必要な場合、法人は投資に対する収益率を懸念しているため、一連の活動を行う可能性は低くなります。

## 状況

- コードを共有したい大量の子会社を持つ大組織。組織が大きくなればなるほど、このパターンの価値は高くなります。
- 定義によると、法人は独自の法的権利と義務を持っています。
- 複数の法人はソフトウェアを開発しており、他の法人のサービスを使用しています。彼らには、お互いのソースコードに貢献する動機があります。
- 組織とその組織構造は十分に複雑です。

## 組織に働く力学

- 特に、技術、法律、ビジネスの観点を考慮する必要がある場合、正式な契約書を書くのに必要な**労力のレベル**があります。
- 大きな組織(特に多くの法人から成る組織)には、多くの**内部規制**があります。新たに締結される契約は、セキュリティ、プライバシー、調達プロセスなど、これらの規制に準拠しなければなりません。規制が多いため、特に標準的な手順がない場合、2つの法人間でソフトウェアを共有することについてこれらの規制に準拠しているかどうかを評価することが困難になる場合があります。
- 組織内のいずれかの法人が、独占的なコードと組織内のライセンス料の会計処理に依存する **ビジネスモデル** を有している場合があります。
- インナーソースのコラボレーションとソースコードの共有に**企業文化**が慣れていない場合があります。これは、共有ソースコードを使用する場合の権利と義務についての不確実性をもたらします。
- ソフトウェアの使用を自由にすることが、競争と所有権の拡大につながります。
- ソースコードの共有に関する事項を含む法的なルールが存在します。しかしこれらのルールは標準化されていないため、プロジェクトごとに交渉と理解のための追加的な労力が発生します。また既存の契約では、真のインナーソースのアプローチをサポートするために十分オープンな意味でのソースコードの共有ができない場合があります。
- あるいは、法的な契約は結ばれていないものの、ソースコードが非公式に共有されている場合もあります。その場合、所有権や権利・義務の明確化が必要なケースにおいて不確実性が生じるかもしれません。

## ソリューション

対象組織(およびその法人)のニーズに合わせてカスタマイズした **インナーソース ライセンス** を作成します。このライセンスは、最も重要な企業間関係に適用できるような汎用的なものである必要があります。

インナーソース ライセンスは、関係する法的実体の境界を越えて、本当にオープンソースのような共同作業を可能にするように書くことが重要です。したがって、フリーソフトウェアの4つの自由(*)は、ライセンスに統合されるべきです。

このライセンスは正式な法的文書として書かれており、コード共有契約を管理するために法人間の契約の一部として使用することができるようにします。

(*「4つの自由」の補足: 使用する自由, 変更する自由, 共有する自由, 変更したソフトウェアを再配布する自由)

## 結果の状況

インナーソースライセンスにより、組織内の法人間でコードを共有するためのツールを手に入れることができます。

このライセンスは、ソースコードの共有に関する組織内の会話を簡素化し、法人が最初に使う動機づけにもなっています。

**注:** 事例で説明されている実験は初期段階にあります。したがって、しっかりとした**結果の状況**はまだ形成されていません。数ヶ月後には、この問題に対するインナーソースライセンスの効果がより明確になり、このセクションは更新されるでしょう。

## 事例

DB Systel社は彼ら自身のインナーソースライセンスを作りました、内容は[DB Inner Source License][db-inner-source-license] をご覧ください。彼らは、オープンソースのような出発点を提供する[EUPL][eupl]を使用し、その後、彼らの特定の組織のコンテキストに必要な制約と追加のルールを作り出しました。

DB 社の中で最初の法人(企業) は、このインナーソース ライセンスを使用しています。

すでに現れているポジティブな効果のひとつは、特に関係者の中にまだインナーソースのコンセプトをよく知らない人がいる場合、会話がシンプルになることです。ライセンスはよく知られた概念なので、インナーソースライセンスがあることは、議論のきっかけになります。

この実験では、真のインナーソースのコントリビューションとコラボレーションモデルにつながるために解決しなければならない、さらなるコラボレーションの課題があることも明らかになりました。

その課題とは、以下のようなものです。

- インナーソースのライセンスプロジェクトを発見できるようにする
- オープンソースのように、プロジェクトでコラボレーションするためのコミュニティを構築すること。

これまでのところ、このインナーソースライセンスの下で共有されるソフトウェアは、ほとんどがツール、インフラ、およびスタックの下位にあるツールであることは言及に値します。

## ステータス

* Structured
* **事例**に記載されている実験は、2020年2月から実施されています。最初の経験では、最初のポジティブな効果を示していますが、パターンを完全に評価するためには、より多くの経験が必要になります。

## 著者

- Cornelius Schumacher (DB Systel GmbH)
- Schlomo Schapiro (DB Systel GmbH)
- Sebastian Spier

## リファレンス

- FOSSBack 2020 Presentation: [Cornelius Schumacher - Blending Open Source and Corporate Values](https://youtu.be/hikC6U8X_Ec) - インナーソース ライセンスの詳細については、27:30以降をご覧ください
- [DB Inner Source License][db-inner-source-license]

## 単語の解説

- **組織** - 複数の企業の母体(同義語: グループ、ホールディング、エンタープライズ) (例: Microsoft Corporation)
- **法的エンティティ** - 独自の法的権利と義務を有するエンティティ (同義語: グループ子会社、子会社、関連会社) (例: Microsoft Japan, GitHub, LinkedIn)

[db-inner-source-license]: https://github.com/dbsystel/open-source-policies/blob/master/DB-Inner-Source-License.md
[eupl]: https://joinup.ec.europa.eu/collection/eupl/eupl-text-eupl-12

## 翻訳の履歴

- **2022-06-05** - 翻訳 [Yuki Hattori](https://github.com/yuhattor)
- **2022-06-13** - レビュー [@kanazawazawa](https://github.com/kanazawazawa)