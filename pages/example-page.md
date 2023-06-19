---
title: Example Page
permalink: /example-page/
---
<style>
	.container{
		width: 1170px;
	}
		.col-3 {
    width: 25%;
    PADDING: 0 15px;
}
	.col-4 {
    width: 33.33%;
    PADDING: 0 15px;
}
		.col-6 {
    width: 50%;
    PADDING: 0 15px;
}
		.col-12 {
    width: 100%;
    PADDING: 0 15px;
}
	header#navigation.full-width .row {
    max-width: 100%;
}
ul.social-share.p-inline-list li.list__item {
    display: inline-block;
    margin-right: 10px;
}
ul.social-share.p-inline-list {
    margin-top: 20px;
    margin-right: 15px;
    list-style: none;
}
ul.social-share.p-inline-list li.list__item a {
    color: #00477e;
    font-size: 22px;
}
.banner{
    background-image: url(./../images/banner.jpg);
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: cover;
    height: 720px;
    background-color: #D6C4AF;
}
header#navigation .p-navigation__tagged-logo a.p-navigation__link {
    padding: 0;
    margin-top: 8px;
}
.banner_block img {
    width: 350px;
}
.banner_block {
    display: flex;
    align-items: center;
    height: 720px;
}
a.p-button.btn {
    border-color: #01436b;
    background-color: transparent;
    border-radius: 30px;
    color: #01436b;
    margin-top: 30px;
    font-weight: 600;
}
.p-navigation [class*=p-navigation__item].is-selected > .p-navigation__link::before{
    display: none;
}
.p-navigation [class*=p-navigation__item] > .p-navigation__link {
    color: #000;
    font-weight: 600;
}
.p-navigation [class*=p-navigation__item].is-selected > .p-navigation__link {
    color: #01436b;
}.p-navigation__items {
    margin-top: 4px;
}

// Features 
section.feature{
    background-image: url(./../images/feature_bg.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
img.arrow-btn {
    width: 70px;
}
.video_ {
    position: relative;
}
.feature_block .inner a:hover {
    opacity: 0.8;
}
a.play_btn {
    position: absolute;
    left: 0;
    right: 0;
    top: 50%;
    z-index: 99999;
    width: 120px;
    height: 120px;
    margin: 0 auto;
    margin-top: -60px;
}
.feature .heading h2 {
  font-family: $font-secondary;
  font-size : 30px;
  line-height : 50px;
  color : #01436B;
}
.feature_block .inner{
    height: 300px;
    width: 100%;
    background-image: linear-gradient(#4089a1, #638aa1, #4089a1);
    border-radius: 30px;
    box-shadow: 0 0px 5px 0 rgba(0,0,0,0.4);
    padding: 30px;
}
.feature_block .inner h3 {
    font-family: $font-primary;
    font-size: 21px;
    line-height: 34px;
    color: #D0D0D0;
}
.feature_block .inner a {
    position: absolute;
    right: 10px;
    bottom: 0px;
}
.feature_video p {
    font-size: 22px;
    line-height: 36px;
    color: #1E1E1E;
    margin-bottom: 10px;
}
.feature_video h3 {
    color: #07477C;
    font-size: 26px;
    font-weight: bold;
    margin-bottom: 0;
}
.feature_video .content_ {
    margin-top: 20px;
}
.feature_video a.read_more {
    font-family: $font-primary;
    font-weight: bold;
    font-size: 18px;
    line-height: 50px;
    color: #07477B;
    text-decoration: underline;
}
.u-align--center{
	text-align: center
}

// Action 
.action_b p {
    font-family: Myriad Pro;
    font-size: 22px;
    line-height: 34px;
    color: #07477B;
}
.action_b{
    display: flex;
    align-items: center;
}
section.action {
    background-image: url(./../images/action-bg.jpg);
    background-position: left bottom;
    background-repeat: no-repeat;
    background-size: cover;
}

.action h2 {
    font-family: Playfair Display;
    font-size: 42px;
    color: #191919;
    line-height: 52px;
}
.action_2 h2 {
    font-family: Playfair Display;
    font-size: 42px;
    line-height: 52px;
    color: #191919;
}
.action2_b p {
    font-size: 24px;
    line-height: 37px;
    color: #375780;
    margin-top: 30px;
    margin-bottom: 10px;
}
.action2_b a.read-more {
    font-size: 24px;
    line-height: 37px;
    color: #375780;
    text-decoration: underline;
    font-weight: bold;
}

.action_3 h2 {
    line-height: 52px;
    font-size: 42px;
    font-family: 'Playfair Display';
}

a.p-button.btn {
    padding: 10px 30px;
}
.action_{
    background-image: url(./../images/action3-bg.png);
    background-position: 0 -70px;
    background-repeat: no-repeat;
    background-size: cover;
}
ul.social-share.p-inline-list li.list__item a img {
    width: 20px;
}

a.p-button.btn:hover {
    background-color: #01436b;
    color: #fff;
}
.p-navigation [class*=p-navigation__item] > .p-navigation__link:hover {
    color: #01436b;
}

.container.action_3 {
    background-color: #C7C6C2;
}

@media (max-width: 1024px){
    .feature .heading h2 {
        font-size: 29px;
        line-height: 39px;
    }
    .feature_block:not(:last-child) {
        margin-bottom: 30px;
    }
    .feature_block .inner h3 {
        font-size: 30px;
        line-height: 40px;
    }
    a.play_btn {
        width: 80px;
        height: 80px;
        margin-top: -40px;
    }
    .feature_video.col-6:not(:last-child) {
        margin-bottom: 30px;
    }
    .action_b p {
        font-size: 18px;
        line-height: 28px;
    }
    .banner_block img {
        width: 180px;
    }
    a.p-button.btn {
        padding: 4px 20px;
    }
    .banner {
        background-size: 163% 55%;
        height: 460px;
        background-color: #D6C4AF;
        background-position: 100% 100%;
    }
    
    .action_2 h2 {
        font-size: 25px;
        line-height: 36px;
    }
    .action2_b p {
        font-size: 15px;
        line-height: 28px;
    }
    .action2_b a.read-more {
        font-size: 18px;
        line-height: 28px;
    }
    .action_3 h2 {
        line-height: 38px;
        font-size: 28px;
    }
    footer .u-align--right {
        text-align: left!important;
    }
    footer p {
        margin-top: 2px;
    }
    .action h2 {
      
        font-size: 28px;
        line-height: 38px;
    }
    .action h2 br {
        display: none;
    }
    .action .row.m-t-60 {
        margin-top: 0px;
    }
    .action_ {
       
        background-position: 0px -22px;
    }
    section.action {
        background-image: none;
       
        background-color: #e6e6e6;
    }
    .p-navigation__banner {
        padding-left: 0;
    }
    .p-navigation__logo {
        width: 179px;
    }
    .p-navigation [class*=p-navigation__item] > .p-navigation__link {
        padding-left: 0;
        background-color: transparent!important;
    }
    ul.social-share.p-inline-list {
        display: none;
    }
    header#navigation .p-navigation__tagged-logo a.p-navigation__link {
        padding: 0;
        margin-top: 4px;
        margin-bottom: 4px;
    }
    a.p-navigation__toggle--open {
        font-size: 20px;
    }
    a.p-navigation__toggle--close {
        font-size: 20px;
    }
    .p-navigation .p-navigation__nav .p-navigation__link::before{
        display: none;
    }
}
@media(max-width: 500px){
    
    .banner_block {
        align-items: unset;
        height: unset;
        display: block;
        margin-top: 42px;
    }
}
@media(min-width: 500px)and (max-width: 1024px){
    .banner {
        height: 360px;
        background-size: contain;
       
    }
    .banner_block {
        height: 360px;
    }
    .video_ img {
        width: 100%;
    }
    
}
	
	.p-t-80 {
	padding-top: 80px;
	}
	.p-b-80{
	padding-bottom: 80px;
	}
	
	</style>





<section style="width: 100%" class="feature p-t-80 p-b-80">

<div style="width: 1170px;" class="container">

<div class="row">

<div style="margin-bottom: 60px" class="heading u-align--center">

<h2>When creating a Lasting Power of Attorney (LPA) &amp; Advance Care Plan (ACP) <br><strong>how would you describe your situation?</strong></h2>

</div>

</div>

<div class="row">

<div class="feature_block col-3">

<div class="inner">

<h3>I’m unsure how to begin</h3>

<a href="#"><img alt="The Legacy" class="arrow-btn" src="![](/images/arrow-icon.svg)"></a>

</div>

</div>

<div class="feature_block col-3">

<div class="inner">

<h3>I would like to speak to my family first</h3>

<a href="#"><img alt="The Legacy" class="arrow-btn" src="![](/images/arrow-icon.svg)"></a>

</div>

</div>

<div class="feature_block col-3">

<div class="inner">

<h3>I’m concerned about losing control of my assets and decision-making</h3>

<a href="#"><img alt="The Legacy" class="arrow-btn" src="![](/images/arrow-icon.svg)"></a>

</div>

</div>

<div class="feature_block col-3">

<div class="inner">

<h3>I’m unsure who are the best people to appoint</h3>

<a href="#"><img alt="The Legacy" class="arrow-btn" src="![](/images/arrow-icon.svg)"></a>

</div>

</div>

</div>

<div style="margin-top: 60px" class="row">

<div class="feature_video col-12">

<div class="video_">

<img alt="The Legacy" src="![The Legacy](/images/video-1.png)">

<a class="play_btn" href="#"><img alt="The Legacy" src="![The Legacy](/images/play-button.svg)"></a>

</div>

</div>

</div>

  

<div class="row m-t-30">

<div class="feature_video col-6">

<div class="video_">

<img alt="The Legacy" src="![The Legacy](/images/video-2.png)">

<a class="play_btn" href="#"><img alt="The Legacy" src="![Play Video](/images/play-button.svg)"></a>

</div>

<div class="content_">

<h3>Lasting Power of Attorney</h3>

<p>A Lasting Power of Attorney (LPA) allows you to appoint a trusted individual or individuals to make decisions on your behalf when you lose mental capacity.</p>

<a class="read_more" href="#">Read More</a>

</div>

</div>

<div class="feature_video col-6">

<div class="video_">

<img alt="The Legacy" src="![The Legacy](/images/video-3.png)">

<a class="play_btn" href="#"><img alt="The Legacy" src="![The Legacy](/images/play-button.svg)"></a>

</div>

<div class="content_">

<h3>Advanced Care Plan</h3>

<p>An Advanced Care Plan (ACP) outlines your healthcare preferences when you are no longer able to express them yourself.</p>

<a class="read_more" href="#">Read More</a>

</div>

</div>

</div>

</div> 
</section>

<section style="padding-top:80px; padding-bottom: 110px; width: 100%;" class="action">
    <div class="container">
      <div class="row">
        <div class="action_b col-6">
          <img alt="The Legacy" src="./src/images/action.png">
        </div>
        <div class="col-6 action_b">
          <div class="inner">
            <p>End-of-life planning may feel overwhelming and even a bit scary, but taking control of your future and making your wishes known can be one of the most empowering and compassionate decisions you'll ever make – not only for yourself but also for your loved ones.</p>
            <p>Making a <strong>Lasting Power of Attorney</strong> (LPA) and an <strong>Advanced Care Plan</strong> (ACP) can bring about peace of mind and reduce uncertainty for those who care about you the most.</p>
          </div>
        </div>
      </div>
      <div style="margin-top:60px;" class="row">
        <div class="col-12 action_b u-align--center">
            <h2>Leave a <strong><i>legacy of love</i></strong> and certainty for<br> the people who matter most to you. Here are <br>some ways to get started.</h2>
             </div>
      </div>
    </div>    
   
  </section>