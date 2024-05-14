# 純26鍵帶調粵語三拼方案。本方案專注於使用粵語音碼精準快速輸入漢字
* 詞庫來自jyut6ping3詞庫，重點參考jyut6ping3方案
## 方案規則
### 首字母<br>
聲母20個，字母完全夠用。
### 身字母<br>
韻母50幾個，剛好係26個字母嘅兩倍上下，因此每個字母分配兩個韻母。
### 尾字母<br>
聲調6個，使用兩組字母表示，總共用12字母表示聲調，同身字母組合即可區分所有唔同嘅韻母同聲調。

# 設計及考慮嘅因素
1. 習慣、方便記憶以及傳統
2. 音素嘅使用頻率同鍵位嘅對應關係
3. 因鍵位數目所限而作兼容性處理
## 首字母=聲母
![alt text](https://github.com/yzswt/svjpgl/blob/main/initials.png?raw=true)
* 絕大多數聲母位於原jyutping所設計的鍵位
* z放在J，考慮到呢個係最常用嘅聲母之一，以及以上第1、2點
* j放在Y，考慮以上第1、2點
* kw放在Q，最低頻嘅聲母，考慮以上第2點
* gw放在R
* ng放在O
* 零聲母放在A
* 成音節m及ng分別作MM及OO
* jyut6ping3作g/k + u/ut/ui/un，本方案作R/Q (gw/kw)
## 身字母=韻母
韻母綜合考慮根據以上所有因素作安排
![alt text](https://github.com/yzswt/svjpgl/blob/main/vowels.png?raw=true)
* 韻母分主次，區分依據係頻率
* 根據音系特點，合併部分音位
* 合併長短對立嘅入聲韻
## 尾字母=聲調
![alt text](https://github.com/yzswt/svjpgl/blob/main/tones.png?raw=true)
* 聲調分爲中行、上行兩組，分別對應主次韻母
* 長短入聲韻嘅區分方法
  短1>>1，
  長3>>3，
  短6>>4，
  長6>>6，
  變調2>>2。極個別唔合規則者（長1及短3）併入各自聲調
  
  
# 例
### 玉宣拓思粵語三拼輸入法
### yzfswjtzlsej yywyue svjpgl suuyrrftl

# 重碼
* 重碼一般都係極個別邊緣音節，例如dap1/daap1，影響微乎其微，本方案爲求簡約，一律合併，不作進一步繁瑣嘅區分
