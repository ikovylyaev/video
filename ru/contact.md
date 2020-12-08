---
layout: page
title: контакты / ru
permalink: /ru/contact/

text-title-nav: Иван Ковыляев
background: http://photo.uralphoto.tk/photo/02769.jpg
lang: ru
text-title: контакты
text-description:
---
<div class="row p-0 m-0">
    <h2 class="col-12" style="opacity: 1;">почта</h2>
      <div class="card col-6" style="background: #000;">
        <div class="card-body">
          <h4>mail@ikovylyaev.com</h4>
        </div>
      </div>
      <div class="card col-6" style="background: #000;">
        <div class="card-body">
          <h4>ikovylyaev@bk.ru</h4>
        </div>
      </div>
  <h2 class="col-12 mt-3">contact us</h2>
  <form action="https://formspree.io/ikovylyaev@bk.ru" method="POST" style="width: 100%; padding: 1.25rem;">
    <input type="text" class="form-control form-control-lg" name="name" placeholder="имя, фамилия"><br>
      <input class="form-control form-control-lg" type="email" name="_replyto" placeholder="email">
    <br>
    <input class="form-control form-control-lg" type="text" placeholder="сообщение..." name="message"><br>
    <div class="custom-control custom-checkbox">
      <input type="checkbox" class="custom-control-input" id="checker">
      <label class="custom-control-label" for="checker">я согласен с <a href='{{site.url}}/terms'>пользовательским соглашением</a> и <a href='{{site.url}}/policy'>политикой в отношении обработки персональных данных</a></label>
    </div>
		<button class="btn btn-outline-light mt-3" id='send-btn' disabled type="submit">отправить</button>
		<div class="nl-overlay"></div>
		<input type="hidden" name="_subject" value="Order from ikovylyaev.com">
	    <input type="text" name="_gotcha" style="display:none">
	    <input type="hidden" name="_next" value="http://ikovylyaev.com/mail/">
	</form>
</div>
<script>
$('#checker').click(function(){
  if ($(this).is(':checked')){
		$('#send-btn').removeAttr('disabled');
	} else {
		$('#send-btn').attr('disabled', 'disabled');
	}
});
</script>
<style>
*{color: #fff;}
.container{margin-top: 20px;}
.card-body h4 a{color: #fff;}
.card-body h4{text-align: center;}
.card-body{background: #151515; border-radius: 1rem;}
/* general style for the form */
.card{width: 50% !important; box-shadow: none !important; border-width: 0px;}
.form-control{background: #151515; border-radius: 0.25rem; border-color: #151515; color: #eee;}
.form-control:focus{background: #000;}
.add-mb{margin-bottom: 30px;}
main.page .text-page h1 {color: #151515;!important}
.form-control:focus{color: #ffffff!important;}
</style>
