---
title: WIP pg 2
permalink: /wills/wip-pg-2/
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
    width: 1170px;
    margin: 0 auto;
    }
    container-fluid{
    width: 100%;
    }
    section.bp-section.is-small.bp-section-pagetitle {
    display: none;
    }
    .action__5 p {
    font-size: 24px;
    color: #000;
    }
    .action__5 p a.read-more {
    color: #375780;
    }
    .content a {
    color: #375780;
    }
    a.p-button.btn {
    border-color: #01436b;
    background-color: transparent;
    border-radius: 30px;
    color: #01436b;
    margin-top: 30px;
    font-weight: 600;
    border: 1px solid #01436b;
    text-decoration: none;
    }
    .col.is-2.is-position-relative.has-side-nav {
    display: none;
    }	
    .col.is-8.is-offset-1-desktop.is-12-touch.print-content {
    margin-left: 0;
    width: 100%;
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
    .offset-1{
    margin-left: 8.33%;
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
    .banner {
    height: 520px;
    background-color: #01436B;
    display: inline-block;
    position: relative;
    }
    .banner h2, .banner h2 span {
     margin: 0;
     text-align: left;
     font-family: 'Playfair Display';
     font-style: italic;
     font-size: 65px;
     line-height: 75px;
     color: #ECD6C6;
    }
    .content .action2_b a.read-more {
    margin-top: 0!important;
    font-size: 24px;
    }
    .action2_b h3 {
    font-size: 40px;
    line-height: 60px;
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 500;
    color: #07477b;
    }
    .banner h2 span {
    margin-left: 60px;
    }
    .banner h3 {
    text-align: left;
    color: #ECD6C6;
    }
    .banner::after {
    content: "";
    background-image: url(https://i.imgur.com/Fwasl3s.png);
    background-position: bottom right;
    background-repeat: no-repeat;
    background-size: contain;
    position: absolute;
    left: 30%;
    right: 0;
    bottom: 0;
    top: 0;
    pointer-events: none;
    }
    header#navigation .p-navigation__tagged-logo a.p-navigation__link {
    padding: 0;
    margin-top: 8px;
    }
    .banner_block img {
    width: 350px;
    }
	section.bp-section.bottom-navigation {
    display: none;
}
    .banner_block {
    display: flex;
    align-items: center;
    height: 520px;
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
    }
    .p-navigation__items {
    margin-top: 4px;
    }
    section.feature{
    background-image: url(https://i.imgur.com/7lJhb2q.png);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    }
    img.arrow-btn {
    width: 70px;
    position: absolute;
    right: 10px;
    bottom: 10px;
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
    .feature_block {
    position: relative;
    }
    .feature .heading h2,.feature .heading h2 strong {
    font-size : 30px;
    line-height : 50px;
    color : #01436B;
    font-weight: 400;
    }
    .feature_block .inner{
    height: 240px;
    width: 100%;
    background-image: linear-gradient(#01436B, #01436B, #085b8e);
    border-radius: 30px;
    box-shadow: 0 0px 5px 0 rgba(0,0,0,0.4);
    padding: 30px;
    position: relative;
    }
    .feature_block .inner h3 {
    font-size: 21px;
    line-height: 34px;
    color: #D0D0D0;
    }
    .feature_block .inner a {
    position: absolute;
    right: 0;
    bottom: 0;
    margin-bottom: 0;
    top: 0;
    left: 0;
    }
    strong i {
    font-family: Playfair Display;
    font-weight: 400;
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
    font-weight: bold;
    font-size: 22px;
    line-height: 50px;
    color: #07477B;
    text-decoration: underline;
    }
    .u-align--center{
    text-align: center
    }
    .action_b p,.action_b strong {
    font-size: 22px;
    line-height: 34px;
    color: #07477b;
    }
    section.bp-section {
    padding: 0;
    }
    .action_b img {
    width: 500px;
    }
    section.bp-section .bp-container {
    width: 100%!important;
    max-width: 100%!important;
    padding-top: 0!important;
    }
    .action h2 a {
    font-size: 28px;
    }
    .action_b{
    display: flex;
    align-items: center;
    }
    section.action {
    background-color: #DADADA;
    position: relative;
    }
    section.action::after {
    content: "";
    position: absolute;
    right: 0;
    bottom: 0;
    width: 400px;
    height: 400px;
    background-image: url(https://i.imgur.com/GExZXiY.png);
    background-position: bottom right;
    background-size: contain;
    background-repeat: no-repeat;
    z-index: 11;
    pointer-events: none;
    }
    section.action_::after {
    content: "";
    position: absolute;
    right: 50px;
    bottom: -30px;
    background-image: url(https://i.imgur.com/DMiuUNg.png);
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    width: 300px;
    pointer-events: none;
    height: 300px;
    }
    .m-t-30 {
    margin-top: 30px!important;
    }
    .action h2,.action h2 strong {
    font-family: Playfair Display;
    font-size: 42px;
    color: #191919;
    line-height: 52px;
    font-weight: 400;
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
    .action_2 h2,.action_2 h2 strong {
    font-family: Playfair Display;
    font-size: 42px;
    line-height: 52px;
    color: #07477b;
    font-weight: 400;
    }
    .action_2 h2 strong i {
    font-weight: 800;
    font-style: italic;
    margin-top: 10px;
    display: inline-block;
    }
    .action2_b p {
    font-size: 24px;
    line-height: 37px;
    color: #07477b;
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
    .action_3 h2, .action_3 h2 i {
    line-height: 52px;
    font-size: 42px;
    font-family: 'Playfair Display';
    color: #000;
    margin-bottom: 30px;
    font-weight:400;
    }
    .content a.read-more {
    font-size: 20px;
    margin-top: 20px;
    display: inline-block;
    font-weight: bold;
    margin-bottom: 0;
    }
    a.p-button.btn {
    padding: 10px 30px;
    }
    .action_ {
    background-image: url(https://i.imgur.com/ursOeJR.png);
    background-position: bottom right;
    background-repeat: no-repeat;
    background-size: contain;
    position: relative;
    }
    .action_3 {
    background-color: #c7c6c2;
    }
    ul.social-share.p-inline-list li.list__item a img {
    width: 20px;
    }
    a.p-button.btn:hover {
    background-color: #01436b;
    color: #fff;
    }
    .feature .heading h2 strong {
    font-weight: 600;
    }
    .p-navigation [class*=p-navigation__item] > .p-navigation__link:hover {
    color: #01436b;
    }
    .container.action_3 {
    background-color: #C7C6C2;
    }
    @media (max-width: 1024px){
    section.action::before,section.action_::after{
    display: none;
    }
    .feature .heading h2,.feature .heading h2 strong {
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
    background-position: 100% 100%;
    }
    .action_2 h2,.action_2 h2 strong {
    font-size: 25px;
    line-height: 36px;
    }
     .banner h2, .banner h2 span {
     font-size: 34px;
     line-height: 44px;
    }
     .col {
     padding: 0;
    }
    .action2_b p {
    font-size: 18px;
    line-height: 28px;
    }
    .action2_b a.read-more {
    font-size: 18px;
    line-height: 28px;
    }
    .action_3 h2,.action_3 h2 i {
    line-height: 38px;
    font-size: 28px;
    }
    footer .u-align--right {
    text-align: left!important;
    }
    footer p {
    margin-top: 2px;
    }
    .action h2,.action h2 strong {
    font-size: 28px;
    line-height: 38px;
    }
    .action h2 br {
    display: none;
    }
    .action .row.m-t-60 {
    margin-top: 0px;
    }
    section.action {
    background-image: none;
    background-color: #e6e6e6;
    }
    .col.is-8.is-offset-2.print-content {
    padding: 0;
    }
    section.bp-section .bp-container > .row {
    margin: 0;
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
    .offset-2{
    margin-left: 12.5%;
    }
    @media(max-width: 767px){
     .col-2,.col-3,.col-4,.col-6,.col-8,.col-10,.col-12{
     padding: 0 25px;
     }
    .offset-2{
    margin-left: 0;
    }
    .col-10 {
    width: 100%;
    }
    .offset-1{
    margin-left: 0;
    }
    .feature_block .inner {
    padding: 20px;
    padding-right: 80px;
    }
    .feature_block .inner {
    height: auto;
    }
    img.arrow-btn {
    width: 50px;
    bottom: auto;
    top: 50%;
    margin-top: -20px;
    }
    .feature_block .inner h3 {
    font-size: 24px;
    line-height: 40px;
    margin: 0;
    }
    .action__5 p {
    font-size: 18px;
    }
    .action2_b p br,.action__5 p br {
    display: none;
    }
    .banner::after {
    left: 0;
    background-size: auto 300px;
    background-position: center bottom;
    }
    .banner_block {
    display: block;
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
    .banner {
    height: 450px;
    }
    }
    @media(max-width: 500px){
    .banner_block {
    align-items: unset;
    height: unset;
    display: block;
    margin-top: 42px;
    }
    .banner::after {
    background-size: contain;
    pointer-events: none;
    }
    }
    @media(max-width: 1170px){
    .container {
    width: 100%;
    padding: 0 15px;
    }
    }
    @media(min-width: 768px)and (max-width: 1170px){
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
    @media(min-width: 768px)and (max-width: 1170px){
    .banner::after {
    background-position: bottom right;
    left: 30%;
    }
    .feature_block .inner h3 {
    font-size: 18px;
    line-height: 25px;
    }
    }
    .p-t-80 {
    padding-top: 80px;
    }
    .p-b-80{
    padding-bottom: 80px;
    }
    section.bp-section .bp-container {
    padding-bottom: 0!important;
    }
    .banner_block a.p-button.btn {
    margin-top: 30px;
    display: inline-block;
    }
    .col.is-1.has-float-btns.is-position-relative.is-hidden-touch {
    display: none!important;
    }
 </style>
 <section style="width: 100%" class="banner">
    <div class="container">
       <div class="row">
          <div class="col-6 banner_block">
             <div class="inner u-align--center">
                <h3>Write a Will and </h3>
                <h2>Enhance The <br>
                   <span>Gift of Certainty</span>
                </h2>
             </div>
          </div>
       </div>
    </div>
 </section>
 <section style="width: 100%" class="feature p-t-80 p-b-80">
    <div class="container">
       <div class="row">
          <div style="margin-bottom: 60px" class="heading u-align--center col-12">
             <h2><strong>When it comes to making your will,</strong><br>how would you describe your situation?</h2>
          </div>
       </div>
       <div class="row">
          <div class="col-10  offset-1">
             <div class="row">
                <div class="feature_block col-3 red">
                   <div class="inner">
                      <h3>Why should I<br> write a will?</h3>
                      <a href="/i-am-unsure-how-to-begin/"><img alt="My Legacy" class="arrow-btn" target="_blank" src="https://i.imgur.com/zkzLJtH.png"></a>
                   </div>
                </div>
                <div class="feature_block col-3">
                   <div class="inner">
                      <h3>I’m unsure<br> about the<br> process</h3>
                      <a href="/how-do-i-speak-to-my-family-about-this/"><img alt="My Legacy" class="arrow-btn" target="_blank" src="https://i.imgur.com/zkzLJtH.png"></a>
                   </div>
                </div>
                <div class="feature_block col-3">
                   <div class="inner">
                      <h3>I have further<br> concerns</h3>
                      <a href="/i-have-further-concerns/"><img alt="My Legacy" class="arrow-btn" target="_blank" src="https://i.imgur.com/zkzLJtH.png"></a>
                   </div>
                </div>
                <div class="feature_block col-3">
                   <div style="background: linear-gradient(#772C33, #772C33, #772C33);" class="inner">
                      <h3>I want to try the <br>Wills Simulator</h3>
                      <a href="https://go.gov.sg/mylegacy-lpa-acp"><img alt="My Legacy" class="arrow-btn" target="_blank" src="https://i.imgur.com/zkzLJtH.png"></a>
                   </div>
                </div>
             </div>
          </div>
       </div>
       <div class="row m-t-30">
          <div class="col-10  offset-1 feature_video">
             <img style="border-radius: 30px" src="https://place-hold.it/1000x500/bbb">
          </div>
       </div>
    </div>
 </section>
 <section style="padding-top:80px; padding-bottom: 110px; width: 100%;" class="action">
    <div class="container">
       <div class="row">
          <div class="action_b col-6">
             <img alt="My Legacy" src="https://i.imgur.com/gdFAwxJ.png">
          </div>
          <div class="col-6 action_b">
             <div class="inner">
                <p>A Will is a legal document that defines the<br> terms for the distribution of your real or<br> personal estate. The Wills Act states that a<br> Testator (the person making the Will) may<br> devise, bequeath, or dispose of their real or<br> personal estate to their loved ones via a Will.</p>
                <a class="read-more" href="">Read more</a>
             </div>
          </div>
       </div>
       <div class="row">
          <div class="col-6 action_b">
             <div class="inner">
                <p>Will-writing may feel like a morbid task, but <br>taking ownership of your future is a rewarding<br> feat. Planning beyond your lifetime arms your<br> loved ones with the confidence to move<br> forward upon your demise.<br><br>
                   Making a Will can bring about peace of mind<br> and reduce uncertainty for yourself and those<br> who care about you the most.
                </p>
             </div>
          </div>
          <div class="action_b col-6">
             <img alt="My Legacy" src="https://i.imgur.com/ijc2ER4.png">
          </div>
       </div>
    </div>
 </section>
 <section style="padding-top:90px; padding-bottom: 90px" class="action_">
    <div class="container action_2">
       <div class="row">
          <div class="col-8 action2_b">
             <h2>We understand that legacy<br> planning is hard to talk about.<br><strong><i>You are not alone</i></strong>.</h2>
             <p>The first step in engaging family members on<br>the topic is to start having open and meaningful<br> discussions together, even beyond estate<br> planning. Here are some ways you can <br> <a class="read-more" target="_blank" href="/how-do-i-speak-to-my-family-about-this/">start conversations with your family.</a></p>
          </div>
       </div>
       <div class="row p-t-80 action__5">
          <div class="col-12">
             <div class="action2_b u-align--center">
                <h3>Leave a legacy of love and certainty for<br> the people who matter most to you.</h3>
                <a class="read-more" href="#">Here are some ways to get started</a>
             </div>
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