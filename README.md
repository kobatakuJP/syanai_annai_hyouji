# syanai_annai_hyouji
LED式の社内案内表示を再現してみる

# ビットマップフォントを探す旅

- ビットマップフォントを使いたいがなかなか見つからない。
- 東雲フォントというものを見つけて以下からダウンロードした
- http://openlab.ring.gr.jp/efont/shinonome/
- → http://openlab.ring.gr.jp/efont/dist/shinonome/
- → http://openlab.ring.gr.jp/efont/dist/shinonome/shinonome-0.9.11p1.tar.bz2
- 上記を解凍し、いくつかある中の「shnmk14i.bdf」というファイルをもとにやってみる。
- → iはイタリックだこれ！無印の「shnmk14.bpf」を使うっす
- JIS(SJISですらない)のコード定義に沿っている・・・UTF-8からの変換が必要。これはつらい。
- 以下の対応表を持ってきた
  - http://ash.jp/code/jis0213_list.htm　で言及されてる以下のファイル
  - http://ash.jp/code/jisx0213-2004-std.txt