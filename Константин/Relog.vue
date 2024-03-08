

<template>
    <div class="center"">
        <div class="row pt-3">
            <div class="col-3 ">
                <h3>Войти</h3>
            </div>
        </div>
        <hr>
        <div class="row flex">
            <h4 style="text-align: center;">Ведите код доступа </h4>
            <div class="number">
                <div class="input-group mb-3">
                    <input autofocus type="text" class="form-control" aria-describedby="basic-addon1" id="1">
                </div>
            </div>
            <div class="number">
                <div class="input-group mb-3">
                    <input type="text" class="form-control" aria-describedby="basic-addon1" id ='2'>
                </div>
            </div>
            <div class="number">
                <div class="input-group mb-3">
                    <input type="text" class="form-control" aria-describedby="basic-addon1" id="3">
                </div>
            </div>
            <div class="number">
                <div class="input-group mb-3">
                    <input type="text" class="form-control" aria-describedby="basic-addon1" id="4">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default{
    data(){
        return {
            id: 1,
        }
    },
    methods: {
        next(){
            if (this.id!=4){
                this.id +=1
                document.getElementById("${this.id}").focus()
            }
        }
    }
}
</script>

<style scoped>
h4{
    margin-bottom: 40px;
}
.flex{
    display: flex;
    justify-content: space-between;
}
.row>* {
    padding-right: 0;

}
.center{
    padding: 0 30%;
}
.form-control{
    padding: .9rem .5rem;

}
.number{
    width: 19%;
}
</style>
