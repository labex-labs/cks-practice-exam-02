# CKS 模擬試験 02

## 言語

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![CKS 模擬試験 02](https://course-cover.labex.io/cks-practice-exam-02.png?lang=ja)](https://labex.io/ja/courses/cks-practice-exam-02)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ja/courses/cks-practice-exam-02)

CKS 試験の全範囲を網羅した、実践的なセキュリティシナリオに基づく 20 問の Kubernetes セキュリティ課題で構成される、独立した第 2 回模擬試験です。

![kubernetes](https://img.shields.io/badge/kubernetes-whitesmoke?style=for-the-badge&logo=kubernetes)
![cks](https://img.shields.io/badge/cks-whitesmoke?style=for-the-badge&logo=cks)


## 演習

|   インデックス | 名前                               | 難易度   | 練習                                                                                                                                           |
|----------|----------------------------------|-------|----------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 🎯  ノードメタデータへのワークロードアクセスを拒否する     | 中級    | <a target='_blank' href='https://labex.io/ja/labs/deny-workload-access-to-node-metadata-663200?course=cks-practice-exam-02'>チャレンジを開始</a>     |
|       02 | 🎯  Kubelet 露出に関する CIS 調査結果のレビュー  | 中級    | <a target='_blank' href='https://labex.io/ja/labs/review-cis-findings-for-kubelet-exposure-663211?course=cks-practice-exam-02'>チャレンジを開始</a>  |
|       03 | 🎯  分割された Ingress ルートのための TLS 再発行 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/reissue-tls-for-a-split-ingress-route-663206?course=cks-practice-exam-02'>チャレンジを開始</a>     |
|       04 | 🎯  名前空間オペレーターのロールのスコープ設定         | 中級    | <a target='_blank' href='https://labex.io/ja/labs/scope-a-namespace-operator-role-663214?course=cks-practice-exam-02'>チャレンジを開始</a>           |
|       05 | 🎯  漏洩した ServiceAccount トークンの封じ込め | 上級    | <a target='_blank' href='https://labex.io/ja/labs/contain-a-leaked-serviceaccount-token-663199?course=cks-practice-exam-02'>チャレンジを開始</a>     |
|       06 | 🎯  API サーバープロキシ昇格のブロック           | 上級    | <a target='_blank' href='https://labex.io/ja/labs/block-api-server-proxy-escalation-663197?course=cks-practice-exam-02'>チャレンジを開始</a>         |
|       07 | 🎯  ホストデバッグサービスの無効化               | 中級    | <a target='_blank' href='https://labex.io/ja/labs/disable-a-host-debug-service-663202?course=cks-practice-exam-02'>チャレンジを開始</a>              |
|       08 | 🎯  ホストログ収集者の権限制限                 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/restrict-host-log-collector-permissions-663210?course=cks-practice-exam-02'>チャレンジを開始</a>   |
|       09 | 🎯  テナントの Pod セキュリティ境界の適用         | 中級    | <a target='_blank' href='https://labex.io/ja/labs/apply-tenant-pod-security-boundaries-663196?course=cks-practice-exam-02'>チャレンジを開始</a>      |
|       10 | 🎯  アプリケーションシークレットのローテーションと制限     | 中級    | <a target='_blank' href='https://labex.io/ja/labs/rotate-and-constrain-application-secrets-663212?course=cks-practice-exam-02'>チャレンジを開始</a>  |
|       11 | 🎯  DNS 例外を用いたテナントエグレスの分離         | 上級    | <a target='_blank' href='https://labex.io/ja/labs/isolate-tenant-egress-with-dns-exceptions-663204?course=cks-practice-exam-02'>チャレンジを開始</a> |
|       12 | 🎯  Web Pod からの HostPath キャッシュの削除 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/remove-hostpath-cache-from-a-web-pod-663208?course=cks-practice-exam-02'>チャレンジを開始</a>      |
|       13 | 🎯  信頼できるイメージレジストリの強制             | 上級    | <a target='_blank' href='https://labex.io/ja/labs/enforce-trusted-image-registries-663203?course=cks-practice-exam-02'>チャレンジを開始</a>          |
|       14 | 🎯  署名済みリリース・マニフェストの検証            | 中級    | <a target='_blank' href='https://labex.io/ja/labs/validate-a-signed-release-manifest-663215?course=cks-practice-exam-02'>チャレンジを開始</a>        |
|       15 | 🎯  イメージからビルドシークレットを削除する          | 上級    | <a target='_blank' href='https://labex.io/ja/labs/remove-build-secrets-from-an-image-663207?course=cks-practice-exam-02'>チャレンジを開始</a>        |
|       16 | 🎯  KubeLinter を使用した Helm 出力のスキャン | 中級    | <a target='_blank' href='https://labex.io/ja/labs/scan-helm-output-with-kubelinter-663213?course=cks-practice-exam-02'>チャレンジを開始</a>          |
|       17 | 🎯  監査証跡からのポリシー復元                 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/restore-policy-from-audit-evidence-663209?course=cks-practice-exam-02'>チャレンジを開始</a>        |
|       18 | 🎯  ビーコン通信を行うワークロードの隔離            | 上級    | <a target='_blank' href='https://labex.io/ja/labs/quarantine-a-beaconing-workload-663205?course=cks-practice-exam-02'>チャレンジを開始</a>           |
|       19 | 🎯  ランタイムファイルドリフトの検出              | 中級    | <a target='_blank' href='https://labex.io/ja/labs/detect-runtime-file-drift-663201?course=cks-practice-exam-02'>チャレンジを開始</a>                 |
|       20 | 🎯  侵害されたジョブトークンの封じ込め             | 上級    | <a target='_blank' href='https://labex.io/ja/labs/contain-a-compromised-job-token-663198?course=cks-practice-exam-02'>チャレンジを開始</a>           |

## LabEx について

[LabEx](https://labex.io) は、コーディングとテクノロジーに特化したインタラクティブな実践学習プラットフォームです。ラボ、AI 支援、仮想マシンを組み合わせて、ビデオなしの実践的な学習体験を提供します。動画なしの独自の実践ラボによる厳格な「実践による学習」アプローチ、ブラウザ内のインタラクティブなオンライン環境で自動化されたステップバイステップのチェック機能、スキルツリーベースのシステムによる構造化されたコンテンツ組織、30 のスキルツリーと 6,000 以上のラボを含む成長し続ける学習リソースにより、[LabEx](https://labex.io) は包括的な実践教育を提供します。プラットフォームには、最新の AI モデルを基盤とした学習アシスタント Labby が含まれており、対話型学習体験を提供します。

## その他

- 🔗 [CKS トレーニング プログラミングコース](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [CKS トレーニング プログラミングプロジェクト](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [CKS トレーニング 無料チュートリアル](https://github.com/labex-labs/cks-free-tutorials)

