---
title: WIP PG 4
permalink: /wills/wip-pg-4/
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
   font-family: 'Myriad Pro';
   src: url('http://chodri.com/legacy/src/fonts/Myriad-Web-Pro-Regular.ttf');
   src: url('http://chodri.com/legacy/src/fonts/Myriad-Web-Pro-Regular.ttf') format('truetype');
   font-weight: normal;
   font-style: normal;
   }
   .container{
   width: 1170px;
   margin: 0 auto;
   }
   .heading  {
   position: relative;
   }
   section.bp-section {
   padding: 0;
   }
   .action__b h4{
   color: #000;
   font-size: 24px;
   margin-top: 15px;
   margin-bottom: 0;
   }
   .action__b h4 a{
   color: #01436b;
   } 
   section.bp-section .bp-container {
   padding-bottom: 0!important;
   }
	.col.is-2.is-position-relative.has-side-nav {
    display: none;
}
	.col.is-1.has-float-btns.is-position-relative {
    display: none;
}
	section.bp-section.bottom-navigation {
    display: none;
}
	.col.is-8.is-offset-1-desktop {
    margin-left: 0;
    width: 100%;
}
   .accordion ul .inner span {
   margin-right: 15px;
   }   
   .m-b-80{
   margin-bottom: 80px;
   }
   container-fluid{
   width: 100%;
   }
   section.bp-section.is-small.bp-section-pagetitle {
   display: none;
   }
   .col.is-2.is-position-relative.has-side-nav {
   display: none;
   }	
   .col.is-8.is-offset-1-desktop.is-12-touch.print-content {
   margin-left: 0;
   width: 100%;
   }	
   .about_a_b img {
   width: 460px;
   }
   .content ul > li:last-child {
   margin-bottom: 0;
   }
   .video_acc .inner::after{
   display:none!important;
   }
   a.p-button.btn {
   border-color: #01436b;
   background-color: transparent;
   border-radius: 30px;
   color: #01436b;
   margin-top: 30px;
   font-weight: 600;
   text-decoration: none;
   border: 1px solid #01436b;
   padding: 10px 30px;
   }
   .action_3 h2, .action_3 h2 i {
   line-height: 52px;
   font-size: 42px;
   font-family: 'Playfair Display';
   color: #01436b;
   margin-bottom: 30px;
   font-weight: 400;
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
   .p-t-80 {
   padding-top: 80px;
   }
   .p-b-80{
   padding-bottom: 80px;
   }
   .u-align--center{
   text-align:center;
   }
   .about_bb .inner {
   padding: 30px;
   background-color: #EBE7E5;
   border-radius: 25px;
   }
   .about_a_b p {
   color: #1A3554;
   font-size: 18px;
   }
	 .action3_b a.p-button.btn {
    padding: 10px 30px;
    margin-top: 20px;
    display: inline-block;
    }
    .action3_b p {
    font-size: 24px;
    color: #000;
    margin-bottom: 30px!important;
    margin-top: 0;
    }
   .faq_sect h2 {
   color: #1A3554;
   font-family: 'Playfair Display'!important;
   font-weight: 400;
   font-style: italic;
	font-size: 50px;
   }
   .faq_sect p {
   margin-top: 10px;
   font-size: 18px;
   }
   .about_bb h4 {
   color: #1A3554;
   font-weight: bold;
   margin-bottom: 0;
   }
   .about_bb p {
   margin-top: 10px;
   font-size: 18px;    
   }
   .about_a_b h2 {
    color: #1A3554;
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 400;
    font-size: 50px;
    line-height: 65px;
}
   .heading h3 {
   margin-bottom: 30px;
   color: #000;
   }
	.about_ac .row:first-child::after {
    content: "";
    left: 0;
    right: 0;
    bottom: -27px;
    position: absolute;
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
    background-image: url(https://i.imgur.com/Wx846RX.png);
    height: 200px;
    width: 300px;
    margin: 0 auto;
}
	.about_ac .row:first-child {
    position: relative;
}
   .content a{
   color: #1A3554!important;
   }
   .m-b-30{
   margin-bottom: 30px;
   }
   .p-t-40{
   padding-top:40px;
   }
   .action_3 {
   background-color: #C8C6C3;
   }
   .accordion h5 {
   margin-top: 0;
   color: #1A3554;
   }
   .accordion table th {
   color: #1A3554;
   }
   .accordion table {
   width: 100%;
   border: 1px solid #ddd;
   background-color: #fff;
   margin-bottom: 30px;
   }
   .content strong {
   color: #1A3554;
   }
   .accordion h6 {
   margin-top: 20px;
   line-height: 30px;
   }
   .accordion ul {
   list-style: none;
   padding: 0;
   }
   .accordion ul li {
   margin: 0;
   }
   .action__4 h2{
   color: #000;
   font-family:'Playfair Display';
   font-weight:400;
   }
   .action__4 p{
   color: #000;
   font-size: 22px;
   line-height: 32px;
   }
   .accordion ul {
   margin: 0;
   }
   .accordion .toggle{
   display:none;
   }
   .accordion ul li label {
   position: relative;
   color: #1A3554;
   display: inline-block;
   width: 100%;
   line-height: 49px;
   text-indent: 20px;
   cursor: pointer;
   font-weight: bold;
   font-size: 18px;
   }
   .accordion ul li label::before {
   width: 100%;
   background-image: linear-gradient(#a6d9e5, #9ac0c8);
   display: block;
   color: #fefefe;
   padding: 0.75em;
   border-radius: 0.15em;
   transition: background 0.3s ease;
   margin-bottom: 0;
   border-radius: 0;
   content: "";
   position: absolute;
   left: 0;
   right: 0;
   top: 0;
   height: 55px;
   z-index: -1;
   }
   .accordion ul .inner li strong {
   color: #1A3554;
   }
   .accordion ul {
   margin: 0!important;
   }
   ul.accordion ul ul {
   padding-left: 45px;
   }
   .inner > ul > li:not(:last-child) {
   margin-bottom:15px;
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
   .about_a_b {
   display: flex;
   align-items: center;
   }   
		section.accordion {
    position: relative;
}
	.about_ac .row:first-child::after {
    content: "";
    left: 0;
    right: 0;
    bottom: -27px;
    position: absolute;
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
    background-image: url(https://i.imgur.com/YMHMsb6.png);
    height: 200px;
    width: 300px;
    margin: 0 auto;
}
	section.accordion::after {
    content: "";
    left: 0;
    right: 50px;
    bottom: -23px;
    position: absolute;
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
    background-image: url(https://i.imgur.com/YzqmSE5.png);
    height: 200px;
    width: 300px;
    margin: 0 0 0 auto;
}
	.action_3::after {
    content: "";
    left: 50px;
    right: 0;
    bottom: 12px;
    position: absolute;
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
    background-image: url(https://i.imgur.com/1pbenGx.png);
    height: 200px;
    width: 300px;
    margin: 0 0 0 0;
}
	.about_ac .row:first-child {
    position: relative;
}
   .about_bb p, .about_bb li, .about_bb p, .about_bb .inner {
   color: #1A3554;
   font-size: 18px;
   }
   .video_acc .inner {
   position: relative;
   }
   .accordion ul .inner::after{
   content: "+";
   width: 25px;
   height: 25px;
   background-color: #fff;
   display: inline-block;
   text-align: center;
   border-radius: 50%;
   position: absolute;
   right: 20px;
   top: 14px;
   color: #1A3554;
   text-indent: 0;
   line-height: 25px;
   }
   ul.accordion input.toggle:checked + .inner::after {
   content: "-";
   }
	.accordionBottom p{
	font-size:20px
	}
   ul.accordion input.toggle:checked + .inner {
   height: auto;
   padding: 45px;
   }
   .accordion ul .inner {
   overflow: hidden;
   margin-top: 0;
   background-color: #EBE7E5;
   margin-top: 6px;
   height: 0;
   padding: 0 45px;
   transition: all ease-in-out .3s;
   -webkit-transition: all ease-in-out .3s;
   text-indent: 0;
   }
   .accordion ul .inner p, .accordion ul .inner li {
   font-weight: 500;
   font-size: 18px;
   color: #1A3554;
   margin-top: 0;
   line-height: 30px;
   }
   .accordion ul .inner h4 {
   font-weight: bold;
   font-size: 22px;
   color: #1A3554;
   margin-top: 0;
   margin-bottom: 0;
   }
   .p-lr-50{
   padding: 0 50px;
   }
   section.action__4 {
   position: relative;
   }
   .action__4::before {
   content: "";
   position: absolute;
   left: 30px;
   bottom: -4px;
   width: 200px;
   background-position: center;
   background-size: contain;
   background-repeat: no-repeat;
   background-image: url(https://i.imgur.com/ymZBFhy.png);
   z-index: 99999999;
   height: 200px;
   }
   section.action__4 .container::after {
   content: "";
   position: absolute;
   right: 0;
   top: 0;
   width: 300px;
   height: 200px;
   background-size: contain;
   background-repeat: no-repeat;
   background-image: url(https://i.imgur.com/4gIO8gl.png);
   }
   .container{
   position: relative;
   }
   .heading::after {
   content: "";
   position: absolute;
   right: -50px;
   top: -28px;
   width: 300px;
   height: 200px;
   background-size: contain;
   background-repeat: no-repeat;
   background-image: url(https://i.imgur.com/AxzRdOk.png);
   }
   @media(max-width: 767px){
   .heading::after{
   display:none;
   }
   section.action__4 .container{
   display:none;
   }
   .action__4{
   display:none;
   }
   .p-lr-50{
   padding: 0;
   }
   .action_3 h2,.action_3 h2 i {
   line-height: 38px;
   font-size: 28px;
   }
   html {
   overflow-x: hidden;
   }
   .about_a_b:first-child {
   margin-bottom: 30px;
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
   .action_3 {
   background-color: #C7C6C2;
   }
   .accordion ul li label {
   line-height: 29px;
   text-indent: 0;
   font-size: 15px;
   padding: 0 15px;
   padding-right: 35px;
   }
   .accordion > li {
   margin-bottom: 10px!important;
   }
   ul.accordion input.toggle:checked + .inner {
   padding: 15px 20px;
   }
   .accordion ul .inner p, .accordion ul .inner li {
   font-size: 15px;
   }
   section.accordion {
   margin-bottom: 50px;
   }
   .accordion ul .inner::after {
   right: 5px;
   top: 5px;
   }
   .accordion ul li label::before {
   height: unset;
   bottom: 0;
   }
   .faq_sect {
   padding: 0 15px;
   }
   .accordion ul .inner {
   width: calc(100% + 50px);
   margin-left: -15px;
   }
   .col.is-8.is-offset-2.print-content {
   padding: 0;
   }
   section.bp-section .bp-container > .row {
   margin: 0;
   }
	.action_3::after{
	display:none;
	}
   }
   @media(min-width: 767px)and (max-width: 1140px){
   .container {
   padding: 0 15px;
   }
   .col.is-8.is-offset-2.print-content {
   padding: 0;
   }
   section.bp-section .bp-container > .row {
   margin: 0;
   }
   }
</style>
<section class="about_ac">
   <div class="container">
      <div class="row p-t-80 p-b-80">
         <div class="col-6 about_a_b">
            <div class="inner">
               <h2>I have further<br> concerns</h2>
               <p>Taking charge of your and your loved ones’ futures through legacy planning is an empowering act for all parties involved. A Will lets you decide who gets what when you pass on, legally enforcing your wishes and distribution of assets to your beneficiaries of choice.</p>
            </div>
         </div>
         <div class="col-6 about_a_b">
            <img alt="My Legacy" src="https://i.imgur.com/mlDIwVj.png">
         </div>
		 </div>
      <div style="position: relative;" class="row">
         <div class="faq_sect">
            <h2>Frequently Asked Questions</h2>
            <p>It’s great that you’ve decided to make an LPA and ACP! Doing so will give your loved ones certainty of your preferences should the worst happen. Speaking of loved ones, it’s a good idea to discuss with them your choices, particularly on who you are appointing as donee for your LPA and your healthcare decisions should you lose mental capacity.</p>
         </div>
      </div>
   </div>
</section>
<section class="accordion p-t-80 p-b-80">
   <div class="container">
      <div class="row">
         <div class="col-12 accordion_b">
            <ul class="accordion">
               <li>
                  <label for="accordion_1">
                     <input class="toggle" id="accordion_1" name="accordion" type="radio">I’m a Muslim. How do I write an Islamic Will?
                     <div class="inner"> </div>
                  </label>
               </li>
               <li>
                  <label for="accordion_2">
                     <input class="toggle" id="accordion_2" name="accordion" type="radio">I have very few assets, I don’t need a Will.
                     <div class="inner"> 
                     </div>
                  </label>
               </li>
               <li>
                  <label for="accordion_3">
                     <input class="toggle" id="accordion_3" name="accordion" type="radio">I’m still young. I don’t need a Will right now.
                     <div class="inner"></div>
                  </label>
               </li>
               <li>
                  <label for="accordion_4">
                     <input class="toggle" id="accordion_4" name="accordion" type="radio">The law already dictates my next of kin as my beneficiary. I don’t need a Will.
                     <div class="inner"></div>
                  </label>
               </li>
               <li>
                  <label for="accordion_5">
                     <input class="toggle" id="accordion_5" name="accordion" type="radio">I need a lawyer to write a Will.
                     <div class="inner"> </div>
                  </label>
               </li>
               <li>
                  <label for="accordion_6">
                     <input class="toggle" id="accordion_6" name="accordion" type="radio">Will a divorce revoke my Will?
                     <div class="inner"></div>
                  </label>
               </li>
               <li>
                  <label for="accordion_7">
                     <input class="toggle" id="accordion_7" name="accordion" type="radio">Is my Will legally bound in perpetuity?
                     <div class="inner"></div>
                  </label>
               </li> 
            </ul>
         </div>
		 </div>
		 <div class="row">
		 <div class="col-12 accordionBottom">
					<p>Have more questions? <a class="read-more" href="#">Seek professional legal advice.</a><br>
Try our <a class="read-more" href="#">Wills Simulator.</a></p>
				</div>
		 </div>
   </div>
</section>
<section style="padding-top: 90px; padding-bottom: 90px" class="action_3">
    <div class="container">
       <div class="row">
          <div class="col-12 action3_b u-align--center">
             <h2>My Legacy Vault</h2>
             <p>Plan, store and share your legal, healthcare and<br> estate matters securely.</p>
             <p>Upload your documents to <a class="read-more" target="_blank" href="https://mylegacy.life.gov.sg/vault/">My Legacy vault</a> for<br> secure storage and share them with those you trust.</p>
             <a class="btn p-button" target="_blank" href="https://mylegacy.life.gov.sg/find-a-service/lpa-acp/">Get Started</a>
          </div>
       </div>
    </div>
 </section>