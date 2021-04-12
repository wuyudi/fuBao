<script>
  let 主题 = "罚款";
  let 主体 = "公司";
  let 目标 = "五百强";
</script>

<div id="input">
  主题 <input type="text" bind:value={主题} />
  <label for="主体"> 主体 </label> <input type="text" bind:value={主体} />
  <label for="目标"> 目标 </label>
  <input type="text" bind:value={目标} />
</div>
<div style="width:700px;">
  <div style="margin-left:auto;margin-right:auto;width:500px;">
    <p>
      关于{主题}，我个人认为，能被{主题}是一种巨大的福气，很多{主体}想被{主题} 都没有机会。如果你{主体}正年轻的时候不被{主题}，你什么时候可以被{主题}？
    </p>
    <p>
      你{主体}一辈子没有被{主题}，你觉得你就很骄傲了？ 这个世界上，我们每一个{主体}都希望成功，都希望成为{目标}，都希望被尊重，我请问大家，你不搞二选一，你怎么能够实现你想要的成功？
    </p>
    <p>
      这世界上被{主题}的{主体}很多，比它辛苦、比它努力、比它聪明的{主体}很多，但并不是所有被{主题}的{主体}都有这个机会真正做一些有价值、有意义并且还能够有成就感的事。所以今天这些{主体}能够被{主题}，我认为是这些{主体}修来的福报。你去想一下没有什么收入的{主体}，你去想一下明天可能要倒的{主体}，你去想想做了很多努力根本没有用的{主体}……
      跟他们相比，直到今天，我依然这么觉得，被{主题}很幸运。
    </p>
  </div>
</div>

<style>
  div {
    margin-left: auto;
    margin-right: auto;
    width: 100px;
  }
  p {
    display: block;
    width: 500px;
    text-indent: 2em;
  }
</style>
