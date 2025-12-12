# MyDiary について

MyDiary は日記投稿システムです

## 機能リスト

1. 日記管理機能
   - 投稿機能
   - 編集機能
1. ログイン認証機能

## ページ構成

| URL         | 内容         |
| :---------: | ------------ |
| /home       | トップページ |
| /diary/list | 日記一覧     |

---

## メソッドについて
メソッド名は、`setName(String name)`のようにキャメルケースにしてください。

```java
public void setName(String name) {
    this.name = name;
}
```