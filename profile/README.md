<style>
    .colorchange1
    {
        animation: ColorChange1 12s infinite linear;
    }

    @keyframes ColorChange1 {
        0% {
            color: rgba(255,0,0,0.50)
        }
        5%{color: rgba(184,0,255,0.50)}
        10%{color: rgba(0,211,255,0.50)}
        30%{color: rgba(150,255,0,0.50)}
        40%{color: rgba(255,190,0,0.50)}
        95%{color: rgba(242, 255, 0, 0.5)}
        100% {
        color: rgba(255,0,4,0.50)
    }
    }
    .colorflow1
    {
        background: -webkit-linear-gradient(135deg,
        rgba(0,255,34,0.50),
        rgba(0,89,255,0.50) 15%,
        rgba(255, 234, 0, 0.5) 25%,
        rgba(0,253,255,0.50) 80%,
        rgba(255,0,113,0.50) 85%,
        rgba(0,255,140,0.50));
        /* 文字颜色填充设置为透明 */
        -webkit-text-fill-color: transparent;
        /* 背景裁剪，即让文字使用背景色 */
        -webkit-background-clip: text;
        /* 背景图放大一下，看着柔和一些 */
        -webkit-background-size: 200% 100%;
        /* 应用动画flowCss 12秒速度 无限循环 线性匀速动画*/
        -webkit-animation: flowCss 12s infinite linear;
    }

    @-webkit-keyframes flowCss
    {
        0% {
        /* 移动背景位置 */
            background-position: 0 0;
        }

        100% {
            background-position: -400% 0;
        }
    }

    h1:hover
    {
        -webkit-animation: flowCss 4s infinite linear;
    }
</style>
<img style="opacity:0.25;width:100%" src="https://github.com/user-attachments/assets/a4ca15d1-66e3-47e3-8cd1-d7c511bb805b">
<div id="header" align="center">
    <img src="https://github.com/user-attachments/assets/d21e73a0-dc8f-4b93-a664-3c2c34ebfb06" style="width:20%;" align="center">
    <h1 class="colorflow1"> Dragon Minecraft Softwares </h1>
    <p class="colorchange1"> - 我们用热爱构建我们的的Minecraft - <p>
</div>
