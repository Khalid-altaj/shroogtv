<template>
<div class="contact">

<div class="container">
<div class="bag">





<div class="modal-body">
<form>
<div class="form-group">
<label for="recipient-name" class="col-form-label">إسم المرسل </label>
<input type="text" class="form-control" id="recipient-name">
</div>


<div class="form-group">
<label for="recipient-name" class="col-form-label"> الرقم الوطني الخاص بك</label>
<input type="text" class="form-control" id="recipient-name">
</div>


<div class="form-group">
<label for="recipient-name" class="col-form-label"> رقم الهاتف الخاص بك </label>
<input type="text" class="form-control" id="recipient-name">
</div>


<div class="form-group">
<label for="recipient-name" class="col-form-label"> عنوان الايميل الخاص بك </label>
<input type="text" class="form-control" id="recipient-name">
</div>

<div class="form-group">
<label for="message-text" class="col-form-label">إجعل رسالتك بناءة</label>
<textarea class="form-control" id="message-text"></textarea>
</div>

</form>
</div>


<div class="modal-footer">
<button type="button" class="btn btn-primary">إرسال وجهة نظرك</button>
</div>
</div>
</div>
</div>



</template>




<style lang="scss" scoped>


.contact{
    padding-top: 120px;
    padding-bottom:40px;


    p{
        color: black;
        font-size: 20px;
        font-weight: bold;
        text-align: center;

    }


    .bag{
        width: 100%;     
        background-color: white;
        border: 2px solid white;
        box-shadow: 2px 5px 5px 2px rgba(0, 0, 0, .5);
    }

    label{
        float: right;
        color: black;
    }

    textarea{
        direction: rtl;
        height: 7rem;
       
      
    }

    input{
        direction: rtl;
       
       
    }

   button{
       background-color: #0b1e3a;
       color: white;
       font-weight: bold;
        
   }

   button:hover{
       background-color: gold;
   }
}
</style>