<script>

</script>

<template>
 <main>
        <div class="container">
            <div class="row pt-3">
                <div class="col-3">
                    <h3>Настройки профиля</h3>
                </div>
            </div>
            <hr>
            <div class="row" style="display: flex; gap: 40px;">
                <div class="col-1">
                    <h5 style="color: gray; font-weight: 400;">Анкета</h5>
                </div>
                <div class="col-1">
                    <h5>Аккаунт</h5>
                </div>
            </div>
            <hr>
            <div class="row">
                <div class="col-12" style="text-align: center;">
                    <h4>Смена пароля</h4>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <h5>Старый пароль</h5>
                    <div class="input-group mb-3">
                        <input type="password" class="form-control" placeholder="" aria-label="Name"
                            aria-describedby="basic-addon1">
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <h5>Новый пароль</h5>
                    <div class="input-group mb-3">
                        <input type="password" class="form-control" placeholder="" aria-label="Secondname"
                            aria-describedby="basic-addon1">
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <h5>Повторите новый пароль</h5>
                    <div class="input-group mb-3">
                        <input type="passoword" class="form-control" placeholder="" aria-label="Interests"
                            aria-describedby="basic-addon1">
                    </div>
                </div>
            </div>
            <hr>
            <div class="row" style="text-align: center;">
                <div class="col-12">
                    <h4>Смена почты</h4>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <h5>Новый адрес почты</h5>
                    <div class="input-group mb-3">
                        <input type="email" class="form-control" placeholder="" aria-label="About"
                            aria-describedby="basic-addon1">
                    </div>
                </div>
            </div>
            <div class="row pt-5">
                <div class="col-4">
                    <button id="save"><b>Сохранить изменения</b></button>
                </div>
            </div>
            </div>
    </main>

</template> 

<style>
#download, #save{
    background-color: white;
    color: #7ac97a;
    border-color: #90EE90;
    border-radius: 5px;
    padding-right: 15px;
    padding-left: 15px;
    text-align: center;
}
#delete, #add{
    background-color: white;
    border: none;
    color: gray;
    
}
#preview{
    background-color: white;
    color: #D3D3D3;
    border-color: #D3D3D3;
    border-radius: 5px;
    padding-right: 15px;
    padding-left: 15px;
    text-align: center;
}
/*
body{
    margin-left: 30px;
    margin-right: 30px;
}
*/
</style>