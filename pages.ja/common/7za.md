# 7za

> 圧縮率の高いファイルアーカイバです。
> `7z` よりも対応しているファイル形式は少ないですが、複数のプラットフォームに対応しています。
> もっと詳しく: <https://manned.org/7za>。

- ファイルまたはディレクトリを圧縮する:

`7za a {{アーカイブ.7z}} {{ファイルまたはディレクトリへのパス}}`

- 元のディレクトリ構造を保持したまま展開する:

`7za x {{アーカイブ.7z}}`

- 特定のアーカイブ形式を使用した圧縮を行う:

`7za a -t{{zip|gzip|bzip2|tar}} {{アーカイブ.7z}} {{ファイルまたはディレクトリへのパス}}`

- アーカイブの内容を表示する:

`7za l {{アーカイブ.7z}}`
