# meals
- 食事管理アプリ

## 仕様技術\
![](https://img.shields.io/badge/transparent-image-v2.0.1-blue)
![](https://img.shields.io/badge/flutter_riverpod-v2.3.2-blue)

## 画面仕様
カテゴリ画面 カテゴリタブ | カテゴリ画面 お気に入りタブ(アイテムなし) | カテゴリ画面 お気に入りタブ(アイテムあり)
--- | --- | ---
![カテゴリタブ](docs/categories_screen.png) | ![お気に入りタブ(アイテムなし)](docs/favorite_no_item.png) | ![お気に入りタブ(アイテムあり)](docs/favorite.png)
カテゴリタップで食事画面に遷移 | お気に入り未追加の場合 | お気に入り追加済の場合

サイドドロワー | 食事画面(フィルターなし) | 食事画面(フィルターあり)
--- | --- | ---
![サイドドロワー](docs/drawer.png) | ![食事画面(フィルターなし)](docs/meals.png) | ![食事画面(フィルターあり)](docs/meals_has_filter.png)
Meals: カテゴリ画面へ遷移<br/>Filter: フィルター画面へ遷移 | カテゴリごとの食事を表示 | フィルターの条件に合わせて表示

詳細画面(お気に入り未追加) | 詳細画面(お気に入り追加済) | フィルター画面
--- | --- | ---
![お気に入り未追加](docs/details.png) | ![お気に入り追加済](docs/add_favorite.png) | ![フィルター画面](docs/filter.png)
右上の☆が白抜き | 右上の☆が色付き | フィルターで選択した条件に合わせて食事画面の表示条件が変更される
