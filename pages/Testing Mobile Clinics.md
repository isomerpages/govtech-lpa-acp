---
title: Testing Mobile Clinics
permalink: /testing-mobile-clinics/
variant: markdown
description: ""
---
<style>
  /* cyrillic */
  @font-face {
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFkD-vYSZviVYUb_rj3ij__anPXDTnohkk7yRZrPJ-M.woff2) format('woff2');
    unicode-range: U+0301, U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
  }
  /* vietnamese */
  @font-face {
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFkD-vYSZviVYUb_rj3ij__anPXDTnojUk7yRZrPJ-M.woff2) format('woff2');
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+0300-0301, U+0303-0304, U+0308-0309, U+0323, U+0329, U+1EA0-1EF9, U+20AB;
  }
  /* latin-ext */
  @font-face {
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFkD-vYSZviVYUb_rj3ij__anPXDTnojEk7yRZrPJ-M.woff2) format('woff2');
    unicode-range: U+0100-02AF, U+0304, U+0308, U+0329, U+1E00-1E9F, U+1EF2-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
  }
  /* latin */
  @font-face {
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFkD-vYSZviVYUb_rj3ij__anPXDTnogkk7yRZrPA.woff2) format('woff2');
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+0304, U+0308, U+0329, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
  }
  /* cyrillic */
  @font-face {
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 500;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFkD-vYSZviVYUb_rj3ij__anPXDTnohkk7yRZrPJ-M.woff2) format('woff2');
    unicode-range: U+0301, U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
  }
  /* vietnamese */
  @font-face {
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 500;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFkD-vYSZviVYUb_rj3ij__anPXDTnojUk7yRZrPJ-M.woff2) format('woff2');
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+0300-0301, U+0303-0304, U+0308-0309, U+0323, U+0329, U+1EA0-1EF9, U+20AB;
  }
  /* latin-ext */
  @font-face {
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 500;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFkD-vYSZviVYUb_rj3ij__anPXDTnojEk7yRZrPJ-M.woff2) format('woff2');
    unicode-range: U+0100-02AF, U+0304, U+0308, U+0329, U+1E00-1E9F, U+1EF2-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
  }
  /* latin */
  @font-face {
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 500;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFkD-vYSZviVYUb_rj3ij__anPXDTnogkk7yRZrPA.woff2) format('woff2');
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+0304, U+0308, U+0329, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
  }
  /* cyrillic */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTjYgEM86xRbPQ.woff2) format('woff2');
    unicode-range: U+0301, U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
  }
  /* vietnamese */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTPYgEM86xRbPQ.woff2) format('woff2');
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+0300-0301, U+0303-0304, U+0308-0309, U+0323, U+0329, U+1EA0-1EF9, U+20AB;
  }
  /* latin-ext */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTLYgEM86xRbPQ.woff2) format('woff2');
    unicode-range: U+0100-02AF, U+0304, U+0308, U+0329, U+1E00-1E9F, U+1EF2-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
  }
  /* latin */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 400;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTzYgEM86xQ.woff2) format('woff2');
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+0304, U+0308, U+0329, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
  }
  /* cyrillic */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 600;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTjYgEM86xRbPQ.woff2) format('woff2');
    unicode-range: U+0301, U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
  }
  /* vietnamese */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 600;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTPYgEM86xRbPQ.woff2) format('woff2');
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+0300-0301, U+0303-0304, U+0308-0309, U+0323, U+0329, U+1EA0-1EF9, U+20AB;
  }
  /* latin-ext */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 600;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTLYgEM86xRbPQ.woff2) format('woff2');
    unicode-range: U+0100-02AF, U+0304, U+0308, U+0329, U+1E00-1E9F, U+1EF2-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
  }
  /* latin */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 600;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTzYgEM86xQ.woff2) format('woff2');
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+0304, U+0308, U+0329, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
  }
  /* cyrillic */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 800;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTjYgEM86xRbPQ.woff2) format('woff2');
    unicode-range: U+0301, U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
  }
  /* vietnamese */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 800;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTPYgEM86xRbPQ.woff2) format('woff2');
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+0300-0301, U+0303-0304, U+0308-0309, U+0323, U+0329, U+1EA0-1EF9, U+20AB;
  }
  /* latin-ext */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 800;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTLYgEM86xRbPQ.woff2) format('woff2');
    unicode-range: U+0100-02AF, U+0304, U+0308, U+0329, U+1E00-1E9F, U+1EF2-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
  }
  /* latin */
  @font-face {
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 800;
    font-display: swap;
    src: url(https://fonts.gstatic.com/s/playfairdisplay/v30/nuFiD-vYSZviVYUb_rj3ij__anPXDTzYgEM86xQ.woff2) format('woff2');
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+0304, U+0308, U+0329, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
  }
  @font-face {
      font-family: 'proxima_nova_bold';
      src: url('http://chodri.com/legacy/src/fonts/Proxima-Nova-Alt-Bold-webfont.woff2') format('woff2');
      font-weight: normal;
      font-style: normal;
  }
  @font-face {
      font-family: 'Myriad Pro';
      src: url('http://chodri.com/legacy/src/fonts/Myriad-Web-Pro-Regular.ttf');
      src: url('http://chodri.com/legacy/src/fonts/Myriad-Web-Pro-Regular.ttf') format('truetype');
      font-weight: normal;
      font-style: normal;
  }
  .container{
    width: 100%;
  margin: 0 auto;
  }
	.eventToday h2 {
    color: #07446B;
    font-weight: bold;
}
	
    section{
    width: 100%;
    }
    .col.is-8.is-offset-2.print-content {
      margin-left: 0;
      width: 100%;
  }
  section.bp-section {
  padding: 0;
  }
  section.bp-section .bp-container {
  padding-bottom: 0!important;
  }
	.eventToday{
	padding: 90px 0 120px 0;
	}
	strong {
    color: #07446B!important;
    font-weight: 700;
}
  .m-b-80{
  margin-bottom: 80px;
  }
    .content a {
      color: #01436b;
  }
    table {
    font-family: arial, sans-serif;
    border-collapse: collapse;
    width: 100%;
    border: 1px solid #dddddd;
  }
  
  td, th {
    border: 1px solid #dddddd
    text-align: left;
    padding: 8px;
    border-width: 1px!important;
  }
	.eventB p {
    font-weight: 500;
}
  th{
    background-color:#D4DFF1;
		 font-size: 19px;
    }
  tr.bg {
    background-color: #83A1D3;
  }
    .m-b-40{
    margin-bottom: 40px;
    }
    .play_today h3 {
      font-size: 30px;
      color: #000;
      font-weight: 400;
      margin-bottom: 0;
    font-family: 'Playfair Display';
    font-style: italic;
  }
    .p-b-110{
    padding-bottom:110px;
    }
  .play_today p {
      margin-top: 10px;
      color: #000;
      font-size: 16px;
  }
    .play_today {
      padding: 30px;
      background-color: #DACBBC;
  }
  .content ul > li:last-child {
      margin-bottom: 0;
  } 
  .eventBlock ul.meta {
    list-style: none;
    padding-left: 0;
    margin: 0;
}
  .heading h3 {
    font-size: 26px;
    color: #000;
    margin-bottom: 30px;
}
.eventBlock p {
    font-size: 15px;
    line-height: 26px;
    color: #000;
    margin-top: 20px;
} 
  .m-t-30{
  margin-top: 30px;
  }
  .eventBlock h4 {
    margin-top: 30px!important;
    display: inline-block;
    margin-bottom: 11px;
}
section.event_banner {
    padding-top: 45px;
}	
  .eventBlock h4 a {
    font-size: 22px;
    font-weight: 600;
    text-decoration: none;
    color: #01436b;
}
.event_banner h1 {
    font-family: Playfair Display;
    font-style: italic;
    font-size: 70px;
    color: #07446B;
}	
.eventBlock ul.meta li {
    font-size: 15px;
    margin: 0!important;
  color: #000;
}
  .eventBlock ul.meta img {
    width: 21px;
    float: left;
    margin-right: 10px;
    margin-top: 6px;
}
	.event_banner h1 span {
    display: block;
    margin-left: 107px;
    font-family: 'Playfair Display';
}
  container-fluid{
  width: 100%;
  }
  section.bp-section.is-small.bp-section-pagetitle {
  display: none;
  }
	a.btn {
    padding: 13px 70px;
    background-color: #01436b;
    color: #fff;
    text-decoration: none;
    font-size: 16px;
    border-radius: 30px;
	    white-space: nowrap;
}
	
a.btn.disabled {
		background-color: #666;
		pointer-events:none;
	  cursor: not-allowed;
	}
	a.btn:first-child {
    margin-right: 30px;
}
a.btn:nth-child(2) {
    margin-right: 30px; 
}
  a.p-button.btn {
      background-color: transparent;
      border-radius: 30px;
      color: #000;
      margin-top: 10px;
      font-weight: 600;
      text-decoration: none;
      padding: 10px 30px;
      background-color: #a5ded1;
      border: 1px solid #a5ded1;
    display: inline-block;
      margin: 0;
  }
  .content strong {
      color: #000;
  } 
	.offset-1{
	margin-left: 8.33%;
	}
  section.bp-section .bp-container {
      width: 100%!important;
      max-width: 100%!important;
      padding-top: 0!important;
  }
  .col.is-8.is-offset-2.print-content {
      margin-left: 0;
      width: 100%;
  }
  .col-3 {
      width: 25%;
      PADDING: 0 15px;
  }
  .col-8 {
      width: 75%;
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
	.col-10 {
      width: 83.33%;
      PADDING: 0 15px;
  }
  .p-t-80 {
    padding-top: 80px;
  }
  .p-b-80{
    padding-bottom: 80px;
  }
  .u-align--center{
    text-align:center;
  }
    .m-b-30{
    margin-bottom: 30px;
    }
    .m-b-60{
    margin-bottom: 60px;
    }
    .m-t-40{
    margin-top: 40px;
    }
    .m-t-80{
    margin-top: 80px;
    }
    .p-t-40{
    padding-top:40px;
    }
    @media(max-width: 767px){
      .p-lr-50{
    padding: 0;
    }
		.offset-1{
	margin-left: 0;
	}
    html {
      overflow-x: hidden;
  }
  .container {
      width: 100%;
      padding: 0 15px;
  }
        .col-3 {
      width: 100%;
  }
      .col-8 {
      width: 100%;
  }
    .col-4 {
      width: 100%;
  }
  .col-6 {
      width: 100%;
  }
  .col-12 {
      width: 100%;
  }
    }
  @media(min-width: 767px)and (max-width: 1140px){
    .container {
      padding: 0 15px;
  }
    }
    section.event_banner {
      background-color: #D0B69A;
  }
  .event_banner img {
      height: 350px;
      object-fit: contain;
      object-position: bottom;
  }
    .heading h2,.play_today h3 {
      color: #000;
      font-family:'Playfair Display';
      font-weight: 400;
  }
      .heading h2,.upcoming {
      color: #000;
      font-family:'Lato';
      font-weight: 400;
  }
  a.btn:hover {
    color: #fff;
    text-decoration: none;
    opacity: .9;
}
    @media(max-width: 767px){
    .events::before {
    display:none;
    }
	.col-10 {
      width: 100%;
  }
	a.btn:first-child {
    margin-right: 2px;
}
    .event_banner img {
      height: 300px;
  }
    }
        @media(min-width: 767px)and (max-width: 1140px){
    .container {
      padding: 0 15px;
      width: 100%;
  }
    }
	
	    ul li { padding: 5px 0px; }

    </style>
  <section class="event_banner">
    <div class="container-fluid">
      <div class="row">
        <div class="col-12 banner_b u-align--center">
					<h1>Plan <span>Today</span></h1>
        <img alt="Legacy Events" src="https://i.imgur.com/f6S7lBG.png">
        </div>
      </div>
    </div>
 </section>
<section class="eventToday">
<div class="container">
	<div class="row">
		<div class="col-10 offset-1 eventB u-align--left">

<strong><p>Thank you for supporting our 'Plan Today' roadshows and mobile clinics organised by the Agency for Integrated Care, Office of the Public Guardian, and My Legacy, to raise awareness about the Lasting Power of Attorney (LPA) and Advance Care Plan (ACP). We will update with upcoming events once details are ready.</p></strong>

<p> For more information on how to start your pre-planning journey by making an LPA and ACP, visit <a href="mylegacy.life.gov.sg/find-a-service/lpa-acp/">mylegacy.life.gov.sg/find-a-service/lpa-acp</a>. The application fee for Singapore Citizens to apply for LPA Form 1 is waived until 31 March 2026.</p>

<p>To book an appointment with an LPA Certificate Issuer (CI) or ACP facilitator near you, visit <a href="mylegacy.life.gov.sg/find-a-service">mylegacy.life.gov.sg/find-a-service</a>.</p>

<p>If you require in-person assistance, you may approach ServiceSG Centres, or call our hotlines:</p>
			<li>MSF -  for queries on LPA: 1800 111 2222</li>
			<li>AIC -  for queries on ACP: 1800 650 6060</li>
		
<p>Individuals with financial needs may access the following resources:</p>
	<section class="p-b-110">
    <div class="container">
      <div class="row">
        <div class="col-12">
      <table style="background-color:#fff" class="table table-striped table-inverse table-responsive">
       <tbody><tr>
					<th>To certify your LPA</th>
					<th>To find an ACP facilitator</th>
        </tr>
                <tr><td scope="row">
									<p>Approach the following organisations to certify your LPA:</p>
									<ul>
									<li>Life Point's LPA One-Stop Services</li>
	<li>Potter's Place Community Services Society (applicants will have to pass a means test)</li>
		<li>Mount Alvernia Outreach Medical Clinic @ Enabling Village (only for referrals from MSF or social service organisations and persons with disability)</li>
										</ul>
		</td>
				<td scope="row"> 
<p>If you are receiving medical care at a public healthcare institution, you can ask your care team to arrange an ACP session for you.</p>
<p> If you are not receiving treatment at any public healthcare institution, you can contact a community ACP facilitator. </p>
<ul>
	<li> Find a community facilitator at: <a href="https://mylegacy.life.gov.sg/find-a-service/find-advance-care-plan-facilitator">https://mylegacy.life.gov.sg/find-a-service/find-advance-care-plan-facilitator/</a>.
                </li>
			</ul>
		 </td>
				</tr></tbody></table></div></div></div></section></div></div></div></section>