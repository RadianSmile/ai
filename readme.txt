1. T(s,a,s') 不太懂為什麼要這樣表示，實做起來明明是 qValue = T(a,s')
2. 剛開始學習時一直有個盲點：S -> a -> 只會對應一個 State ，後來發現，在同一個 state 使用同一個 action 是有機會產生不同 state 的
