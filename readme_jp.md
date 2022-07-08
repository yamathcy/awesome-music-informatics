
# Awesome Music Infomatics in Japanese
このリストはREADME.mdの日本語版に加え，参考になる日本語の資料も追加で掲載しています． 日本語の資料には:jp:の絵文字をつけています．

このリストは，音楽情報処理に関するAwesomeな記事，チュートリアル，ライブラリ，Webページ等をまとめたものです．
もし新しい情報をリストに追加したい場合・記載した情報の誤り等があった場合は，issueにて山本（yamathcy）にお伝えいただければ幸いです．
リスト作成にあたり，slackグループ Openmusicinformatics（openmusicinformatics.slack.com）の皆様にご協力いただきました．ありがとうございます．

## Pythonライブラリ

### 音響信号処理
- Librosa https://librosa.org/ 音楽・音響情報処理の汎用ライブラリ
- madmom https://madmom.readthedocs.io/en/latest/ 音楽解析用のライブラリ．ビート解析等．深層学習モデルベースの処理も可能．
- essentia https://essentia.upf.edu/index.html 音楽信号に特化したライブラリ．特に音楽に関する特徴量を抽出可能．
- opensmile https://www.audeering.com/opensmile/ 音声感情認識用の特徴抽出ライブラリ．
- pyreaper https://github.com/r9y9/pyreaper 基本周波数抽出Reaperのpythonラッパー．
- pyworld https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder 音声分析合成WORLDのpythonラッパー．
- crepe https://marl.github.io/crepe/ 深層学習ベースの楽音の基本周波数抽出．
- kymatio https://www.kymat.io/ ウェーブレット散乱変換を行うライブラリ．
- pysndfx https://pypi.org/project/pysndfx/ エフェクトをかけるライブラリ．
- nnmnkwii https://github.com/r9y9/nnmnkwii 音声合成用のライブラリ．

### 楽譜情報処理
- music21 https://web.mit.edu/music21/　Music XMLのハンドリングと，音楽学的分析を行うためのライブラリ．
- pretty-midi https://craffel.github.io/pretty-midi/ Midiを扱うライブラリ．
- mido https://mido.readthedocs.io/en/latest/ Midiを扱うライブラリ．
- pypianoroll https://salu133445.github.io/pypianoroll/ Pythonでピアノロール形式のデータを楽に扱うためのライブラリ．
- muspy https://github.com/salu133445/muspy 音楽生成の処理（読み込み・前処理・生成の評価・生成音楽のデータ出力等）のパイプライン処理を行うライブラリ．
- miditok https://github.com/Natooz/MidiTok 音符をトークン化するライブラリ．
- miditoolkit: https://github.com/YatingMusic/miditoolkit シンボリックタイミング（tick）とピアノロールを両方考慮するMIDIパーサー　
- note_seq https://github.com/magenta/note-seq MIDIデータの操作，one-hot表現等機械学習モデルに適した形式への相互変換を行うライブラリ 

### Deep learning
- Torchaudio https://pytorch.org/audio/stable/index.html Pytorch用の音声処理ライブラリ
- tf.signal https://www.tensorflow.org/api_docs/python/tf/signal Tensorflow用の音声処理ライブラリ
- kapre https://github.com/keunwoochoi/kapre Tensorflow用の音声処理ライブラリ
- nnAudio https://github.com/KinWaiCheuk/nnAudio Pytorch用の音声処理ライブラリ　（リポジトリ内，↑でサポートする音声の特徴表現のリスト有）

### その他のライブラリ
- mir_eval https://craffel.github.io/mir_eval/ 自動採譜，メロディ検出，ビート認識などのタスクの評価と，アノテーションファイルのIO
- mirdata https://github.com/mir-dataset-loaders/mirdata 音楽情報処理のデータセットのハンドリング
- musdb https://github.com/sigsep/sigsep-mus-db 音楽音源分離データセットMUS-DBのインターフェース
- nussl https://github.com/nussl/nussl 音源分離ライブラリ
- pyroomacoustics https://github.com/LCAV/pyroomacoustics 音源分離ライブラリ
- magenta https://magenta.tensorflow.org/ Google発，AIに基づく音楽生成・創作ライブラリ
- muzic https://github.com/microsoft/muzic Microsoft発，AIに基づく音楽生成・創作ライブラリ
- omnizart https://music-and-culture-technology-lab.github.io/omnizart-doc/ 歌声（音符とピッチ）・ドラム・ピアノ・コードの採譜が可能なライブラリ
- spotipy https://spotipy.readthedocs.io/en/2.17.1/ spotify APIのpythonラッパー
- espnet https://github.com/espnet/espnet 各種音声処理のためのツールキット
- DDSP https://magenta.tensorflow.org/ddsp 微分可能信号処理DDSP
- ALTA https://github.com/emirdemirel/ALTA 歌詞認識のツールきっと
- Muskit https://github.com/SJTMusicTeam/Muskits 各種音楽情報処理のためのツールキット（現在開発中，2022年7月，歌声合成のみに対応）

## その他のソフトウェア・ライブラリ・WEBサイト等
- Tony https://www.sonicvisualiser.org/tony/ 歌声のピッチ・音符を分析・アノテーション可能なスタンドアロンなアプリ
- Sonic Visualiser https://www.sonicvisualiser.org/documentation.html さまざまな音楽信号を分析・アノテーション可能なスタンドアロンなアプリ
- sox http://sox.sourceforge.net/ コマンドラインで音声処理を行う
- AMPACT https://ampact.tumblr.com/ MATLAB製，演奏表現に関する音楽分析を行うスタンドアロンなアプリ
- essentia.js https://mtg.github.io/essentia.js/ WEB向けにessentiaをjsで動かせるようにしたJSライブラリ
- Songle https://songle.jp/ 産総研発，能動的音楽鑑賞（音楽要素に着目しながら好きな音楽を聴いていく・理解を深める）を行う
- Spleeter https://github.com/deezer/spleeter 高性能な音楽音源分離．歌声・ベース・ドラム・ピアノ等を分離可能
- lab.js https://lab.js.org/ WEB上で心理実験を行うためのJSライブラリ
- wavesurfer.js https://wavesurfer-js.org/ WEB上で音楽信号を可視化できるJSライブラリ
- WebAudio API https://developer.mozilla.org/ja/docs/Web/API/Web_Audio_API WEB上で音ファイルを扱うためのライブラリ
- curio audio annotator https://github.com/CrowdCurio/audio-annotator WEB上で環境音分析のアノテーションを行う
- Demucs https://github.com/facebookresearch/demucs　 音楽音源分離
- Basic Pitch https://basicpitch.spotify.com/　 ブラウザ内で完結可能なピッチ解析
- Meyda https://github.com/meyda/meyda WEB上で音響特徴量を解析可能なJSライブラリ
- :jp: TextALIVE https://textalive.jp/ 歌詞に基づくコンテンツ支援サービス
- :jp: Songrium https://songrium.jp/ 音楽視聴支援サービス

## データセット
- Audio Content Analysis http://www.audiocontentanalysis.org/data-sets/
- ISMIR Datasets https://ismir.net/resources/datasets/
- SigSep Multi-track https://sigsep.github.io/datasets/
- UPF-MTG datasets https://www.upf.edu/web/mtg/software-datasets
- paperwithcode https://paperswithcode.com/
- MCR https://github.com/dharasim/MCR/wiki
- FMA: A Dataset For Music Analysis https://github.com/mdeff/fma

## 書籍・講義・チュートリアル
- Fundamentals of Music Processing https://www.audiolabs-erlangen.de/fau/professor/mueller/bookFMP (Jupyter notebook: https://www.audiolabs-erlangen.de/resources/MIR/FMP/C0/C0.html) 音楽情報処理の基礎をまとめたもの．jupyter notebookつき．（難易度：易〜中）
- KAIST, GCT634 (AI613) Fall 2021. Musical Applications of Machine Learning https://mac.kaist.ac.kr/~juhan/gct634/index.html 深層学習を，音楽情報処理を題材に解説したもの．（難易度：中）
- Stanford CCRMA Notes https://musicinformationretrieval.com/ 音楽情報処理の各タスクを，事例中心に平易に解説したもの．（難易度：易）
- Audio Signal Processing for Music Applications https://ja.coursera.org/learn/audio-signal-processing Xavier Serra氏（スペイン，ポンペウファブラ大学）による音響信号処理の講義． （難易度：易）
- ISMIR Tutorials https://ismir.net/resources/tutorials/ 国際会議ISMIRで行われたチュートリアル（難易度：中）
- Handbook of Artificial Intelligence for Music: Foundations, Advanced Approaches, and Developments for Creativity https://www.springer.com/gp/book/9783030721152 人工知能の音楽への応用．
- Deep Learning Techniques for Music Generation: https://link.springer.com/book/10.1007/978-3-319-70163-9 深層学習ベースの音楽生成をまとめたもの．
- Preparation Course Python Notebooks https://github.com/meinardmueller/PCP 信号処理の基礎をまとめたもの．Jupyter notebookつき．
- Audio content analysis https://www.audiocontentanalysis.org/ 音データの分析方法について記述されたもの．
- A tutorial on AI music composition https://www.microsoft.com/en-us/research/uploads/prod/2021/10/Tutorial-on-AI-Music-Composition-@ACM-MM-2021.pdf  国際会議ACMMM2021で行われた，深層学習ベースの音楽生成のチュートリアル． 
- Open Source Tools & Data for Music Source Separation https://source-separation.github.io/tutorial/intro/src_sep_101.html   音楽音源分離のチュートリアル．
- Music-Recommendation-Tutorial-2017 https://www.slideshare.net/FabienGouyon/musicrecommendationtutorial2017　  音楽推薦のチュートリアル
- Music and Human-Computer Interaction https://link.springer.com/book/10.1007/978-1-4471-2990-5　音楽とヒューマンコンピュータインタラクション（HCI）の融合研究の事例集．
- :jp: ONGAACCELシンポジウム2020 https://www.youtube.com/watch?v=mmGCFzQFbJg プロジェクト「ONGA ACCEL（「次世代メディアコンテンツ生態系技術の基盤構築と応用展開）」の研究成果の公開シンポジウム
- :jp: Pythonで学ぶ音源分離 https://book.impress.co.jp/books/1119101154 
- :jp: Pythonで学ぶ音声認識 https://book.impress.co.jp/books/1120101083
- :jp: Pythonで学ぶ音声合成 https://book.impress.co.jp/books/1120101073
- :jp: Magentaで開発　AI作曲 https://www.ohmsha.co.jp/book/9784274227318/
- :jp: 関西学院大学 音楽情報処理 by 片寄晴弘先生 https://crestmuse.jp/klab/lecture/mi/ 
- :jp: NAIST 音情報処理 2018 by 中村哲先生 https://ahcweb01.naist.jp/lecture/2018/sp/
- :jp: 東京大学 応用音響学 2005 by 嵯峨山茂樹先生 https://ocw.u-tokyo.ac.jp/course_11270/
- :jp: 音楽はAI×トークンで扱おう！ by ヤマハ 鈴木正博様 https://speakerdeck.com/suzuqn/muana-20220629
- :jp: Pythonで学ぶ音楽信号分析と音楽アプリ開発 by Kurene様 https://www.wizard-notes.com/music-analysis

## サーベイ論文等
- Content-Based Music Information Retrieval: Current Directions and Future Challenges, Casey et al., 2008 https://ieeexplore.ieee.org/document/4472077?tp=&arnumber=4472077  音楽ファイルの”中身”に基づいて音楽を処理し，情報検索へ用いる，Content-based MIRについてのサーベイ
- A Survey of Music Recommendation Systems and Future Perspectives Song et al., 2012 https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.414.6614&rep=rep1&type=pdf　  音楽推薦システムのサーベイ
- Music Information Retrieval: Recent Developments and Applications, Schedl et al., 2014 https://www.nowpublishers.com/article/Details/INR-042   音楽情報検索のサーベイ
- Automatic Music Transcription: An Overview, Benetos et al., 2018 https://ieeexplore.ieee.org/document/8588423　  自動採譜のサーベイ
- Musical Source Separation: An Introduction, Cano et al., 2018 https://ieeexplore.ieee.org/document/8588410　  音楽音源分離のサーベイ
- Deep Learning for Audio-Based Music Classification and Tagging: Teaching Computers to Distinguish Rock from Bach, Nam et al., 2018 https://ieeexplore.ieee.org/document/8588424　  深層学習に基づく音楽分類・タギングのサーベイ
- Cross-Modal Music Retrieval and Applications: An Overview of Key Methodologies, Müller et al., 2018 https://ieeexplore.ieee.org/document/8588416　  マルチモーダルな音楽情報検索についてのサーベイ
- Audiovisual Analysis of Music Performances: Overview of an Emerging Field, Duan et al., 2018 https://ieeexplore.ieee.org/document/8588405　  音楽における音と映像のマルチモーダル学習についてのサーベイ
- An Introduction to Signal Processing for Singing-Voice Analysis: High Notes in the Effort to Automate the Understanding of Vocals in Music, Humphrey et al., 2018 https://ieeexplore.ieee.org/document/8588417　  歌声の分析と関連するMIRタスクについてのサーベイ
- Music performance analysis: A survey, Lerch et al., 2020 https://transactions.ismir.net/articles/10.5334/tismir.53/　  MIRにおける音楽演奏分析のサーベイ
- Deep Learning for Audio Signal Processing, Putwins et al., 2019 https://arxiv.org/abs/1905.00078　  音響データにおける深層学習のサーベイ
- A functional taxonomy of music generation systems, Herremans et al., 2017 https://dl.acm.org/doi/abs/10.1145/3108242?casa_token=qkSGMAo2GgUAAAAA:ojfdHvKlXLB8my1J8Fw3zBlOm7M59H9Meo-RSGsXKzvDJlN3fqsUFhb1fDX2jPismOgjBV8LsQRyBg　  音楽生成のサーベイ
- Automatic Melody Harmonization with Triad Chords: A Comparative Study, Yeh et al., 2021 https://arxiv.org/pdf/2001.02360.pdf　  音楽の和声づけ（Harmonization）のサーベイ
- A Survey on Recent Deep Learning-driven Singing Voice Synthesis Systems, Cho et al., 2021 https://arxiv.org/pdf/2110.02511.pdf 　  深層学習ベース歌声合成のサーベイ
- Music Composition with Deep Learning: A Review, Hernandez-Olivan et al., 2021 https://arxiv.org/abs/2108.12290　  深層学習に基づく音楽生成のサーベイ
- Melody Extraction from Polyphonic Music by Deep Learning Approaches: A Review Reddy M et al., 2022 https://arxiv.org/pdf/2202.01078.pdf　  混合音からメロディのピッチを推定する，メロディ検出のサーベイ
- 20th Anniversary of ISMIR, 2019. https://transactions.ismir.net/collections/special/20th-anniversary-of-ismir/　  ISMIR20周年特別ペーパー（各MIRのサブタスクの歴史の紹介等．）
- Music Emotion Recognition: Toward new, robust standards in personalized and context-sensitive applications., Gómez-Cañón et al., 2021
https://github.com/juansgomez87/datasets_emotion, https://ieeexplore.ieee.org/document/9591555　  音楽感情認識のサーベイ
- A Survey of Music Visualization Techniques., Lima et al., 2021 https://dl.acm.org/doi/pdf/10.1145/3461835　  音楽可視化のサーベイ
- Expression Control in Singing Voice Synthesis: Features, approaches, evaluation, and challenges., Bonada et al. 2015 https://ieeexplore.ieee.org/abstract/document/7298564　  歌声合成における，表現の制御に関するサーベイ
- A Comprehensive Survey on Deep Music Generation: Multi-level Representations, Algorithms, Evaluations, and Future Directions Ji et al., 2020 https://arxiv.org/abs/2011.06801　  深層学習に基づく音楽生成のサーベイ
- TOWARDS A (BETTER) DEFINITION OF THE DESCRIPTION OF ANNOTATED MIR CORPORA., Peeters et al., 2012 https://ismir2012.ismir.net/event/papers/025_ISMIR_2012.pdf   音楽のデータセットを新たに作るための観点の説明を行った論文

- :jp: 創作過程の分類に基づく自動音楽生成研究のサーベイ，松原ら． 2013 https://www.jstage.jst.go.jp/article/jssst/30/1/30_1_101/\_article/-char/ja/ 創作過程に基づいて既存研究を分類し，比較したサーベイ
- :jp: 音楽情報処理の最前線， 会誌「情報処理」　Vol.50 No.8. 2009 https://ipsj.ixsq.nii.ac.jp/ej/index.php?action=pages_view_main&active_action=repository_view_main_item_snippet&index_id=5735&pn=1&count=20&order=7&lang=japanese&page_id=13&block_id=8 多様な音楽情報処理の研究の紹介．
- :jp: 音楽を軸に広がる情報科学, 会誌「情報処理」　Vol.57 No.6. 2016 https://ipsj.ixsq.nii.ac.jp/ej/index.php?action=pages_view_main&active_action=repository_view_main_item_snippet&index_id=8409&pn=1&count=20&order=7&lang=japanese&page_id=13&block_id=8 
- :jp: 音楽情報処理のための深層学習, 阪上 2018　https://ipsj.ixsq.nii.ac.jp/ej/?action=pages_view_main&active_action=repository_view_main_item_detail&item_id=189869&item_no=1&page_id=13&block_id=8
- :jp: 2050年の情報処理： 21.Post-Truth音楽情報処理, 深山 2020 https://ipsj.ixsq.nii.ac.jp/ej/?action=pages_view_main&active_action=repository_view_main_item_detail&item_id=204414&item_no=1&page_id=13&block_id=8


## Awesomes
- awesome-awesome https://github.com/sindresorhus/awesome
- awesome-python-scientific-audio https://github.com/faroit/awesome-python-scientific-audio#music-information-retrieval
- awesome-music https://github.com/ciconia/awesome-music
- awesome-sheet-music https://github.com/ad-si/awesome-sheet-music
- awesome-audio-visualization https://github.com/willianjusten/awesome-audio-visualization
- awesome-deep-learning-music https://github.com/ybayle/awesome-deep-learning-music
- awesome-web-audio https://github.com/notthetup/awesome-webaudio
- awesome-musicdsp https://github.com/olilarkin/awesome-musicdsp
- awesome-data-labeling https://github.com/heartexlabs/awesome-data-labeling

## その他
- Music Technology conference list http://conferences.smcnetwork.org/ 音楽・音関係の国際会議の日程のリスト
- ISMIR community https://ismir.net/about/  国際会議ISMIRのグループ
- :jp: 音楽情報科学研究会（SIGMUS） http://www.sigmus.jp/
- :jp: 統計的文法理論と構成的意味論に基づく音楽理解の計算モデル https://www.jaist.ac.jp/is/labs/tojo-lab/kiban-A/index.html
- :jp: OngaCREST https://ongacrest.jp/
- :jp: OngaACCEL https://ongaaccel.jp/

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Yuya Yamamoto](https://sites.google.com/view/yamathcy) has waived all copyright and related or neighboring rights to this work.
