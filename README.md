# k-card
## 吉安k包

### 规则简介
1. 去除扑克牌中大小鬼、四张2、四张3、四张8、四张A（剩下共36张牌、五人场七人场需要去掉一张K，剩35张牌、八人场加上四张A，剩40张牌）
2. 牌局人数包括三人场（每人12张牌）、四人场（每人9张牌）、五人场（每人7张牌）、六人场（每人6张牌）、七人场（每人5张牌）、八人场（每人5张牌）
3. 牌型包括单牌（4-K，4最小K最大，八人场A最大）、对子、顺子（至少三张连续单牌）、连对（至少两个连续的对子）、炸弹（至少3张相同点数的牌，炸弹大与前面所有牌形）
4. 玩法规则类似于斗地主。逆时针顺序出牌，所有玩家出牌必须大过上一家出的牌，如无法大过上家的牌或者不想出牌可以选择过，如一圈后所有玩家都选择过，当前玩家可以继续出任意牌。‘地主’玩家先手出牌，’地主‘玩家先打完手牌地主获胜、任一‘非地主’玩家先打完手牌则地主失败
5. 换牌机制。牌局开始由抓到红桃4或者上一牌局的‘地主’玩家先换牌。可以用自己的一张手牌更换其他的非‘K’（八人场非‘A’）的任一手牌。换完后，下一家可以根据自己的手牌情况选择是否换牌。一圈换牌结束，最后换牌的玩家成为地主。如一圈结束后换牌玩家只有一个，牌局立即结束，‘地主’直接获胜
6. ‘冲冲冲’。换牌之前如果有玩家认为自己的牌足够好，由抓到红桃4或者上一牌局的‘地主’玩家先选择是否‘冲’，选择‘冲‘直接成为‘地主‘开始牌局。一圈结束没有玩家‘冲’，则开始换牌阶段
7. 结算规则。游戏开始前玩家约定牌局基数‘M'以及‘冲’的倍数‘C’。换牌结算数 = 换牌次数 * M、冲结算数 = C * M。
