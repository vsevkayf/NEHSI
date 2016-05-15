---
layout: pageHE
language: he
title: צור קשר
permalink: /he/contactUs/
---

<style>
@import url(http://fonts.googleapis.com/css?family=Montserrat:400,700);

#form-div {
	background-color:rgba(72,72,72,0.4);
	padding-left:35px;
	padding-right:35px;
	padding-top:35px;
	padding-bottom:50px;
	width: 450px;
	float: left;
	left: 50%;
	position: absolute;
  	margin-top:30px;
	margin-left: -260px;
  	-moz-border-radius: 7px;
  	-webkit-border-radius: 7px;
}

.feedback-input {
	color:#3c3c3c;
	font-family: Helvetica, Arial, sans-serif;
  	font-weight:500;
	font-size: 18px;
	border-radius: 0;
	line-height: 22px;
	background-color: #fbfbfb;
	padding: 13px 13px 13px 54px;
	margin-bottom: 10px;
	width:100%;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	-ms-box-sizing: border-box;
	box-sizing: border-box;
  	border: 3px solid rgba(0,0,0,0);
}

.feedback-input:focus{
	background: #fff;
	box-shadow: 0;
	border: 3px solid #3498db;
	color: #3498db;
	outline: none;
  	padding: 13px 13px 13px 54px;
}

.focused{
	color:#30aed6;
	border:#30aed6 solid 3px;
}

/* Icons ---------------------------------- */
#name{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/name.svg);
	background-size: 30px 30px;
	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#name:focus{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/name.svg);
	background-size: 30px 30px;
	background-position: 8px 5px;
  	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#title{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/doc.svg);
	background-size: 30px 30px;
	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#title:focus{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/doc.svg);
	background-size: 30px 30px;
	background-position: 8px 5px;
  	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#company{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/CompanyName.svg);
	background-size: 30px 30px;
	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#company:focus{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/CompanyName.svg);
	background-size: 30px 30px;
	background-position: 8px 5px;
  	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#phone{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/Phone.svg);
	background-size: 30px 30px;
	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#phone:focus{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/Phone.svg);
	background-size: 30px 30px;
	background-position: 8px 5px;
  	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#email{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/Email.svg);
	background-size: 30px 30px;
	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#email:focus{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/Email.svg);
	background-size: 30px 30px;
  	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#HAU{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/planet.svg);
	background-size: 30px 30px;
	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#HAU:focus{
	background-image: url(http://vsevkayf.github.io/NEHSI/images/svg/planet.svg);
	background-size: 30px 30px;
  	background-position: 11px 8px;
	background-repeat: no-repeat;
}

#comment{
	background-image: url(http://rexkirby.com/kirbyandson/images/comment.svg);
	background-size: 30px 30px;
	background-position: 11px 8px;
	background-repeat: no-repeat;
}

textarea {
    width: 100%;
    height: 150px;
    line-height: 150%;
    resize:vertical;
}

input:hover, textarea:hover,
input:focus, textarea:focus {
	background-color:white;
}

#button-blue{
	font-family: 'Montserrat', Arial, Helvetica, sans-serif;
	float:left;
	width: 100%;
	border: #fbfbfb solid 4px;
	cursor:pointer;
	background-color: #3498db;
	color:white;
	font-size:24px;
	padding-top:22px;
	padding-bottom:22px;
	-webkit-transition: all 0.3s;
	-moz-transition: all 0.3s;
	transition: all 0.3s;
  	margin-top:-4px;
	font-weight:700;
}

#button-blue:hover{
	background-color: rgba(0,0,0,0);
	color: #0493bd;
}
	
.submit:hover {
	color: #3498db;
}
	
.ease {
	width: 0px;
	height: 74px;
	background-color: #fbfbfb;
	-webkit-transition: .3s ease;
	-moz-transition: .3s ease;
	-o-transition: .3s ease;
	-ms-transition: .3s ease;
	transition: .3s ease;
}

.submit:hover .ease{
  width:100%;
  background-color:white;
}

@media only screen and (max-width: 580px) {
	#form-div{
		left: 3%;
		margin-right: 3%;
		width: 88%;
		margin-left: 0;
		padding-left: 3%;
		padding-right: 3%;
	}
}
</style>



<div class="form-div">
	<form action="https://getsimpleform.com/messages?form_api_token=39dda43c5bb42c646bc0a41d973c9a36" method="post">
		<div class="form-field">
			<input name="name" type="text" placeholder="שם" id="name" class="validate[required,custom[onlyLetter],length[0,100]] feedback-input" required>
		</div>
		<div class="form-field">
			<input name="title" type="text" placeholder="תואר" id="title" class="validate[required,custom[onlyLetter],length[0,100]] feedback-input" required>
		</div>
		<div class="form-field">
			<input name="company Name" type="text" placeholder="חברה" id="company" class="validate[required,custom[onlyLetter],length[0,100]] feedback-input" required>
		</div>
		<div class="form-field">
			<input name="phone" type="tel" placeholder="טלפון" id="phone" class="validate[required,custom[onlyNumber],length[0,20]] feedback-input" required>
		</div>
		<div class="form-field">
			<input name="email" type="email" placeholder="אימייל" class="validate[required,custom[email]] feedback-input" id="email" required>
		</div>
		<div class="form-field">
			<input name="How did you hear about us" type="text" placeholder="איך שמעת עלינו?" id="HAU" class="validate[required,length[0,100]] feedback-input" required>
		</div>
		<div class="form-field">
			<textarea name="comments" placeholder="הודעה" class="validate[required,length[6,300]] feedback-input" id="comment" required></textarea>
		</div>
		<input type="submit" class="btn btn-default" value="שלח/י" id="button-blue">
	</form>
</div>

