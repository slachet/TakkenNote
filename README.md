# 民法

## 無効/取消/解除
- 無効: 法律行為が最初から存在しないとする --> 誰でも主張可能
- 取消: 詐欺や錯誤、虚偽の意思表示だったので効力の発生はあるが、遡及して無効 --> 瑕疵のある意思表示をした側の主張が**必要**
- 解除: 法律行為は完全に有効だが、その後の事情で契約をやめること: 主張する側の主張が必要

## 善意無過失の第三者の保護
- (取消|解除)**前の**第三者は、善意無過失であれば保護される
- (取消|解除)**後の**第三者は、善意無過失であっても保護されない (二重譲渡だから) --> 登記が対抗要件
- 制限行為能力者の法律行為は取り消し可能なので、善意無過失であっても**登記でも対抗できない** --> 1ヶ月以上の期間を定めて催告する (本人の沈黙: 取消; 監督者の沈黙: 追認)

## 解除/時効/取消し前後の第三者

| - | 前に第三者が登場 | 後に第三者が登場 |
| --- | --- | --- |
| 時効完成 | 時効取得者が登記なくても主張 | *登記が対抗要件* |
| 取消 | 取消権者が主張 | *登記が対抗要件* |
| 錯誤取消 | 善意無過失な第三者が主張 | *登記が対抗要件* |
| 解除 | *登記が対抗要件*　| *登記が対抗要件* |

### 保護される元の持ち主, 保護されない "前の第三者"

```
[0]
<A>

[1]
A -------> <B>

[2]
A -------> B -------> <C> (Cが登場)

[2]
A ---X---> B -------> <C> (AとBの取消, AとBの解除, Bの時効取得)

[3]
<A>        B           C  (Aが登記がなくても対抗できる)
|<~~~~~~~~~?~~~~~~~~~~~|
```

### 登記が対抗要件となる "後の第三者"

```
[0]
<A>

[1]
A -------> <B>

[1]
<A> ---X---> B            (AとBの取消: そもそも契約はなかった)

[2]
<A> ---X---> B -------> C (Cの登場)

[3]
<A> ---X---> B -------> C (Bが二重譲渡, 登記で対抗)
|<~~~~~?~~~~~|~~~~~?~~~>|
```

### 転借の第三者 (サブリース)
- 無断の転借が行われた場合、賃貸人は第一の賃借人との借家契約を解除できる (転借をした特段の事情があれば、解除できない)
- 賃貸人と賃借人の解除において、転借人に通知不要
- 賃貸人と賃借人が*合意解除*した場合、転借人の権利は失われない
- 転借人は、賃貸人 (所有者) に直接義務を負う: **転借人は前払いでは対抗できない**
  - 賃料 > 転賃料: 転賃料 (転借人の保護)
  - 賃料 <= 転賃料: 賃料 (直接なので上乗せは無視)
- 背信等での賃貸借契約の解除後でも、転借人への明渡請求は6カ月の猶予が必要

## 制限行為能力
- 成年後見人・保佐人・補助人: 制限行為能力者を助ける
- 成年後見人は当然に代理権を持ち、保佐人と補助人は申立によって (特定の) 代理権を得る
- 保佐人と補助人は同意と取消だけできるが、成年後見人は包括的な代理権を持つため全権を持つ

## 同時履行の抗弁権
- 同時履行の抗弁権がある場合、債務を不履行でも債務不履行にならない
- 双務契約は同時履行の抗弁権を発生させる
- 相手方の債務が弁済期にないと、同時履行の抗弁権はないこともある

### 具体例
- 代金支払い <--> 所有権移転登記
- (解除 or 取消の) 原状回復義務 <--> 所有権移転登記の抹消

### 実は同時履行ではない
- 敷金返還債務 <--> 目的物返還債務 (敷金が返されないからといって明け渡さないことはできない)
- 造作買い取り代金支払い債務 <--> 建物明け渡し義務
- (有償委任 or 有償寄託の) 支払い債務 <--> 事務履行債務 (受任者はまず委任事務をしなければならない)

## 共有
- 行為に必要な同意
  - 保存行為: 単独
  - 管理行為: 過半 (賃貸に出すなど)
  - 変更処分: 全員
  - (使用収益は全部についてできる)
- 共有者の死亡: 相続人 --(いなければ)--> 特別縁故者 --(いなければ)--> 他の共有者
- 5年以内の不分割特約, 更新可能

## 善管注意義務
- 委任の受任者は、無報酬でも善管注意義務
- 寄託の受託者は、無報酬なら自己と同一の注意、有償なら善管注意義務

## 死亡
- 使用貸借は、借主の死亡によって終了、貸主の死亡は継続
- 賃貸借は、いずれの死亡によっても継続
- 定期贈与は一方の死亡によって終了、通常の贈与は継続

## 相続
- 被相続人: 死亡者
- 相続人: 生き残った人間ら

## 占有
### 一見して占有ではないが、占有
- 時効取得のための占有は、直接占有だけではなく、代理占有 (賃貸に出す) も可能
- 占有回収の訴えを提起し、これを回復した場合、占有を奪われていた期間も占有の期間に算定

### 時効取得
- 20年間公然と所有の意思を持つ
- 善意無過失に10年間公然と所有の意思を持つ
    - 善意無過失の判定は占有の開始で判定
    - 前の占有者の **瑕疵** を継承する
- 占有は相続される

## 損害賠償請求権の時効

```
          0       3                                 20
不法行為   ========|----------------------------------|
         |        \                                  \
         |          \                                  \
         |            \   身体生命の場合は5年に延長          \
         |              \                                 \
身体生命   ==============|----------------------------------|
         |              |                                 /
         |              |                               /
         |              |                             /
         |              |                           /   身体生命の場合は20年に延長
         |              |                         /
         |              |                       /
         |              |                     /
不履行　   ==============|--------------------|
          0             5                   10     20
```

### 不法行為のための損害賠償
- 主観的起算点 **3年**以内 && 客観的起算点 *20年以内*: 改正に変更なし

#### 人の生命や身体の侵害のための損害賠償の場合 (改正で追加)
- 主観的起算点 **5年以内** && 客観的起算点 *20年以内*

### 債務不履行のための損害賠償
- 主観的起算点 *5年以内* && 客観的起算点 **10年以内**

#### 人の生命や身体の侵害のための損害賠償 (改正で追加)
- 主観的起算点 *5年以内* && 客観的起算点 **20年以内**

### 民法の一般債権の時効
- 主観的起算点5年以内 || 客観的起算点から10年以内

> 民法の債権と所有権以外の財産権は20年以内

## 停止条件付き譲渡
- 停止条件が成就した時から効力を生じる (停止条件が解除されたら効力発生)
- 条件付き契約の各当事者は、契約時点から、条件の成否が未定の間は相手の利益を害せない。害したら、相手は債務不履行の損害賠償債権を得る
- 停止条件が未成就であれば、他人に当該債権を譲渡できる
- 相手方が停止条件を故意に妨げた場合、停止条件が成就したとみなせる

## 保証契約
- 個人の根保証契約 (債務が特定されない場合の保証) は限度額の定めが必ず必要、個人以外なら不要

## 制限行為能力者
- 制限行為能力を理由として取り消しできるのは、制限行為能力者である本人も含まれ、それは法定代理人等が否定できない
- 未成年時点での契約を成年時点で追認すると、有効となり、制限行為能力を理由に取り消しできない

## 抵当権の譲渡と放棄
- 譲渡: 譲渡された人が譲渡した人の位置に移動、譲渡した人はその直下に移動
- 放棄: 譲渡された人と譲渡した人が同列、債権の割合で按分

# 都市計画法

```
都市計画 > 区域区分 > 地域地区 > 地区計画
```

- 都市計画区域外
- 準都市計画区域
- 都市計画区域
  - 区域区分
    - 市街化調整区域
    - 線引き区域
    - 市街化区域
      - 地域地区
        - 特別用途地区: 用途地域の制限を緩和
        - 特別用途制限地域: 用途地域が設定されていないときに制限を設定
        - 高層住居誘導地区: タワマン
        - 高度地区: 高さのmax/minを設定
        - 高度利用地区: 壁面の位置や容積率のmax/min、建蔽率のmaxを設定し、上空のdead spaceを利用する
        - 特定街区: 西新宿
        - 防火地域
        - 準防火地域
        - 景観地区
        - 風致地区: 都市の自然敵景観
        - 都市再生特別地区: すべての制限がない
        - 用途地域
          - 第一種低層住居専用
          - 第二種低層住居専用地域
          - 田園地域
          - 第一種中高層専用地域
          - 第二種中高層専用地域
          - 第一種住居地域
          - 第二種住居地域
          - 準住居地域
          - 商業地域
          - 近隣商業地域
          - 準工業地域
          - 工業地域
          - 工業専用地域
            - 地区計画

## 都市計画
都市計画の決定や変更は、土地所有者の2/3 (全体うちの所有する割合) 以上の同意が必要

## 区域区分
- 知事が決定
- 都道府県にまたがっても良い

## 用途地域
- 市街化区域には必ず定める
- 市街化調整区域には*原則*定めない
- 非線引き区域と準都市計画域には定めることができる
- `特別用途地区` は用途地域内の一部 (用途制限の緩和)
- `特定用途制限地域` は用途地域が未指定 (*市街化調整区域には設定できない*)
- 市町村が決定。東京都23区は東京都が決定

### 一種と二種で扱いが異なる施設
- 火葬場: 第一種中高層専用地域は**不可**, 第二種中高層住居専用地域以下は*可能*
- カラオケ (10000m^2以下): 第一種住居地域は**不可**, 第二種住居地域は**可能**
- 3000m^2<床面積<10000m^2の店舗: 第一種住居地域は**不可**, 第二種住居地域は**可能**

## 地区計画
- 用途地域の有無は関係なく定められる
- 市町村が決定
- 住民レベル

## 防火地域・準防火地域
**都市計画区域のみに指定可能**

## 開発
- 都道府県知事が許可 (指定都市・中核都市・特例市では市長)
- 市街化調整区域の開発は原則禁止
  - 周辺住民の日常生活に必要な店舗のための開発や市街化促進の恐れがないが市街化区域では困難な開発は、開発許可が出る

### 開発行為の定義

```
(建築物の建築 || 特定工作物の建築) && 土地の区画形質の変更
```

- 第一種特定工作物
  - コンクリートプラント
  - アスファルトプラント
- 第二種特定工作物
  - ゴルフコース
  - 10000m^2以上の野球場・遊園地・墓地・動物園

*注意: 開発行為ではない*
- 建築物の建築: 土地の区画形質の変更ではない
- 青空駐車場をつくるための土地区画形質の変更工事: 建築物がない

### 許可の必要な開発行為

| 開発許可 | 市街化区域 | 非線引き区域 | 準都市計画区域 | それ以外 | 市街化調整区域 |
| --- | --- | --- | --- | --- | --- |
| --- | 1000m^2 <= | 3000m^2 <= | 3000m^2 <= | 10000m^2 <= | **0m^2** < |
| (比較: 事後届) | 2000m^2 <= | 5000m^2 <= | 10000m^2 <= | 10000m^2 <= | 5000m^2 <= |


注意:
- 都市計画事業、土地区画整理事業など事業の施行として行う行為は*許可不要*
- 市街化調整区域は必ず許可必要
- 市街化区域の「農林漁業の住宅や建築物」は許可必要 <--> 市街化区域以外での「農林漁業の住宅や建築物」は*許可不要*
- 公益上必要な建築物の建築は*許可不要* <--> 国、地方公共団体が行う庁舎や宿舎は原則許可必要

### 災害危険区域 ("災害レッドゾーン" の一部) の開発行為

> 都市計画法第33条第1項第8号は2022年に改正

- 自己の居住の用に供する目的以外の開発は、災害レッドゾーンでは原則禁止 (改正で、自己の業務用施設の開発行為は原則禁止となった)
- 災害レッドゾーン
  - 災害危険区域
    - がけ崩れ
    - 出水
    - 津波
  - 地すべり防止区域
  - 土砂災害**特別**警戒区域 (土砂災害警戒区域は、開発行為可能)
  - 急斜地崩壊危険区域
  - 津波災害特別警戒区域

# 国土利用計画法
地価の安定化のための法律: 民間セクターの対価を伴う取引を規制する
## 事後届け
### 原則必要な広さ
- 都市計画区域
    - 市街化区域: 2000m^2以上
    - 市街化区域以外 (i.e., 市街化調整区域 or 非線引区域): 5000m^2以上
- 都市計画区域外: 10000m^2以上

cf. 開発許可の必要な開発行為の大きさ

### 事後届けが不要となる例外
- 取引の一方が公共の主体
- 民事調停で取得した場合 (売買以外の取得)

# 宅地造成及び盛り土規制法 (2022年3月1日に "宅地造成等規制法" から改正)

- 地造成等工事規制区域 <-- 重要
- 造成宅地防災区域
- 特定盛度規制区域

## 地造成等工事規制区域

### "宅地造成" の定義
以下に当てはまり、かつ宅地 (農地・放牧・森林または道路公園河川公共施設*以外*の土地) 以外の土地を宅地にする

- 1mでも必要: *崖を生じる*盛土
- 2mから必要: 切土が含まれる || 崖を生じない盛土
- 切土または盛土を含む造成面積: 500m^2を超える

> 宅地造成を含まない転用ならば、下記届出 (事後14日以内の届出) で十分

### 許可
- 「宅地造成」を含み、区域内であれば、工事に着手する前に知事の許可が必要
- 上記許可を受けた計画の変更は、原則許可が必要 (軽微なら届出)
- 都市計画法の許可があれば、当該許可は不要

### 届出
- 規制区域指定時点で宅地造成工事が進行中: `within 21 days after designation`
- 許可不要 (e.g., 都市計画法による開発の許可を受けた場合) な (高さ2mを超える擁壁 || 排水施設の除去): `before 14 days before start`
- 農地転用 or 宅地転用 or 宅地-->宅地: `within 14 days after operation`

### 設計者の制限

以下であれば、政令の有資格者が設計しなければならない

- 5mを超える擁壁
- 盛土 or 切土をする土地の面積が1000m^2を超える土地に排水施設を設置

# 登記法
- 表題部: 不動産の物的状況 (i.e., 新築増築改築) (登記官の職権で設定できる)
- 権利部甲区: 所有者や取得年月日
- 権利部乙区: 登記の目的原因、権利者

## 期限
- 表題部1ヶ月以内の登録義務 (物的状況だけ義務、他は任意)
- 権利部は義務なし (第三者への対抗のために普通は登記する)
- (2024年4月1日から) 相続した場合、登記が義務化 (権利部の更新), 相続を知った日から3年以内

## 申請者
権利者 (買主) と義務者 (売主) が共同

## 閲覧
- 登記簿謄本は誰でも
- 土地所在図、地積測量図等は誰でも
- 申請書とその他の図面は、正当な理由必要

## 分筆・合筆
- 所有権以外があっても可能: 分筆 (抵当権があれば、1つの債務に2つの土地になる)
- 所有権以外があったら不可能: 合筆 (一物一権の原則: 土地の一部分に権利があることを許さない)

# 土地区画整理法
- 土地区画整理事業は、必ず都市計画区域内 (市街化区域, 市街化調整区域, 非線引き区域) (*not in 準都市計画区域 or 都市計画区域外*)
- 都道府県が行う土地区画整理事業は、市街化区域か非線引き区域のみ
- 個人施行者は引き継がれる (死んで区画整理が中止しないように)
- 公的施行は、土地区画整理審議会を必ず置く。それ以外の施行は置かない。

# 宅建法
## 組織に免許は必要か
- 農協は必要
- 信託会社は国土交通大臣に届け出るので十分
- 国・地方公共団体はすべて不要

## 免許が必要なオペレーション
| Who | 売買 | 交換 | 貸借 |
| --- | --- | --- | --- |
| 自ら | 要 | 要 | 不 |
| 代理 | 要 | 要 | 要 |
| 媒介 | 要 | 要 | 要 |

自ら貸主 (大家業) には転貸借も含む: *サブリースに宅建業の免許は不要*

## クーリングオフ
### 要件
- 売主が宅建業者、買主が宅建業者以外 (法人でも可能)
- 特定の場所以外で申し込み or 契約が行われた
  - 宅建業者の事務所: 規制があり、厳正だから
  - *売主が依頼した*事務所: 事務所と同様に規制があり、厳正だから
  - *買主が申し出た*自宅や勤務先: 意志が強いと推認できるから (電話後訪問はクーリングオフ可能)
  - クーリングオフの*書面*で告知を受けてから8日以内 (告知日を含めて8日以内: 次週の同一曜日の23:59:59まで可能) に買主が意志を**発信**
  - (代金支払 && 物件引渡) が完了

## 宅建士登録
1. 宅建試験合格
2. *実務経験2年未満であれば*登録実務講習 (国土交通大臣の登録を受けた講習)
3. 宅建士登録
4. *宅建試験合格後1年を超えたならば*法定講習 (交付から起算して半年以内が有効, 都道府県知事が指定した講習)
5. 取引士証交付 (5年更新, 毎回法定講習)

## 宅建士停止
### 犯罪
- **罰金以上の**刑罰であれば免許取消
  - 宅建業法
  - 傷害罪・暴行罪
  - 脅迫罪
  - 背任罪
  - 現場幇助罪・凶器準備集合及び結集罪
- いかなる罪についても**禁錮以上の**刑罰の終了から5年間は登録ができない
- 過失の障害や致傷は欠格事由ではない
- 刑の確定までは免許は残る (控訴や上告すれば残る)

### 欠格事由に該当するようになった
- 欠格事由に至った場合、次の人間が該当した日から*30日以内* (禁錮懲役の場合も含まれる)
  - **本人**
  - 法定代理人
  - 同居親族
- 欠格事由の例
  - 制限行為能力者となった (改正で、実際の制限行為能力者というよりは、必要な認知機能を失った場合となった)
  - 禁錮以上の刑罰
  - 宅建業法背任暴力犯罪での罰金以上
- 両罰規定
  - 業者-->役員: 宅建業者の免許取り消しについての聴聞の公示の60日前までに役員 (*支店長は含まない*) であった者は、*業者の免許取消から5年間*は免許を取得できない
  - 役員-->業者: 役員 (*支店長は含む*) が欠格事由であった場合、宅建業者は*役員の刑の執行の終了から5年間*は免許を取得できない
- 執行猶予があれば、**執行猶予の終了後直ちに免許を受けられる**

## 業者/人の消滅
| Who died | Reporter | Period |
| --- | --- | --- |
| 宅建士の死亡 | 相続人 | 30d (知った日から) |
| 法人の消滅 | 消滅した元役員 | 30d |
| 法人の破産 | 破産管財人 | 30d |
| 法人の解散 | 清算人 | 30d |
| 廃業 | 本人/役員　| 30d |

> "**免許取消処分**の回避" の回避: 宅建業者が免許取消処分を受けそうにな (聴聞の公示) ってから処分確定までの間に廃業した (including 意味のない合併) 場合は、5年間免許が取得できなくなる

> 業務停止処分の回避は回避されていない (聴聞の公示を受けて廃業しても、5年たたずに再開できる)

## 報酬
権利金または売買代金x + TAX
- x<=200: `5%`
- 200<x<=400: `4%+2`
- 400>x: `3%+6`

| 取引様態 | 売買 | 貸借 (権利金は売買代金と同じ) |
| --- | --- | --- |
| 媒介 | 一方から1倍, 双方からも合計上限 | 一方から0.5ヶ月, 双方から合計1ヶ月 (承諾があれば一方から1倍、他方無料) |
| 代理 | 一方から2倍 | 一方から2倍, 双方からも合計2倍 |

> *2024年6月30日まで*廉価な空き家の特例: **売り主から領収できる仲介手数料は**、400万以下の空き家であれば、現地調査等の費用を加えた報酬の合計が税別18万円以下 (400万円のときの報酬) に引き上げられる

> *2024年7月1日から*廉価な空き家の特例: **売り主と買い主の両方から領収できる仲介手数料はそれぞれ**、800万円以下の空き家であれば、現地調査等の費用を加えた報酬の合計が税別33万円以下 (800万円のときの報酬) に引き上げられる

> 廉価な空き家の特例は、*代理*では適用不可能 (なぜなら、2倍となれば大抵は18万を超えるから)

> *2024年7月1日から*長期の空き家の**賃貸**の特例: 双方からの**合計2ヶ月**が上限 (借主からは1ヶ月が上限)

## 宅建士の設置
- 従業者証明を携帯させなければならない (バイトでも)
- 事務所: 5人に1人以上
- *契約をする*場所 (案内所等): 成年の*専任*を1人以上 (変更した場合は都道府県に30日以内に届け出)
- 事務所以外に営業する (展示会で契約) 場合、*10日前まで*に**所在地の知事と免許権者**に届出
- 事務所を増やした場合、*30日以内*に**免許権者**に届出

## 掲示義務・保存
- 従業者は`従業者証明書`
- 従業者名簿を**10年間**保存 (宅建士以外についても)
- 取引の帳簿
  - 取引の度に記録
  - 各事業年度毎で整理 (これを閉鎖と呼ぶ)
  - 閉鎖後**5年間** (新築 && 自ら売主は**10年間**) 保存
- 標識は`事務所と契約する場所の両方`
- 報酬額の掲示: 事務所のみ
- 帳簿: 事務所のみ

## 契約様態
- 専任媒介: 自己発見取引を許す, 最長3ヶ月, 2週間に1回以上の報告, REINSへは*休業日を除く***7日以内** (他業者利用の媒介で契約成立した場合の措置を記載)
- 専属専任媒介: 自己発見取引を許さない, 最長3ヶ月, 1週間に1回以上の報告, REINSへは*休業日を除く***5日以内** (自己発見取引の場合の措置を記載)

## 景表法
- 徒歩または道路距離、徒歩は80m/分の繰り上げ
- 名前にシンボルを入れるなら **直線距離** で300m以内
- 「新築」は建設完了から1年以内、誰も住んでいない状態、工事が途中で止まったならその期間の表示が必要
- 取引様態は広告のたびに、また注文を受けるたびに

## 書面
### 34条書面
- 説明は誰でも良い
- 記名は業者 <--> 35, 37条書面は宅建士
- 売買の媒介では双方に交付義務医義務, 賃貸借の媒介では不要
### 35条書面
- 代金以外の**金額と目的**
- 契約不適合責任の保証保険契約その他の措置の有無 (有ならその内容): **契約不適合責任は契約なので37条書面**義務医
- 売り主から買い主へ
### 37条書面
- 定めがあるときは記載
  - 契約不適合責任
  - 契約不適合責任のための保証保険契約
- 定めがなくても記載
  - 既存建物であれば、建物の構造体力条主要な部分の状況について当事者双方が確認した事項, なければ無いと書く
- 双方へ

## 保全の状況についての書類の保存状況

| 売買 宅地 | 売買 建物 | 貸借 宅地 | 貸借 建物 |
| --- | --- | --- | --- |
| 不 | 要 | 不 | 不 |

"契約終了時の取り壊しの定め" は借地でしかありえないので、`貸借 宅地` のみ

## ヘルプ
- 手付金の分割も猶予も禁止
- 名乗らず勧誘は禁止

## 監督処分
- 指示処分は公告不要、業務停止と取消、解除は公告必要 (宅建士についての処分の公告はない)
- 業務停止は1年以内に全部または一部
- 業者の免許取消は免許権者である国土交通大臣か知事のみが可能、他は事業を行っているところの知事も可能
- 宅建士は、登録を削除したら返納、満期で更新しなくても返納しなくて良い、事務禁止処分なら **提出**
- 代理は本人に帰属、よって代理人が宅建業者でも、宅建業は本人が免許を取らなければならない
- 宅建士に対するいかなる処分も広告できない。宅建業者に対する指示処分は広告できない
- 宅建業者が処分された時、その処分が専任宅建士の責めに帰すなら、その宅建士も処分可能

## 供託所
- 供託所は、本店の最寄り
- 営業の開始でも、支店の新たな設置でも、営業保証金を収めてから知事または国土交通大臣に届け出て、営業開始
- 業者が免許を受けてから3ヶ月以内に供託の届け出をしないと、催告され、催告から1ヶ月経っても届け出がないと、免許取り消しが **可能**
- 還付で営業保証金の不足が生じたら2週間以内に供託、供託してから2週間で知事に届出


遺産分割協議成立後、その効力は相続時点に遡及する
遺産分割は、遺産分割協議をしなければ分割できない債権についてのみ。可分債権は遺産分割の対象にならず、当然に分割される (勝手に自分の分を引き出して良い)。可分債権は、賃金債権、事故の損害賠償請求権や売掛金。かつては預貯金も可分債権なので勝手に引き出して良かったが、H28年からは遺産分割の対象となったので、遺産分割協議が必要になった

# 税金

## 種類
- 地方税
  - 固定資産税
  - 不動産取得税
- 国税
  - 所得税
  - 印紙税
  - 登録免許税
  - 贈与税

- 固都税: 1.4%, 台帳価格, 1月1日時点の所有者が1月1日時点で存在する市町村へ, 3年更新 (地目の変更などがあれば市町村長が変更可能)
  - 住宅用地の特例:
    - 住宅ならば1/3
    - 住宅 && 200m^2まであれば1/6
  - 新築の軽減措置 (2024年3月)
    - 戸建ては3年間1/2, マンションは5年間1/2
    - 長期優良住宅なら、戸建て5年間1/2、マンション7年間1/2
  - 課税標準が土地30万建物20万償却資産150万以下は、免税 (各市町村毎で計算, 各市町村内で合算)
  - 1.4%は標準税率であり、市町村は条例で上限を変えられる
- 不動産取得税: 4% (土地は一律3%, 住宅3% cf. 土地は消費税は無料), 台帳価格, 存在する都道府県へ
  - 住宅の場合3%
  - 法人の合併と相続は **不動産取得税** は無料
  - 新築特例: 50-240m^2以下の新築を取得した場合、課税標準から1200万円の控除
  - 新築が売れずに6ヶ月なら所有者を取得業者とする (業者なら1年程度)
- 譲渡 (所得税): 39.63%, 儲かった分, 国+地方へ
  1. 住宅 or 住まなくなってから3年後の12月31日まで: 3000万控除 (前年と前々年にこれを利用すると住宅ローン控除が使えない)
  2. 収容: 地方公共団体に買い取られる: 5000万控除
  3. 10年を超える所有: 6000万円以下の部分は軽減税率14.21% (翌年、翌々年、前年、前々年にこれを利用すると住宅ローン控除が使えない)
  4. 5年を超える所有: 軽減税率20.315%
  - 同年に収容と住居の売却をしても5000万が限度
　- 所有期間の判定は、判定する年の1月1日時点でN年か
- 登録免許税: 台帳の価格, 登記時点, 不動産の所在地
  - 売主と買主負担
- 印紙税: 領収書や契約書を作成するたびに
  - 電子契約は非課税
  - 5万円以上の領収書
  - 特に売買においては、*営業に関しないものは非課税*
  - 記載金額がなければ200円, 贈与文書は記載金額がない
  - 建物の賃貸借契約書は、印紙税の課税対象ではない
  - 土地の賃貸借では、変換されない権利金や**手付金が記載金額**
  - 売買は売買代金、**手付金の金額だけであれば記載金額なし**と扱う
  - 交換では、差金のみの記載ならそれ、交換金が両方あれば *高い方*
  - 契約変更では、増加なら増加分が記載金額、**減額なら記載金額なし**
  - 複数の譲渡であればその合計 (土地の譲渡と建築の請負が1枚の契約書なら、高い方)

# 8種制限
- 相手方は、宅建業者以外ならすべて当てはまる
- 住宅販売瑕疵担保保証金の供託は、契約以前にその所在地を伝える (引き渡しではない)
- 住宅販売瑕疵担保保証金の供託金は、前年までの戸数 (55m^2以下なら2つで1つ換算)
- 住宅販売瑕疵担保保証金の供託金の計算のための販売戸数の届け出が基準日から **3習慣以内** にないと、基準日の翌日から **50日を経過した以降** は新築の販売禁止
- 事前支払いは、名目に関係なくすべて解約手付にできる
- 損害賠償の予定や違約金の設定は、合計額が代金の **20%以下** であれば良い
- 手付金 (とあるなら中間金) が代金の **10%以上または1000万円以上** (未完成なら5%以上または1000万以上) であれば保全措置を **手付金の受領前** に講ずる (登記を移したなら不要)
- 手付金 (中間金は含まず) は、代金の**20%以下**
- 営業保証金や弁済業務保証金分担金の供託所とその所在地を説明しなければらならない (*35条書面 or 37条書面ではないから、口頭で良い*)
- 住宅瑕疵担保責任 (i.e., 契約不適合責任) を無効化する特約をつけられず、2年以上が絶対 (民法では、新築については10年間、中古については権利を知ってから5年または講師できる時から10年の早い方)
- 他人物売買は原則禁止
- クーリングオフは説明も解除の意思も必ず文書

# 地価公示
- 国土交通大臣が土地鑑定委員を任命し、土地鑑定委員会は公示区域内から標準地を選定し、土地鑑定委員会は不動産鑑定士2人に1月1日の標準地の価格を評価させ、委員会が審査してこれを定める
- 正常な価格とは、更地であれば単位面積当たりいくらか、を示したもの。標準地に建物があれば、無いものとして評価
- 地価公示の参照は、売買は努力義務 (指標)、不動産鑑定士が公示区域内の土地について価格を求めるときは義務 (基準)
- **地価公示において、知事の関与はない**

# 借地借家法
## 借家
### 期間の定め
- 普通借家: 期間の制限なし、ただし *1年未満だと期間の定めのないものとみなす*
- 定期借家: 期間の制限なし

### 契約
- 普通借家: 口頭でも成立
- 定期借家: 公正証書の契約と書面を必要とする説明

### 更新
- 普通借家: 可能, 再契約は可能
- 定期借家: 不可能, 再契約は可能

## 借地権
- 借地権の登記がなくても、借地に自己所有の建物があれば対抗できる (滅失しても、借地上に建造の意思を示せば2年間は対抗できる)
- 借地者が行う借地の譲渡や転貸には所有者の承諾が必要だが、所有者に不利にならないなら承諾がなくても裁判所から許可を得られる
- 借地者が、土地への抵当権設定後に建物を建造した場合、抵当権者はその建物を競売することができる <--> 法定地上権
- 建物買取請求権: 借地権の存続期間が終了 && 契約の更新がない
- 借地上に建物を再構築した場合、借地権は延長する ()
- 期間の定めのない普通借地権は最短30年、それより短ければ自動的に30年に延長
- 民法の賃借権の最長は50年だが、借地借家法の普通借地権では最長期間はない

## 地上権
- 地上権: 物権 (借地権 (賃借権) は債権) なので、所有権に近い
  - 当該権原についての処分が自由
  - (地上権を目的とする) 抵当権を設定できる
  - 地代を払うことはあり得る
  - (管理まで自分で行うため) 地主の修繕義務はない (借地であれば、借地人が修繕義務を負う)
- 法定地上権: (抵当権の設定などで) 建物と土地の所有者が異なるようになった場合、建物の所有者が借地料を払うことで引き続き建物の使用を主張できる権利
  - 要件:
    - **第1順位の**抵当権設定時に土地に建物が有ること
    - **第1順位の**抵当権設定時に土地と建物の所有者
    - 土地または建物の*どちらか一方*に抵当権が設定されている
    - 抵当権の実行により、土地の所有者と建物の所有者が別人になった
  - 賃借権は第三者に借地権を対抗できないが、法定地上権は対抗できる
  - 地上権は同意がある場合の土地利用

## 家賃変更特約

> 貸主も借主も増減の意思表示はどんな契約でもできる

> 定期借家だけは、"減額しない特約" が有効になる。他はすべて借主にfavourな "増額しない特約" だけ有効になり、他は無効になる。

|特約の方向|土地・普通|土地・定期|建物・普通|建物・定期|
| --- | --- | --- | --- | --- |
|一定期間増額しない|有効|有効|有効|有効|
|減額しない|無効|無効|無効|有効|

## 借主が減額の裁判に勝ったら
- 裁判の確定までは貸主の言値が通る
- 減額の意志の時点に遡及
- 支払い家賃と減額された家賃の差が発生すれば、その合計 (遡及するので) は年利10%で**返還**

## 借地借家の権利移動
### 対抗要件
- 原則: 借りていることの登記が対抗要件
- 借家の場合、冬季は現実的には不可能なので、対抗要件が引き渡しに変更
- オーナーの変更には賃借人の同意は不要

| 対抗要件 | 借りているもの |
| --- | --- |
| 引き渡し | 建物 |
| 登記 | 土地 |

# 借地権
- 対抗要件: 借地上に**登記済みの建物の所有**
- (普通借地権の)存続期間: 最短30年間 (30年より短ければ延長)
- 借地上の建物の滅失後、借地の残存期間を超えて建物を新たに建造できない特約は、
- 借地者が行う借地の譲渡や転貸には所有者の承諾が必要だが、所有者に不利にならないなら承諾がなくても裁判所から許可を得られる

> 借地権の登記がなくても、借地に自己所有の建物があれば対抗できる (滅失しても、借地上に建造の意思を示せば2年間は対抗できる)

# 農地法

|3条|4条|5条|
|---|---|---|
|権利移動|転用|権利移動 && 転用|

- 市街化区域の宅地転用は、農業委員会への届け出で十分 (大きさに関係ない)
- 相続での権利移動は3条の対象ではない (ただし、農業委員会に届出)
- 農地法の農地かどうかは、登記ではなく現況判断
- 2a未満なら、農家による、農地から農地関連への転用は、5条の許可不要
- 都道府県ならば、無条件に3条不要、必要性があれば4 or 5条も不要

# 区分所有法
- 占有者 (賃借人等) は、規約や集会の決議について区分所有者と同じ義務を負う
- 共用部分は、持分割合に応じて利益を得、費用を支払うが
- 共用部分の変更は、**議決権と区分所有者**の3/4以上で決議 (規約で**区分所有者**は過半数まで減らせる)
- 区分所有者全員の同意があれば、招集の手続きを経ずに集会を開ける

# 借家法
- 普通借家は更新が原則
- 普通借家は口頭契約も可能、定期借家は公正証書から定期性が記載された契約書が必要
- 200m^2未満の居住用なら、やむを得ないなら中途解約が1ヶ月の経過で可能

# 建築基準法

## 建築確認・許可
- 建築確認や都市計画の許可がまだの場合、賃貸の契約のみ可能 (賃貸の広告、売買の広告と契約は禁止)
- 建築確認後、その変更が発生したとき、変更手続き中でも当初の確認事項に基づき広告を継続して良い。当初と変更の内容の両方を示せば、変更の内容の広告も可能
- マンションの管理費が住戸ごとに異なるのにそれを表示できないとき、最高額と最低額を表示すれば足りる

## 建築確認の要否
- `(都市計画区域 || 準都市計画区域)` && `(新築 || 増改築 || 移転)`: 必要
- `(都市計画区域 || 準都市計画区域)` && `(用途変更 || 大規模修繕)`: *不要*
- `ANYWHERE` && `木造` && `(3階以上 || のべ500m^2以上 || 軒高9m以上)`: 必要
- `ANYWHERE` && `非木造` && `(2階以上 || のべ200m^2以上)`: 必要
- `特殊建築物: 200m^2以上`: 必要

## 接道義務

- 4m以上の道路に2m以上接していたら建築可能
- 4m未満の道路に2m以上接するが、建築可能 (セットバック必要): `建築基準法が適用されたときにすでに建築物が建ち並んでいた` && `特定行政庁の指定を受けた`
  - 1.8m未満であれば、建築審査会の同意が必要
- 道路に2m未満0m以上接しているが、建築可能: `通路として利用できる空き地や通行路が4m以上` && `通路や空き地の所有者の全員の許可がある` && `2階建て以下の住居専用`
- 接道義務は **(都市計画区域 || 準都市計画区域)にのみ適用される** 

## 避雷針・非常用昇降機
- 20m^2以上: 避雷針必須
- 31m^2以上: 非常用昇降機必須

## 採光換気
開口部は
- 採光のため: 居室床面積1/7以上の割合
- 換気のため: 居室面積1/20以上の割合

## 日影規制

- `Xh-Yh/Zm`: *ある用途地域*において、冬至において、Zmの高さ部分について、隣地境界線から5-10mの部分はX時間, 10mを超える部分はY時間だけ日陰になっても良い
- 商業・工業・工業専用は原則適用なし

```
 隣地境界線から10m超部分
    |
    |
5h-3h/4m <-- 測定する高さ
 |
 |
5-10mの部分
```

> その建物自体が用途地域外であっても、その影が用途地域にあり、建物が10mを超えるならば、規制対象

## "跨る" 場合

| 地域 | 判定 |
| --- | --- |
|用途地域 | 過半に属する地域の制限を受ける |
| 建蔽率/容積率 | 按分計算 |
| 斜線制限 | そこに属する部分はその部分に (用途地域をまたぐなら、問題となる部分が属する地域に従う)|
| (準) 防火地域 | 全部を厳しい方に準ずる |

## 防火

```
IF

のべ面積が 1000m^2を超える 建築物
&&
(耐火建築物|準耐火建築物) ではない

THEN

防火上有効な構造の (壁 || 防火床) によって有効に区画
&&
各区画の床面積の合計が1000m^2以内
```

## 建蔽率の緩和

| 条件 | 緩和範囲 |
| --- | --- |
| 建蔽率80%の防火地域内の耐火建築物 | 100%に変更 |
| (防火地域内 && 耐火建築物) \|\| (準防火地域内 && (耐火建築物 \|\| 準耐火建築物)) | +10% |
| 指定角地 \|\| 準角地 | +10% |

> 追加は加算, not 積

## 斜線制限

| 制限 | 用途地域 |
| --- | --- |
| 北側 | (第一種/第二種)(低層/中高層), 田園 | 
| 隣地 | ((第一種/第二種)低層 or 田園)以外 |
| 道路 | ALL |

### 道路斜線制限
- すべての用途地域に当てはまる
- 接する道路の反対側から1.25:1=縦移動:横移動の比率で斜線を引き、道路の反対側からXmだけ離れた (適用距離) 時点で垂直線へと変化する線を超えて建物を建てない制限
- セットバックすれば、斜線の開始起点もセットバック分離れる

```
                 |
                 |
 <-- 適用距離 --> |
                 |
                /
               /
              /
             /
            /
           /
          /
         /|
        / |
       /  |
      /   |
     /    |
    /     |
   /      | 1.25
  /       |
 /   1    |
/---------|
   Road   |  Land
```

### 隣地斜線制限

- 第一低層住居・第二低層住居・田園 **以外** (絶対高さ制限が10m or 12m)
- 勾配は、住居系は1.25
- 基準の高さは、住居系は20m
- 一定の高さ以上の部分の建物をセットバックすれば、斜線はセットバック分離れる (それ以下の部分をセットバックしても緩和はない)

```
                  |
                  |
                  |
                  |
                  /
                 /
                /
               /
              /
             /    2.5
            /
   <-- sb  /   1
/---------|-------- 31m
          |
          |
          |-- 12m
          |
  A Land  |  B Land
```

### 北側斜線制限

- 第一低層住居・第二低層住居・田園 (5m)・第一中高層・第二中高層 (10m) (高さ制限が)
- まほく (真北) 側は、より厳しい隣地制限 or より厳しい道路制限 (8m以上の道路であれば道路制限のほうが厳しい)

```
<------ true north

                  |
                  |
                  |
                  |
                  /
                 /
                /
               /
              /
             /    1.25
            /-----------12 m
   <-- sb  /   1
/---------|-------- 5m or 10m
          |
          |
          |
          |
  A Land  |  B Land
```

