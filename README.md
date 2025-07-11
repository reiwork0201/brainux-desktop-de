# brainuxで多分動くと思われるdesktop DEとファイルマネージャとその他
aiで調べただけで実際には試してはないです。
300MB以下のRAMで動くGUI付きデスクトップ環境（DE）+ファイルマネージャの中で、実用性のある候補を絞って紹介します。

/////DEも含めて/////


JWM + ROX-Filer
50〜70MB
最軽量構成。デスクトップ背景なし、設定は手動。

LXDE + PCManFM
100〜150MB
軽量でGUI操作が快適。古いPCにも最適。

Openbox + PCManFM
80〜120MB
柔軟に構成可能。パネル追加で使いやすくなる。

LXQt + PCManFM-Qt
130〜180MB
Qt製で見た目が良い。標準構成が整っていて導入が簡単。

XFCE + Thunar
150〜200MB（最小構成で200MB以下も可）
見た目と操作性のバランスが良く、安定。

IceWM + ROX-Filer
80〜120MB
Windows 95風のUI。軽量ながらパネルも標準。

Fluxbox + SpaceFM
約100MB
タイル風WM。直感的な右クリック操作が可能。

twm + XFE
60〜80MB
X11初期の極限軽量WMとC製の爆速ファイラ。

pekwm + PCManFM
90〜110MB
右クリック中心のUI。ユニークな仮想デスクトップ管理。

Ratpoison + ROX-Filer
50MB台
マウス不要。キーボードのみの操作に特化。

Blackbox + PCManFM
70〜90MB
フラットでミニマルなテーマ。見た目が好みの人向け。





//////////////ここからファイルマネージャ//////////////


PCManFM
10〜30MB
LXDE標準。タブ対応で軽快、GVFSでネットワークも使える。

Thunar
30〜50MB
Xfce標準。拡張可能で安定した操作感。

ROX-Filer
5〜20MB
おそらく最軽量。爆速で起動、古いマシン向け。

XFE
20〜40MB
Windows風のUI。FOX Toolkitベースで軽量。

SpaceFM
20〜40MB
多ペイン・タブ・スクリプト対応の高機能ファイラー。

emelFM2
10〜20MB
2ペインのUNIX風。外部ツールとの連携に強い。

Worker
15〜30MB
2ペイン＋キーボード操作中心。Luaスクリプト対応。

gentoo
10〜20MB
古典的ファイルマネージャ。非常に軽く、基本機能のみ。

tuxcmd
30〜50MB
Total Commander風のUI。GTK1.2ベース。

Double Commander (GTK2/Qt4)
40〜80MB
2ペイン・タブ・FTP/ZIPなど豊富な機能。高機能軽量。

GNOME Commander
50〜90MB
Exif対応・リネーム・FTPなどフル装備な2ペイン型。

Dfm
5〜10MB
TinyCore向け。最低限のGUI機能、最軽量級。

xfm
10〜15MB
90年代風の超シンプルファイラー。

xplore
10〜15MB
Motif系UI。古典的な軽量2ペイン。

muCommander
約50MB
Javaベース。多機能でクロスプラットフォーム。

//////////////その他///////////////
Leafpad
10MB前後
メモ帳のような最軽量GUIテキストエディタ。

Mousepad
20MB前後
XFCE向け。UTF-8対応で軽快。

Geany
30〜50MB
軽量なプログラミング用GUIエディタ兼IDE。

vim / nano / micro
数MB
ターミナル用エディタ。最軽量クラス。

Geeqie
20〜40MB
高速で多機能な画像ビューア。

feh
5〜10MB
CLIベースの超軽量ビューア。スライドショー対応。

Viewnior
15〜30MB
非常に軽量なGUI画像ビューア。

mpv
30〜60MB
軽量で幅広いフォーマット対応のメディアプレイヤー。

Audacious
20〜40MB
音楽専用。Winamp風インターフェース。

smplayer
80〜150MB
mpv/mplayerベースでGUI付き。

Xterm
2〜5MB
最軽量のGUIターミナルエミュレータ。

URxvt
5〜10MB
美しい表示と軽さを両立。

LXTerminal
10〜20MB
LXDE標準ターミナル。使いやすい。

ROXTerm
10〜20MB
GTKベース。軽くて機能も必要十分。

Galculator
5〜10MB
GTKベースのシンプルで軽量な電卓。

xfburn
20MB
CD/DVD書き込みソフト。GUIあり。

ClipIt
5〜10MB
クリップボード履歴管理アプリ。GTKで軽快。


MuPDF
10〜20MB
超高速・軽量なPDFビューア。

EPDFView
15〜30MB
GTKベースのEvince軽量版。

zathura
10〜30MB
Vim風操作。プラグイン式で軽量。

Xarchiver
10〜20MB
GTKベース。多形式対応の軽量アーカイバ。

PeaZip（Qt版）
50〜100MB
多機能で圧縮形式豊富。

Ark（KDE）
約100MB
KDE系だが構成次第で軽量。

atool / p7zip / unzip
数MB
CLI専用の定番アーカイバ。最軽量。

dmenu
1〜2MB
超軽量ランチャー。Openbox/i3に最適。

rofi
5〜10MB
見た目が良く柔軟な設定が可能。

gmrun
約5MB
GTKベースの軽量な実行ランチャー。

Transmission (gtk/light)
20〜50MB
軽量なBitTorrentクライアント。

Pidgin
50〜80MB
軽量マルチプロトコルチャットクライアント。

w3m / lynx / links
5〜10MB
テキストブラウザ。超軽量。

nmtui
数MB
NetworkManager用のTUI設定ツール。

netcat / socat / curl / wget
1〜5MB
CLI定番。スクリプトでの通信にも便利。

htop
2〜5MB
視覚的な軽量プロセスモニタ。

conky
5〜10MB
デスクトップに各種情報を表示。

rsync
数MB
高速で高機能なファイル同期ツール。

fbreader
10〜20MB
ePub/Mobi/PDF対応の軽量電子書籍ビューア。

featherpad
20〜40MB
Qtベース。Notepad++風の軽量エディタ。

2048-qt / 2048-cli
〜10MB
超軽量パズル。気軽に遊べる。

DOSBox
20〜50MB
レトロなDOSゲーム用仮想環境。

OpenTTD（最低構成）
約100MB～
低スペックでも遊べる経営シム。

nInvaders / bastet / nethack
数MB
TUIで動作する名作CLIゲーム。

xpad
10MB以下
付箋アプリ。極めて軽量。

gtg（Getting Things GNOME）
30〜50MB
ToDoリスト管理。

osmo
30MB前後
カレンダー、メモ帳、連絡帳が一体。


EBView
10〜30MB
EPWINGや電子ブック形式に対応。GTKベースで表示が速く、マウス操作も可能。SHARP Brain辞書の閲覧にも応用可。

Qolibri
30〜60MB
EPWING・StarDict・EBXAなど対応。タブ型・マルチ辞書検索可能。Qt製で比較的軽量。完全オフライン動作。

GoldenDict（軽量設定）
約100MB
StarDictやDSL、Dictd、Babylonなど多形式に対応。CSS無効化で軽量に。音声や画像にも対応可能。

sdcv
5〜10MB
StarDict形式に対応したCUI辞書ビューワ。CLIでの高速検索に最適。スクリプト連携も可能。

eblook
5MB以下
EPWING/EB形式に対応。コンソールから使え、独自UIやAPI連携にも向く。

FBReader（＋辞書変換）
20〜30MB
辞書データをePubやテキストに変換すれば、ビューアとして使用可能。UIが整っていて読みやすい。

MuPDF / zathura（PDF辞書用）
10〜30MB
辞書をPDF化すれば高速に閲覧可能。検索やズームも対応。超軽量PDFビューア。




Sylpheed
20〜40MB
GTKベースで超軽量。POP3/IMAP対応。日本語も安定。署名やGPGにも対応。

Claws Mail
30〜60MB
Sylpheed派生で拡張性あり。ラベル・スレッド表示・RSSなど機能充実。

Balsa
30〜50MB
GNOME向け軽量クライアント。Mbox/Maildir対応。GPG署名対応。

Mutt / NeoMutt
10〜20MB
超軽量CLIメールクライアント。POP3/IMAP/SSL/PGPすべて対応。高いカスタマイズ性。

alpine
5〜10MB
カーソルキー操作が可能なTUIメールクライアント。IMAP/POP両対応。

mailx
数MB
スクリプト用のCLIメール送信ツール。添付ファイル対応。軽量で単機能。

msmtp
数MB
SMTP専用クライアント。sendmail互換でCLIからの送信に便利。
