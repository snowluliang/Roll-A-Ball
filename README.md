# Roll-A-Ball
Game made with Unity
- 详情
![](https://github.com/snowluliang/Roll-A-Ball/blob/master/Roll-a-ball/game.png)

- 吃完黄色方块,晋级
``` 
void SetCountText()
    {
        countText.text = "Count: " + count.ToString();
        if (count >= 12)
        {
            winText.text = "You Win!";
        }
    }
```
