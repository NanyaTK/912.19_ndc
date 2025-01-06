# NDC コマンド
ディレクトリ移動や整理をNDCに基づいて実行するコマンド
## 注意書き
デフォルトの作業ディレクトリは/mnt/hです

## インストール
1. ダウンロードし，任意のディレクトリに配置します（本例ではルートディレクトリ）
1. rootディレクトリ（~）の.bash_aliasesを編集若しくは新規作成します
1. ```alias ndc='source ~/ndc'```を追記します
1. ```exec $SHELL -l```でシェルを再読み込みします

## 使い方
```  
  echo "cd shortcut               : ndc -d <folder_number>"
  echo "cd home                   : ndc -h"
  echo "show Directory structure  : ndc -s <target_path>"
  echo "auto folder manager       : ndc -a <folder_name>"
  echo "compress folder           : ndc -x"
```

## ライセンス
三条項BSDライセンスとします
