## nextセットアップ
npx create-next-app@latest --typescript
https://nextjs.org/docs/getting-started

プロジェクト名を指定
一階層下にフォルダができるので注意

## gh repo create
pushできるようにする

## nextUIセットアップ
手順に従う
https://nextui.org/docs/guide/getting-started


## prisma(server)のセットアップ
https://www.prisma.io/docs/getting-started/quickstart

npm install prisma --save-dev
npx prisma init --datasource-provider sqlite

warn You already have a .gitignore file. Don't forget to add `.env` in it to not commit any private information.

Next steps:
1. Set the DATABASE_URL in the .env file to point to your existing database. If your database has no tables yet, read https://pris.ly/d/getting-started
2. Run prisma db pull to turn your database schema into a Prisma schema.
3. Run prisma generate to generate the Prisma Client. You can then start querying your database.


## .envをgitignoreに追加

## sqltoolsを使う（別になんでも）→Windowsだとエラーが出たのでやめる

https://vscode-sqltools.mteixeira.dev/en/home/

## schema追加, migration実施
npx prisma migrate dev --name init

dbが作成される
あとprismaclientもinstallされた

以下dbファイルはgitignoreに入れる

*.db
*.db-journal


## lib/prisma.ts作成
こっちの公式を採用
https://www.prisma.io/docs/guides/database/troubleshooting-orm/help-articles/nextjs-prisma-client-dev-practices
こっちは古いためかエラー出る
https://github.com/prisma/prisma-examples/blob/latest/typescript/rest-nextjs-api-routes-auth/lib/prisma.ts


## components/Post.tsx作成

削除
Rowしか子にできない為

## post.tsx作成

https://github.com/prisma/prisma-examples/blob/latest/typescript/rest-nextjs-api-routes-auth/pages/index.tsx

## zodインストール

npm install zod --save

https://zenn.dev/mizchi/articles/1c35fdcc77065c02f631


## formidableインストール

npm i formidable @types/formidable --save

https://zenn.dev/masumomo/articles/971424e0515c71

formidableのparseがcallbackなので、同期式にならない

navbar
menu
dashboard
import
master
transaction


csvを取り込む
https://zenn.dev/tatsuyasusukida/articles/nodejs-csv-rea

tsvを取り込む
delimiterを\t

テーブルで表示
https://nextui.org/docs/components/table

チェックを実行
logic

文言を作成
logic

mini tableを作るとか


データベースに登録する
データベースから読み込む
prisma


取り込み画面
適当なCSVを取り込む
登録する
テーブルに表示する

nodeのassertでチェックする
jest使えば？
https://qiita.com/okazuki/items/991a068892e946531612

https://zenn.dev/miruoon_892/articles/e42e64fbb55137


Rechartよさそう
https://github.com/recharts/recharts
https://zenn.dev/acha_n/articles/how-to-customize-recharts



react-markdown
https://github.com/remarkjs/react-markdown