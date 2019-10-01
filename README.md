# Project2-1_Enigma_machine

## Naming style
### ROLL_NUMBER
### snake_case

##想法
###main.py, input > plugboard > 轉盤 > plugboard > output, 第一個輸入為I, 把I與全部的字母配對後進入轉盤階段, 出來時的字母與H做配對, 此時會存有2個配對組合, 進入下一個字母P, 找配對組合中是否有P與他人配對過, 如果有就把配對的字母丟入轉盤階段, 如果沒有, 一樣跟全部字母都配對過一次, 出來後的字母檢查後再與E配對, 以此類推, 如果配對過的字母跟目前要配對的不同, 就可跳過, 把10個字母都成功的配對組合、轉盤順序跟起始位置存起來.
###decoding.py, 此時的起始位置是輸入138字之後的起始位置, 輸入IPQHUGCXZM之後才會是HEILHITLER, 所以把起始位置回推138字之後就是真正的起始位置了, 再把那一長串丟進去解碼, 看有沒有形成一個句子囉~

## 工作分配
###  1051438張友澤 找出最初始plugboard位置的可能  15%
###  1051535楊宗霖 幫忙測試code結果對比答案正確性  15%
###  1051524莊子毅 編寫基本enigma功能 各種plugboard的可能   15%
###  1051433葛東昇 轉盤輪轉debug 利用接電板組合去編寫一份first_letter.py但答案與正解不一樣  15%
###  1051518李政憲 找出我們這組固定轉盤的 PLUGBOARD,找出最後答案  20%
###  1051434蔡適謙 開GIT 初始code  20%
