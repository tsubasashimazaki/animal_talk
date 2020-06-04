<template>
   <div id="thread">
       <div class="thread-inner">
           <ul>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
               <li><div class="threadMessage">こんにちは</div></li>
           </ul>
       </div>
       <form class="text-center">
  <div class="form-group">
    <label for="threadInputTitle">件名</label>
    <input type="text" class="form-control" id="threadInputTitle" placeholder="件名を入力してください">
  </div>
  <div class="form-group">
    <label for="threadInputContent">本文</label>
    <input type="text" class="form-control" id="threadInputContent" placeholder="本日の出来事を入力してみよう">
  </div>
  <button type="submit" class="btn btn-primary text-center">こちらの内容で送信<i class="fas fa-paw"></i></button>
</form>
   </div>
</template>

<script>
    export default { //コンポーネントがエクスポートされた場合に存在する
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
