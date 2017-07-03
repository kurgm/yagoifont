# 851フォント

8:51:22 pm さん ([@pm85122](https://twitter.com/pm85122)) [曰く](https://twitter.com/pm85122/statuses/492011400479268866):

> うごメモ時代に　フリー素材として  
> ていきょう　していた　文字（フォント）  
>   
> あるていどは　にほんごを　表示できるが  
> まだまだ　実用的というには　ほどとおい  
>   
> かくすう順に　かんじを　作成しているので  
> 小学校で　習うような　字が　まだ  
> 表示できないところが　アレ  
>   
> 半角カタカナも　未対応　かなしいね  

## 生成

`python Bitmap2OTF/bitmap2otf/bitmapotf.py data/yagoifont.json`


## データソース

- https://dl.dropboxusercontent.com/u/77785050/851font_all.png
  (2015/2/5 に取得)

- 『851フォント Ver 0.36α』（うごメモはてなから）
-- `D9936E_0C1DFDCFD7553_002_nnn.gif` （nnn はページ番号）がそれです

- くろごまが作成した縦書き用グリフ（回転・移動・反転などを施しました）


## 現在対応している文字の概要

- 半角・全角英数字
- ひらがな・カタカナ
- 漢字（第一水準の1〜14画、ほか。ただし14画は途中）
- 組文字
- ギリシャ文字
- キリル文字
- アルメニア文字
- 記号、空白文字、その他


### 外字

Unicode に収録されていない文字は外字領域に割り当てています：

|     Unicode    |   Shift_JIS    |          割り当てられている文字           |
|----------------|----------------|------------------------------------------|
|U+E000 〜 U+E009|0xF040 〜 0xF049|手書き風の数字 0〜9                        |
|U+E00A          |0xF04A          |ガンダム                                  |
|U+E00B          |0xF04B          |たいと                                    |
|U+E00C          |0xF04C          |http://glyphwiki.org/wiki/u4a3b-itaiji-001|
|U+E00D          |0xF04D          |「純」の欠画                               |
|U+E00E          |0xF04E          |ビャンビャン麺のビャン                     |


## 既知の問題

- (「功」の下に「天」)の字をとりあえず「巭」（「功」の下に「夫」）に割り当てています

