# 各組的期中報告與自評內容包括:

. 在 V-rep 模擬平台中, 展示各組所選定的鋼球運動系統, 是否可以完成至少兩個週期的循環運動?

. 各組頂球機構的位移、速度與加速度分析, 手動運算是否與程式驗算或 V-rep 模擬相符? . 詳細說明各組如何進行協同設計, 如何利用 Gitbook、Github 與近端或雲端主機增加設計流程效益?

. 提供各組鋼球運動系統的細部零件材料表、各零件工程圖與組立檔, 若使用 Solidworks, Inventor 或 Creo 請提供相關檔案, 若使用 Onshape, 請提供個別零組件與工程圖的網路連結.

. 所有組員的貢獻請各自使用學號登記下的 cd2018 倉儲展示, 各組期中報告則整理在各組的 Gitbook 中.

# 小組鋼球循環系統(onshape)

<img src="https://2018g3.gitbooks.io/cd2018/content/assets/46578978import.png">

onshape檔案:https://github.com/s40523115/cd2018/tree/gh-page

# 機構設計原理

本提球機構利用旋轉螺紋把球壓在送球機構的面上，球就會順的螺紋貼合著送球機構的面逐漸抬升上去。

# 摘要

跟小組討論從三個鋼球循環系統中，選出一個當作小組鋼球運動系統，並找找看是否有什麼嚴重的問題需要修改，大致上看完差不多後，使用v-rep進行模擬看是否能進行兩個周期的循環運動，如果不行，回去原始檔案看出什麼差錯，改完後繼續模擬。

# v-rep模擬

<img src="https://2018g3.gitbooks.io/cd2018/content/assets/54872178import.png">

# 遇到的問題

在vrep模擬時，傳動軸無法平穩地自轉，把球抬到該有的軌道上。

球在剛開始抬升的時候，會撞到送球機構，導致傳動軸不穩並把球擠出去。

# 解決方法

我在onshape上稍微更改了綁定的方式，把軌道以及送球軌道往上抬，使零件在爆炸的時候可以剛好炸到基板，後面再把除了基板以外的零件全部設為可碰撞。

把傳動軸的速度設為-300deg/s扭矩設N*m重量設5kg

檔案:https://github.com/s40523115/cd2018/tree/gh-page/vrep

影片:https://www.youtube.com/watch?v=bg7g1wUVAsg

# 零件表

<img src="https://2018g3.gitbooks.io/cd2018/content/assets/456789import.png">

# 結論:

很像是因為底板的關系，在vrep模擬時出了很多的問題，例如:沒有炸到自己想要的零件，傳動軸不會穩頂的旋轉，轉速太快或太慢導致鋼球上不去，所以花了十分多的時間去解決他們，但在最後我也獲益許多。
