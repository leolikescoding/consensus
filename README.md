# consensus
new fast consensus

```
after reading paper from phantom GHOSTDAG
and paper from conflux project , i have the idea why not 
try to design it in a more direct way.
i am discussing this with conflux cto Ming Wu , no any response from him yet.
```
Conflux Design:

![conflux  design](https://github.com/leolikescoding/consensus/blob/main/WechatIMG42.png)

```
My Idea:
the yellow one is the traditional pow main chain
every block could reference any of the lower-hash-power blocks 
a simiple order-function can be assigned to the referenced blocks.
```

![my design concept](https://github.com/leolikescoding/consensus/blob/main/WechatIMG41.jpg)




```
Eth :
Eth actually use a rewarding pre-forks incentive method , this actually not increase the tps.
In our design we encourage the random selection mechanism to increase the tps which is used in both
conflux and phantom design.

```

![eth design](https://github.com/leolikescoding/consensus/blob/main/WechatIMG11.png)