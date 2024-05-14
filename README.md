# trpc-csv-upload(動作検証)

## 概要
[trpc公式のformdata](https://github.com/trpc/trpc/tree/main/examples/.experimental/next-formdata)の実装そのままでcsv uploadができることを確認した。

## 手順
* `git clone`する
* `pnpm i`する
* `pnpm dev`する
* `http://localhost:3003/react-hook-form`にアクセスする
* `MOCK_DATA.csv`をuploadする
* `apps/trpc/public/{数値}/}`にMOCK_DATA.csvが保存されていることを確認する
* vs codeのcompareコマンドなどでuploadしたファイルと保存されたファイルに差分がないことを確認sる

## appendix
* csvは[mockaroo](https://www.mockaroo.com/)で作成している
