个人专属

设置初始化的时间：textAnimate
初始化花片数量：
``` json
    {
                        bloom: {
                    num: 100,
                    width: 1080,
                    height: 650,
                    // color: "rgb(190, 26, 37)",
                },
    }
```


整个区域的监听事件：
``` json
            canvaas.addEventListener('click', function (event) {
                // 获取点击位置相对于 canvas 的坐标
                const x = event.clientX - canvaas.getBoundingClientRect().left;
                const y = event.clientY - canvaas.getBoundingClientRect().top;

                // 在这里执行针对点击事件的操作
                console.log(`点击坐标：x=${x}, y=${y}`);
                alert("进行弹窗" + `点击坐标：x=${x}, y=${y}`);
            });

```