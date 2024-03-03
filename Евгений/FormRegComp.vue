<script>

</script>
<template>
  
  
  
  
  
  
  <div class="cont">

    <div class="mb-3 nickname form">
  <label for="exampleFormControlInput1" class="form-label">Введите никнейм</label>
  <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Никнейм">
</div>

   <div class="mb-3 emal form">
  <label for="exampleFormControlInput1" class="form-label">Введите почту</label>
  <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
</div>

  <div class="mb-3 pasword form">
  <label for="exampleFormControlInput1" class="form-label">Введите пароль</label>
  <input type="password" class="form-control" id="exampleFormControlInput1" placeholder="Пароль">
</div>

    </div>
    

</template>

<style scoped>
 @import url('https://fonts.cdnfonts.com/css/rubik');
    html, template, label   {
        font-family: 'rubik';
    }
    #app {
        font-family: 'rubik';
    }
.cont{
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    width: 35%;
    padding: 20px;
}
.form{
    width: 100%;
}
.head hr {
  width: 90%;
}
.form-control{
  border-radius: 10px;
  height: 30px;
}

</style>