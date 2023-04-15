<div>
    <p class="trash">a</p>
    <h1 class="texts">
        現在準備中
    </h1>
    <h2 class="texts">
        背景画像がバグってるから<br>改行して無理矢理引き伸ばしてるサイトだね！
    </h2>
    <h3 class="texts">
        svelteって難しいね！
    </h3>
    <p class="trash">a</p>
</div>

<style>
    div {
        background: center / contain no-repeat url($lib/assets/yutasaba.jpg);
        background-color: rgba(40, 40, 40, 0.751);
        background-blend-mode: darken;
        background-size: auto;
    }
    .trash {
        color: rgba(0, 0, 0, 0);
    }
    .texts {
        text-align: center;
        position: relative;
    }
    h1 {
        text-shadow: 0px 0px 15px rgba(119, 230, 119, 0.589);
        color: white;
        font-size: 1000%;
    }
    h2 {
        text-shadow: 0px 0px 15px rgb(119, 230, 119, 0.897);
        color: white;
        font-size: 500%;
    }
    h3 {
        text-shadow: 0px 0px 15px rgb(119, 230, 119, 0.897);
        color: white;
        font-size: 300%;
    }
</style>