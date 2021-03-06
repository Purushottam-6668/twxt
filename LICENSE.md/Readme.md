<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
    <head>
        <b:include data='blog' name='all-head-content'/>
        <meta content='width=device-width, minimum-scale=1.0, maximum-scale=1.0' name='viewport'/>
        <b:if cond='data:blog.pageType == &quot;index&quot;'>
            <title><data:blog.pageTitle/></title>
            <b:else/>
            <title><data:blog.pageName/> ~ <data:blog.title/></title>
        </b:if>
        <link href='//stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css' rel='stylesheet'/>
        <b:skin><![CDATA[/*

/* **************************
Template name: LMS Education
Template url: https://btemplates.com/2020/blogger-template-lms-education/
Ported by: https://rivieramaya.mx & https://ixibanyayu.com/
Designed by: https://btemplates.com/
Distributed by: https://btemplates.com/
Documentation: https://btemplates.com/blog/lms-education-template/
Realise date: 01/06/2020
License: Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International
License url: http://creativecommons.org/licenses/by-nc-nd/4.0/
CSS Framework: Bootstrap 4.1 https://getbootstrap.com/
Version: 1.0.4
*****************************

*//* Variable definitions
   ====================
   <Variable name="bgcolor" description="Page Background Color"
             type="color" default="#fff" value="#ffffff">
   <Variable name="textcolor" description="Text Color"
             type="color" default="#212529" value="#212529">
   <Variable name="linkcolor" description="Link Color"
             type="color" default="#333" value="#333333">
   <Variable name="hoverlinkcolor" description="Hover Link Color"
             type="color" default="#D8815F" value="#D8815F">
   <Variable name="pagetitlecolor" description="Blog Title Color"
             type="color" default="#212529" value="#212529">
   <Variable name="descriptioncolor" description="Blog Description Color"
             type="color" default="#212529" value="#212529">
   <Variable name="titlecolor" description="Post Title Color"
             type="color" default="#343a40" value="#343a40">
   <Variable name="bodyfont" description="Text Font"
             type="font" default="normal normal 100% 'Rubik', sans-serif" value="normal normal 100% &#39;Rubik&#39;, sans-serif">
*/

body {
    font: $bodyfont;
    background-color: $bgcolor;
    color: $textcolor;
}
a {
    color: $linkcolor;
}
a:hover {
    color: $hoverlinkcolor;
}
p.description {
    color: $descriptioncolor;
}
#header-wrapper h1, #header-wrapper h1 a {
    color: $pagetitlecolor;
}
.post-title a {
    color: $titlecolor;
}
#testimonials .carousel-control-next-icon {
background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23666' viewBox='0 0 8 8'%3e%3cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3e%3c/svg%3e") !important;
}
#testimonials .carousel-control-prev-icon {
background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' fill='%23666' viewBox='0 0 8 8'%3e%3cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3e%3c/svg%3e") !important;
}


/* Gadgets panel */
body#layout {
    max-width: 1000px;
}
body#layout .widget .editlink {
    background-color: #999;
    color: #000;
}
body#layout .layout-widget-description {
    display: none;
}
body#layout .add_widget {
    padding: 0;
}
body#layout #bt-labels, body#layout #btemplates-search {
    display: none;
}
body#layout #topMenu, body#layout #logoImage {
    float: left;
    width: 45%;
}
body#layout #SocialNetworks, body#layout #MainMenu {
    float: right;
    width: 45%;
}
body#layout #btemplates-main-menu {
    clear: both;
}
body#layout #header-wrapper {
    height: auto;
}
body#layout #btemplates-main-content {
    margin-top: auto;
}
body#layout #content-wrapper {
    float: left;
    width: 67%;
}
body#layout #sidebar-wrapper {
    float: right;
    width: 30%;
}
body#layout #footers .section {
    width: 27%;
    float:left;
}
body#layout #blocksMainMenu, body#layout #content-1 .Image, body#layout #bt-subscription .Image, body#layout #bt-videos .Image {
    display: block;
}
body#layout #btemplates-dropdown-2::before {
    content: "Template documentation at: https://btemplates.com/blog/lms-education-template/";
}
body#layout #LinkList67::before {
    content: "Here you can add info like email, phone number or location:";
}
body#layout #LinkList68::before {
    content: "Add your social networks here. Your links will be changed for icons automatically:";
}
body#layout #LinkList78::before {
    content: "Main menu with dropdown items support:";
}
body#layout #Image97::before {
    content: "Add your logo here:";
}
body#layout #Header1::before {
    content: "Edit blog title/logo and description here:";
}
body#layout #Image98::before {
    content: "You can change the header background image here:";
}
body#layout #LinkList63::before {
    content: "Edit/add items for the Blocks menu in the home page here:";
}
body#layout #HTML49::before {
    content: "List of latest posts or by Label. Check the documentation to add your own content:";
}
body#layout #Image91::before {
    content: "You can change the Labels section background image here:";
}
body#layout #Label3::before {
    content: "Select Labels to display here:";
}
body#layout #HTML59::before {
    content: "List of posts to show profiles/testimonials:";
}
body#layout #Image93::before {
    content: "You can change the Email Subscription section background image:";
}
body#layout #FollowByEmail1::before {
    content: "Email subscription settings:";
}
body#layout #HTML79::before {
    content: "List of latest post or by Label. Check the documentation to add your own content:";
}
body#layout #Image89::before {
    content: "You can change the Video section background image here:";
}
body#layout #HTML96::before {
    content: "Settings for the Video section in the home page:";
}
body#layout #ContactForm1::before {
    content: "Contact form in the home page settings:";
}
body#layout #HTML98::before {
    content: "List of latest posts or by Label as gallery. Check the documentation to add your own content:";
}
body#layout #footers::after {
    content: "Thank you for using LMS Education template by BTemplates.com";
}
body#layout #content-wrapper {
    margin: 0;
}
body#layout #header-wrapper .Image {display: block;}
body#layout #footer-wrapper .links, body#layout #search {
    display:none;
}

]]></b:skin>
        <style type='text/css'>
            /* GENERAL STYLES */

            /* Hide top navbar */
            #navbar-iframe {
                height:0px;
                visibility:hidden;
                display:none
            }

            body {
            }
            a {
            }
            a:hover {
            }
            a:visited {
                color: #666;
            }
            blockquote {
                background-color: #d4f7f7;
                border-left: 10px solid #86e8e8;
                margin: 1.5em 10px;
                padding: 0.5em 10px;
                quotes: &#39;\201C&#39;&#39;\201D&#39;&#39;\2018&#39;&#39;\2019&#39;;
            }
            blockquote:before {
                color: #86e8e8;
                content: open-quote;
                font-size: 4em;
                line-height: 0.1em;
                margin-right: 0.25em;
                vertical-align: -0.4em;
            }
            blockquote p {
                display: inline;
            }
            .clear {
                clear:both;
            }
            .clearfix:after {
                clear:both;content:&#39;.&#39;;
                display:block;
                visibility:hidden;
                height:0;
            }
            .clearfix {
                display:inline-block;
            }
            * html .clearfix {
                height:1%;
            }
            .clearfix {
                display:block;
            }

            /* HEADER */
            #bt-header {
                background-position: center center;
                background-size: auto 100%;
                background-repeat: no-repeat;
                height: 30rem;
                width: 100%;
            }
            #header-bg-1 {
                background-image: url(https://2.bp.blogspot.com/-7Wj-vIgtneY/XS4uM_rIBcI/AAAAAAAABOk/EhbQjIgf6Rg-aJRTUaia8OmxLBlKOSGMwCLcBGAs/s1600/header-left.png);
                background-repeat: no-repeat;
                background-size: auto 100%;
                background-position: left center;
            }
            #header-bg-2 {
                background-image: url(https://1.bp.blogspot.com/-cRoJO1bxDHA/XS4v7eZdcSI/AAAAAAAABO4/7tGrxkhJYgsm_h54zG5EwuJPf1GygZ3egCLcBGAs/s1600/header-right.png);
                background-repeat: no-repeat;
                background-size: auto 100%;
                background-position: right center;
            }
            #header-wrapper h1, #header-wrapper h1 a {
                letter-spacing: 0.025em;
                font-weight: bold;
                position: relative;
            }
            #header-wrapper h1, #header-wrapper h1 a {
                content: &#39; &#39;;
                display: block;
                padding: 1rem;
                border-radius: 5px;
                left: 0;
                top: 0;
                width: 100%;
                height: 100%;
                z-index: 1;
                opacity: 0.8;
                background-color: #fff;
            }
            #header-wrapper h1 a:hover {
                text-decoration: none;
            }
            #header-wrapper h1 a:hover:after, .status-msg-body b:after {
                content: &#39;&#39;;
                position: absolute;
                bottom: -0.125rem;
                left: -0.5rem;
                right: -0.5rem;
                height: 0.75rem;
                z-index: -1;
                background-image: url(&quot;data:image/svg+xml;charset=utf8,%3Csvg id=&#39;Layer_1&#39; xmlns=&#39;http://www.w3.org/2000/svg&#39; viewBox=&#39;0 0 260 15.6&#39;%3E%3Cstyle%3E .st0{fill:%23f3bc34} %3C/style%3E%3Cpath class=&#39;st0&#39; d=&#39;M206.8 7.3l-.1.3c.1-.2.2-.3.1-.3zM234.7 10h-.1c-.2.4-.1.3.1 0zM54.8 4.2l-.6-.4c.2.4.4.5.6.4zM17.1 5.1zM34.5 9.6l.1.3c0-.2 0-.3-.1-.3zM22.4 10.8c-.3-.1-.7-.1-1-.1.2.1.7.1 1 .1zM17.5 5c-.1.1-.2.1-.4.2.2-.1.3-.2.4-.2zM52.7 9.8l.5.9c-.1-.3-.3-.6-.5-.9zM19.5 11.6c-.2-.2-.4-.2-.6-.3 0 .2.3.3.6.3zM120.9 11.4c-.1.1-.2.2-.2.3.3-.1.3-.2.2-.3zM80.9 10.4h-.1s.1.1.2.1l-.1-.1zM92.6 10.4l-.2.2c.2-.1.2-.1.2-.2zM72.1 11.3c-.1.1-.3.2-.4.3l.4-.3z&#39;/%3E%3Cpath class=&#39;st0&#39; d=&#39;M260 6c-1-.6-4.7-1.2-5.8.3-.2-.1.1-.3.2-.4-.9.2-2.2.1-3.6 0s-2.9-.2-4.2 0c-1 1.5-3.9-.6-4.8 1.4l.5-.4c.9.5-1.2 1.4-1.5 1.9-.8-1.2-.1-1-1-2l1.1.4-.3-1c-3.1 2.8-6.2-.9-8.2 1.1.1-.1.1-.3.2-.4-1.4-.5-2.3.8-3.3 1.2-.1-.5.6-.9 1.1-1.3-2.4-.3-6.4 1.2-9 .4-.9.7.4.9-.6 1.5-.8-.2-1.4-.7-.4-1.1-2.3-1.2-7.6 1-11.1-.2-1.8.8-.7 1.1-3.5 1.6.7-.5-.7-1.7 1-1.7l.2-.5c-2.8-.1-6.6-.3-8.1 1.2-.1-1.1-.5-.2-1.6-.8-.4.1 0 .2.2.2-1 .9-1.6-.1-2.3.1l.3-.2-2 .7c-.3-.2-.8-.4-.9-.7v.8c-1.1 0-.5-1-1.9-.8l.3.6c-.9-.4-2.2.4-2.4-.5 0-.2.1-.1.4-.1-1.3-1.2-3.5.3-5.1-.3l.4 1.3c-1.6.4-1-.3-.9-.7-1.1 0-1.3-.4-2.7-.6-.7.3-.4.5-.6.8l-1.5-.4 1-.7c-2.3 1.8-5.6-.4-7.2 1.2-.8-.4.8-.7.3-1-2.6-.9-6 1-8.2 0-3.6-1-7.8-.4-11.8-1.1l.1.3-2.9-.4c-.8.7-2.7.3-4 1.1.1-.3-.1-.7.2-.9-1.2.1-2.6.4-3.3-.1l.4-.3c-2.7-.3-6.4-.5-7.9.1-.9 0-.9-.6-1.1-1-1.6-.1-2.6.2-3.9.7-.3-.2-.7-.3-1-.6l-.6.8c-.6-.1-.1-.7-.6-.9-2.5.9-5.3-.1-7-.1l.2.4c-.7.3-2.1-.3-1.2-.7-3.4-.6-5.1 1.2-9.6.8-.6-1.5-4.1.3-4.8-1.4-1.9.4-3.2-.3-4.5.6 0-.2-.2-.2.1-.3-.8-.6-3.3-.2-5.3.2l-.1-.5c-.9 1.2-4.2.9-4.9 2-.2-.2.4-.5.7-.7-1-1.1-1.8.5-3.1.2.1-.3-.3-.6 0-.8-4.4-1.2-10.6.7-16.3-.1-1.6 0 .6 1.2-1.5 1.1-.6-.6 1-1.1-.3-1.4-.9.7-1.3.5-2.6.5.2-.4 0-.6.9-.9-.7-.5-3.1.9-4.5 0 .1.3-.2.5-.5.7-2.1 1-4.9-.9-5.1-.4 0 0-.7.2-.1.3-.8 0-1.9-.2-1.7-.7-.4.3-.8.8-1.4.8l.3-.6c-.4.1-.8.5-1.1.6l.6.4c-.9-.5-2.6.8-2.6-.4h.3l-1.7-.5c-.7.5-1.3 1-2.5.9-.5-1.3-2.9-.2-4.3-.3l.1-.4c-1.1.6-4 .4-3.5.6-1.1 0-2.6-.2-2-.6-.8.1-2.7.1-3.2.9l-1.8-1c-1 1.6-3.6-.5-3.6 1.2-1-.2-.8-.6-1.5-.9-1.4.9-2.8.8-4.2.7v-.2c-1.4-.1-3.1.8-5.1 1l-.5-1.2c-1 .2-1.3 1.2-2.3 1-.2-.2 0-.3.2-.3-1 .3-2.3.1-3.1-.2-1.5 1-2.7.7-3.9 1.8-1.3-1 1.7-.6.6-1.6-2.2-.4-4.4.4-6.7 1.1-.2-.2 0-.4.1-.7 0 0-1.2.9-2.2 1.8C.9 8.3 0 9.4.5 10c-.5.9-1.2 1.4.9 2 .6-.5 2.5-1.3 2.9-.4l.1-.9c2.6-.6.4 1.8 3.6 1.6l-.7-.3c.6-.1 1.1-.7 1.8-.5.2.2-.2.4-.5.6.9-.5 1.7-.9 2.6-1.4.1.5.1.8-.4 1.2 2.5-.2-.6-1.6 2.4-1.4.6.4-.2.6-.5.9 1.4.7 2.3-.1 3.8-.6.1.8-.9.7.3 1.2-.3-.4-.5-1.1.5-1.2-.4.8.7.4 1.6.5-.2-.3-.1-.6.2-.8.4-.1.8.1 1.4.1l-1.1-.7c1.5-.8 2.4.3 3.6.6-.1.1-.3.3-.5.3 1.2.3 2.5.9 4.1.1l-.3.1c2.9-.9-1-1.3 2.4-2.2 1.1.1-.4 2.6 2.1 1.6-1.3-.6 1.6-1.7 3.1-2L32.4 10c.6 0 1.6-.5 2-.3l-.1-.3c-.2-1.3 1.9.1 3-.7-1.3 1.8-1.4 1.5-1.6 3.2 1-1 2.2-1.9 4.1-1.8l-1.5 1.4c2.5.2 5.5-1.9 7.6-3-.5 1 .3 1.4-.6 2.2l2.4-.3-.7 1.1c1-1.2 2.1-.4 1.9-1.9-.3.2-.2.4-.7.3.1-.4.5-1.4 1.7-1.3.9.3-.5.6-.2 1 .8-.6.9.3 1.7-.1l-.8-.6c.6-.9 1.4-.1 2.2-.5-1 .4-.7.9-.3 1.4l-.1-.1c.8-.1 1.6-.7 2-.2l-.5 1.2.9-.9c.3.1.6.6 0 .8 2.8.7-.1-2.5 3.6-1.5 0 .5-.4.8-1.4.5-.2.7.1 1.1 1.1 1.4v.1c1.9 0 4.4 0 5.6-.8.4.3 0 .6-.4.9 2.1.4 2.8-.7 5 .1l-1-.4c1.4-.6 4-.8 5.3.1l-.4.3c1.3-.7 3.5.6 4 0-.6-.4 0-.6-.8-1l3.4-.7.2 1.2 1.8-.4c-.4-.5 2.4.4 2.5-.7 1 .4-.4.9-.8 1.4 1-.3 1.1.2 2.1-.5l1 1.1 2.6-.7c-.1.1 0 .2-.1.3 1.2-.9 3.1.6 4.6-.9-.1.1-.1.1-.1.2.9-.8 2.9-.2 3.7 0 1.4-.2.6-1 .6-1.4 3.9.4 2.7.3 6-.9 2 1.4-2.4 2.1.1 3 .4-.6 2.1-1.1 4.1-1.3 1.8.5 4.8.9 6.5 1.9l-.2-.9 2.6-.4-1.5 1.2c.4-.3 1.7-.8 2.6-1.2 2.7-.7 1.4 1.9 3.5.7.1.1.1.2.2.3.7-.6 2.4-.3 4.4-.5l-.7 1.1-1.3-.3c.7 1.1 2.1-.1 3.4 0 1.3-.3.7-1.3 1.4-1.6.5.1 1.2-.2 1.6.1 1.1.4.1 1.3-.3 1.8 1-1.1 1.4-.9 3.6-1.3.1.5-.1.8-.4.9.5-.1.9-.3 1.2-.8l.7.7c2.5 1 2.6-2 5.6-1.5-.8.6 2.6 0 3.5.7-1.1.1.4 1.6-.2 2.3 2.4.5 1-1.3 3-1.4l-.9 1.3c1.9-.5.5-.7 2.4-1.1-.5.4.8.4-.3.8 2.5.2 1.9.1 4.1.3l.2-1.3c.7-.1 1 .5 1.2.7-.3 0-.8-.1-.7.1.8 1.2 1.4-.6 2.4.5-.2-.4-.5-1 .4-1.1-.3.8 1.4.8 1.4 1.2-.6-.6 2-.2 2.1-1 1 .7-.4.6-.4 1.1.9-1 3.7 0 4.6-.6 0 .1.1.1.1.2 1.2-.6 3-.7 5.3-1.5l-.8.7c2.2.4 1.4-1.5 3.3-1.5-.4 1.1 3.1 0 2.2 1.2 1.1-.6 2.3-.8 3.1-1.7 1 .6-2.1 1.4-.6 1.8l1.6-.5.3.6c.1-.4 1.5-.4 1.4-.8.2.7.9 1.2.8 1.8 1-.2 2.4.5 3.3-.1l.1.3c1-1.3 3.1-.2 3.6-1.5l.6.7c1.5-.1 1.3-1.5 2-1.8.6 0 1.4-.2 2 0-2 .8 1 1.1 1.4 1.6.8 0 3.1 0 3.7-.7-1 .7-.4 1.2-2.1 1.3.9 1.3 2.6-.2 4.5-.1v.6c2.7-.4 2.8-1.5 4-2.5.3.8.1 1-.7 1.7 1.8.5 4.7-.1 6.7 0 .6.5.2.9-.5 1.1 2.1-.6 4.7.1 6-1.2-.5.5.9.3 1.6.6 0-.3.1-.6.2-.6 1.3-.6 4.1-1.1 5.6-.7l-.5.4c1.7.1 3-.5 4.3-.9 1.3-.4 2.6-.8 4.5-.4.7.3-.7 1.1.7 1 .7-.5.4-1.5 2.2-1.3l-.1.9 1.2-.9c-.7-.7-2.6-.4-1.3-1.2 1.6.8 1.3-.9 3.3 0-.4.1-1 .8-1.3 1.2 2 .4 3.4.1 4.8-.1 1.4-.3 2.8-.6 4.9-.2 2-.8 4.6-1.2 5.9-1.9 0 .9 0 1.7-.8 2.4 1.8 0 2.4-2.1 3.7-.9.7-1.3 4.7-1.2 5-3l2-.8z&#39;/%3E%3Cpath class=&#39;st0&#39; d=&#39;M58.1 11.1c-1 0-1.9 0-2.3.2.2.2 2.3.6 2.3-.2zM208.2 13.3c-.1 0-.3.1-.4.1.1 0 .3 0 .4-.1zM216.3 12.9c-.1-.1-.2-.2-.4-.3 0 .3.1.5.4.3zM132.6 11.5zM178.5 13.7c.7-.4 1-.7 1-1-.4.1-.7.3-1 1zM163 12.6c-.1.1-.2.1-.3.2.3-.1.3-.2.3-.2zM130.2 12c.7-.4 1.6-.3 2.4-.5-.7.2-1.9-.3-2.4.5zM226.1 11.4l-.7.6.8-.4zM218.6 12c-.3-.1-1.7.3-1.3.6.4-.3.9-.5 1.3-.6zM189.6 11.4l-.3.6.7-.5z&#39;/%3E%3C/svg%3E&quot;);
                background-repeat: no-repeat;
                background-size: cover;
            }
            h1 .first-word, h1 a .first-word {
                color: #2EB8D7;
            }
            #header-wrapper .Image {display: none;}
            #header-inner {
                text-align: center;
            }
            #header-inner a img {
                margin: 0 auto;
                max-width: 90%;
                height: auto;
            }
            p.description {
            }
            #secondary-menu a {
                color: #212529;
                font-size:1.5em;
                margin-right: 0.25em;
            }
            #btemplates-dropdown-2 {
                background-color: #F3F8FC;
            }
            #btemplates-dropdown-2 .fa {
                color: #333;
            }
            #btemplates-main-menu {
                font-weight: bold;
                position: relative;
                z-index: 8;
                background-color: transparent;
                transition: background-color 0.25s;
            }
            #btemplates-main-menu .btemplates-dropdown {
                width:100%;
            }
            #btemplates-main-menu nav{

            }
            #btemplates-main-menu .nav-item .dropdown-item img {
                width: 100%;
                object-fit: cover;
                transition: all 1.5s cubic-bezier(0, 0, .3, 1);
            }
            #btemplates-main-menu .nav-item a.dropdown-item:hover img {
                transform: scale(1.1);
            }
            #btemplates-main-menu .nav-item a {
                color: rgb(17, 70, 105);
            }
            #btemplates-main-menu .nav-item &gt; a {
                color: #111;
            }
            #btemplates-main-menu .nav-item &gt; a:hover {
                color: #555;
            }
            #btemplates-main-menu .nav-item:last-child a {
                /*padding-right: 0;*/
            }
            .dropdown-submenu {
                position: relative;
            }
            #btemplates-main-menu h2 {
                display: none;
            }
            .dropdown-submenu&gt;a:after {
                content: &quot;\f0da&quot;;
                border: none;
                font-family: &#39;FontAwesome&#39;;
                vertical-align: middle;
            }
            .dropdown-submenu&gt;.dropdown-menu {
                top: 0;
                left: 100%;
                padding-left: 0.5rem;
                margin-top: 0px;
                margin-left: 0px;
            }
            @media (min-width: 991px) {
                .dropdown-menu {
                    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
                }
            }
            #logoImage h2, #logoImage .caption {
                display:none;
            }
            .status-msg-body b {
                position: relative;
            }
            .status-msg-body a {
                display: none;
            }
            #blocksMainMenu h2 {
                display: none;
            }
            #blocksMainMenu a {
                color: #fff;
                font-weight: bold;
            }
            #blocksMainMenu a:hover {
                text-decoration: none;
            }
            .bt-block {
                cursor: pointer;
                transition: opacity 0.25s, margin-top 0.3s linear;
            }
            .bt-block:hover {
                opacity: 0.85;
                margin-top: -1rem;
            }
            .status-msg-wrap {
                background-color: #F3F8FC;
                font-size: 150% !important;
            }
            .status-msg-bg {
                border-radius: 5px;
                opacity: 1;
            }
            .status-msg-body, .status-msg-bg {
                padding: 1rem;
            }
            #bt-posts-1 .bt-post-title a, .btemplates-tags a.bt-tag, #btemplates-posts-slider .bt-post-title a, #bt-blog .bt-post-title a, #bt-videos .bt-post-title a {
                color: #2EB7D7;
            }
            #bt-posts-1 .bt-post-title a:hover, .btemplates-tags a.bt-tag:hover, #btemplates-posts-slider .bt-post-title a:hover, #bt-blog .bt-post-title a:hover, #bt-videos .bt-post-title a:hover {
                color: #5AB6CC;
            }
            #bt-posts-1 {
                color: #666;
            }
            #bt-posts-1 h2 {
                text-align: center;
            }
            #bt-posts-1 .btemplates-post {
                border: solid 1px #eee;
                max-width: 350px;
                transition: background-color 0.5s;
            }
            #bt-posts-1 .btemplates-post:hover {
                background-color: #eee;
            }
            #bt-posts-1 .btemplates-post:hover .bt-post-thumbnail img {
                transform: scale3d(1.1, 1.1, 1.1);
            }
            #bt-posts-1 .btemplates-post:hover .bt-post-author-avatar img {
                transform: rotate(-10deg);
            }
            hr.title-separator {
                width: 100px;
                text-align: center;
                border: solid 1.5px #FAC300;
            }
            hr.subtitle-separator {
                width: 100px;
                text-align: center;
                border: solid 1.5px #eee;
            }
            #bt-posts-1 .bt-post-thumbnail {
                width: 350px;
                height: 180px;
                overflow: hidden;
                float: none;
                max-width: 100%;
            }
            #bt-posts-1 .bt-post-thumbnail img{
                width: 100%;
                height: 100%;
                object-fit: cover;
                border-bottom: 1px solid #eee;
                transition: all 1.5s cubic-bezier(0, 0, .3, 1);
            }
            #bt-posts-1 .bt-post-author-avatar {
                text-align: center;
                margin-top: -25px;
            }
            #bt-posts-1 .bt-post-author-avatar img {
                transition: transform 1s;
                border-color: #eee;
                position: relative;
                z-index: 1;
            }
            #bt-posts-1 .bt-post-title {
                text-align: center;
                margin: 1rem 0;
                font-weight: bold;
            }
            #bt-posts-1 .bt-post-content {
                padding: 0 1rem;
                font-size: 0.9rem;
            }
            #bt-posts-1 .bt-post-location {
                text-align: center;
                padding: 1rem 1rem 0;
                font-size: 0.8rem;
            }
            #bt-posts-1 .bt-post-location .fa, #btemplates-posts-slider .bt-post-location .fa {
                color: rgb(230, 161, 14);
            }
            #bt-posts-1 .bt-post-date {
                text-align: right;
                font-size: 0.7rem;
                padding: 1rem;
                color: #999;
            }
            .parallax {
                background-attachment: fixed;
                background-position: center;
                background-repeat: no-repeat;
                background-size: cover;
            }
            #content-1 {
                text-align: center;
                min-height: 300px;
            }
            #content-2 h2 {
                padding-bottom: 1.5rem;
            }
            #content-1 .Image {
                display: none;
            }
            #btemplates-search h2 {

            }
            #btemplates-search input[type=&#39;text&#39;] {
                padding: 0.5rem;
            }
            #btemplates-search input[type=&#39;submit&#39;] {
                background-color: #43e8d8;
                border: 0;
                border-radius: 0.25rem;
                padding: 0.5rem 2rem;
                color: #fff;
                font-weight: bold;
            }
            #testimonials h2 {
                text-align: center;
            }
            #testimonials .carousel-item {
                text-align: center;
            }
            #testimonials .carousel-inner img {
                width: 175px;
                height: 175px;
            }
            #testimonials .bt-post-content {
                font-size: 1rem;
            }
            #testimonials .bt-post-location {
                color: #999;
            }
            #bt-subscription .Image {
                display: none;
            }
            #bt-subscription {
                text-align: center;
                min-height: 300px;
                color: #fff;
                background-color: #2EB8D7;
            }
            #bt-subscription .input-group-prepend {
                display: none;
            }
            #bt-subscription .bt-widget-description {
                color: #fff;
            }
            #bt-subscription input[type=&#39;text&#39;] {
                padding: 0.75rem;
                font-size: 1rem;
                height: auto;
                width: inherit;
                border: 1px solid #ced4da;
            }
            #bt-subscription input[type=&#39;submit&#39;] {
                font-size: 1rem;
                padding: 0.75rem;
                width: auto;
                height: auto;
                margin-left: 1rem;
                border-radius: 5px;
            }
            #bt-blog h2 {
                text-align: center;
            }
            #bt-blog .bt-post-thumbnail {
                width: 350px;
                height: 180px;
                overflow: hidden;
                float: none;
                max-width: 100%;
            }
            #bt-blog .btemplates-post {
                transition: background-color 0.5s;
            }
            #bt-blog .btemplates-post:hover .bt-post-thumbnail img {
                transform: scale3d(1.1, 1.1, 1.1);
            }
            #bt-blog .btemplates-post:hover {
                background-color: #eee;
            }
            #bt-blog .bt-post-thumbnail img{
                width: 100%;
                height: 100%;
                object-fit: cover;
                border-bottom: 1px solid #eee;
                transition: all 1.5s cubic-bezier(0, 0, .3, 1);
            }
            #bt-blog .bt-post-title {
                text-align: center;
                margin: 1rem 0;
                font-weight: bold;
            }
            #bt-blog .bt-post-content {
                padding: 0 1rem;
                font-size: 0.9rem;
            }
            #bt-blog .bt-post-date {
                text-align: center;
                font-size: 0.7rem;
            }
            #bt-videos {
                background-color: #333;
                color: #fff;
            }
            #bt-videos .Image {
                display: none;
            }
            #bt-videos a {
                color: #fff;
            }
            #bt-videos h2, #bt-videos h3, #bt-videos .bt-post-content {
                text-align: center;
            }
            #bt-contact h2, #bt-contact .bt-widget-description {
                text-align: center;
            }
            #bt-contact .contact-form-widget {
                max-width: 100% !important;
                text-align: center;
            }
            #bt-contact .contact-form-widget .form {
                display: inline-block;
                width: 90%;
                text-align: left;
            }
            #bt-contact input[type=&quot;text&quot;] {
                padding: 0.75rem;
                font-size: 1rem;
                height: auto;
                margin: 0;
            }
            #bt-contact input[type=&quot;button&quot;] {
                font-size: 1rem;
                padding: 0.75rem;
                height: auto;
                border-radius: 5px;
                background-color: rgb(66, 203, 219);
                color: #fff;
            }
            #bt-contact form span {
                color: rgb(66, 203, 219);
            }
            #btemplates-dropdown-2 ul {
                margin-right: auto;
            }
            #btemplates-dropdown-2 .nav-item &gt; a {

            }
            #btemplates-dropdown-2 .nav-item &gt; a:hover {

            }
            #btemplates-social a.nav-link{
                padding: .5rem .7rem;
            }
            #btemplates-social a.nav-link:hover {
                opacity: 0.8;
            }
            #btemplates-dropdown-1 a {
                color: #c41d1d;
            }
            #btemplates-dropdown-1 a:hover {
                color: #D8815F;
            }
            nav.navbar h2 {
                display: none;
            }
            #btemplates-popular-posts .PopularPosts {
                display: none;
            }
            body#layout #btemplates-popular-posts .PopularPosts {
                display: block !important;
            }
            #btemplates-popular-posts .PopularPosts h2 {
                display: block;
                text-align: center;
            }
            #btemplates-popular-posts .PopularPosts img {
                padding-right: 0 !important;
            }

            #btemplates-popular-posts .PopularPosts .widget-item-control {
                margin-top: 0;
            }
            #bt-labels h2 {
                text-align: center;
            }
            .btemplates-tags {
                text-align: center;
            }
            .btemplates-tags a.bt-tag {
                text-align: center;
                display: inline-block;
                margin: 0 1rem 1rem 0;
            }
            .btemplates-tags a:hover img {
                opacity: 0.8;
            }
            .btemplates-tags a img {
                border: 2px solid #333;
                transform: scale(1);
                transition: all 0.3s ease;
                width: 75px;
                height: 75px;
            }
            .btemplates-tags a:hover img, .btemplates-tags a:focus img {
                transform: scale(1.1);
            }


            /* CONTENT WRAPPER */


            #btemplates-first-post {
                display: none;
            }
            body#layout #btemplates-first-post {
                display: block;
            }
            #btemplates-first-post-c h2 {
                display: none;
            }
            #btemplates-first-post-c .widget {
                margin-bottom: 2rem;
            }
            #btemplates-main-content {
                background-color: #fff;
                padding: 15px;
            }
            .breadcrumb, .status-msg-bg {
                background-color: #F3F8FC;
            }
            .post-title a {
            }
            .video-container {
                position:relative;
                padding-bottom:56.25%;
                padding-top:30px;
                height:0;
                overflow:hidden;
            }

            .video-container iframe, .video-container object, .video-container embed {
                position:absolute;
                top:0;
                left:0;
                width:100% !important;
                height:100% !important;
            }
            .post-header-line-1 {
                transition: color 1s;
            }
            .post-header-line-1 .post-labels:hover .fa {
                color: rgb(240, 188, 13) !important;
            }
            .post-header-line-1 .post-labels:hover .rounded-circle {
                border-color: rgb(240, 188, 13) !important;
            }
            .post-header-line-1 .post-author:hover .fa {
                color: rgb(66, 203, 219) !important;
            }
            .post-header-line-1 .post-author:hover .rounded-circle {
                border-color: rgb(66, 203, 219) !important;
            }
            .post-header-line-1 &gt; span {
                margin: 0 0.5rem;
            }
            .post-header-line-1 .rounded-circle {
                width: 1.5em;
                height: 1.5em;
                display: inline-block;
                transition: border-color 1s;
            }
            .post-header-line-1 a {
                color: #444;
            }
            .post-body {
                line-height: 1.5;
            }
            .post-body ul{list-style-type:circle;list-style-position:inside;padding:0 0 0 0.25em;}
            .post-body ol{list-style-type:decimal;list-style-position:inside;padding:0 0 0 0.25em;}
            .post-body a { text-decoration: underline; color: rgb(17, 70, 105); }
            .post-body a:hover { color: rgb(31, 92, 132); }
            .post-body a img: hover {
                border: 1px solid #999;
            }
            .post code{
                background:url(//1.bp.blogspot.com/_Zuzii37VUO4/TUws668Wr6I/AAAAAAAAFX0/LgnevWURtjQ/s000/code.png) no-repeat 0 5px;padding:0 35px 0 0;display:block;min-height:35px;padding:0 0 0 30px;
            }
            .post table {
                border-color:#CDCDCD;border-style:solid;border-width:1px 0;width:100%;text-align:center;
            }
            .post table td,.post table th {
                border-bottom:1px solid #EFEFEF;padding:5px 15px 5px 0;
            }
            .post img {
                max-width: 100%;
            }
            .post .posts-list-tag {

            }
            .post .posts-list-tag li {
                list-style: none;
                border-bottom: 1px solid #F3F8FC;
                line-height: 3;
                transition: background-color 0.5s;
            }
            .post .posts-list-tag li:hover {
                background-color: #DBE4EC;
            }
            .post .posts-list-tag li a {
                text-decoration: none;
                display: block;
                transition: color 0.5s;
            }
            .post-footer-line {
                margin-bottom: 0.5rem;
            }
            .post-footer .post-timestamp {
                font-size: 80%;
            }
            .bt-post-share-buttons a {
                text-align: center;
                border: 2px solid #999;
                border-radius: 50%;
                width: 2em;
                height: 2em;
                display: inline-block;
                line-height: 2;
            }
            .bt-post-share-buttons a i {
                transition: font-size 0.5s;
            }
            .bt-post-share-buttons a:hover i {
                font-size: 125%;
            }
            .bt-post-share-buttons a[href$=&quot;email&quot;] {
                border-color: rgb(240, 188, 13);
                color: rgb(240, 188, 13);
            }
            .bt-post-share-buttons a[href$=&quot;facebook&quot;] {
                border-color: #3b5998;
                color: #3b5998;
            }
            .bt-post-share-buttons a[href$=&quot;twitter&quot;] {
                border-color: #55acee;
                color: #55acee;
            }
            .bt-post-share-buttons a[href$=&quot;pinterest&quot;] {
                border-color: #CB2125;
                color: #CB2125;
            }
            .bt-post-share-buttons a[href$=&quot;tools.html&quot;] {
                border-color: #28AE00;
                color: #28AE00;
            }
            .post-author, .Profile .profile-name-link {
            }
            #btemplates-author-box {
                box-shadow: 0 0 50px .1px rgba(0,0,0,0.07);
                box-sizing: border-box;
                border-radius: 7px;
                padding: 1rem;
                margin: 1rem 0 1.75rem;
                transition: box-shadow 1s;
            }
            #btemplates-author-box:hover {
                box-shadow: 0 0 50px .1px #CFDEEA;
            }
            #btemplates-author-box img.rounded-circle{
                width: 75px;
                height: 75px;
            }
            #btemplates-author-box a[rel=&#39;author&#39;] {
                font-weight: bold;
                font-size: 1.25rem;
                margin-bottom: 0.75rem;
                display: block;
            }
            #btemplates-author-box span[itemprop=&#39;description&#39;] {
                color: #444;
            }
            #blog-pager {
                margin-bottom: 1.5rem;
            }
            #blog-pager .btemplates-post:first-child::before {
                content: &#39; Newer post&#39;;
            }
            #blog-pager .btemplates-post:last-child::before {
                content: &#39;Older post &gt;&#39;;
            }
            #blog-pager .bt-post-thumbnail {
                width: 100%;
                height: 150px;
            }
            #blog-pager .bt-post-title {
            }
            #blog-pager a {
                color: #212529;
            }
            #blog-pager .bt-post-content {
                display:none;
            }
            #blog-pager .bt-post-date {
                display: none;
                color: #999;
            }
            .home-link::before {
                content: &#39;\00a0\f015&#39;;
                font-family: fontAwesome;
            }
            .blog-pager-older-link::after {
                content: &#39;\00a0\f105&#39;;
                font-family: fontAwesome;
            }
            .blog-pager-newer-link::before {
                content: &#39;\f104\00a0&#39;;
                font-family: fontAwesome;
            }
            .status-msg-wrap {
                width: 100%;
                margin: 0 auto 2em;
                font-size: 125%;
            }
            .status-msg-border {
                border: 0;
            }
            /* SIDEBAR */
            #sidebar-wrapper .widget {
                margin-bottom: 1em;
            }
            #sidebar-wrapper .widget h2, #footers .widget h2 {
                padding-bottom: 0.5em;
                margin-bottom: 0.5em;
                border-bottom: 1px solid #FAC300 !important;
            }
            #sidebar-wrapper h2 {

            }
            #sidebar-wrapper ul {
                padding: 0;
            }
            #sidebar-wrapper li {

            }
            #sidebar-wrapper .widget {

            }
            #sidebar-wrapper .widget-content {

            }
            #sidebar .widget, #footers .widget {
                margin-bottom: 2.5em;
            }
            #sidebar .FollowByEmail, #footers .FollowByEmail {
                border: solid 1px #67eaca;
                padding: 1em;
                background-color: #3bccce;
                color:#fff;
            }
            #sidebar .FollowByEmail .bt-widget-description, #footers .FollowByEmail .bt-widget-description{
                color:#fff;
            }
            #sidebar input[type=text] {
            }
            #sidebar input[type=submit] {
                cursor: pointer;
            }
            #sidebar .FollowByEmail input[type=submit], #footers .FollowByEmail input[type=submit] {
                background-color: #111;
            }
            #sidebar .PopularPosts ul , #footers .PopularPosts ul {
                padding: 0;
            }
            #sidebar .PopularPosts li, #footers .PopularPosts li {
                list-style: none;
            }
            #sidebar .PopularPosts .item-thumbnail, #footers .PopularPosts .item-thumbnail {
                width:75px;
                float:left;
            }
            #sidebar .PopularPosts .item-thumbnail img, #footers .PopularPosts .item-thumbnail img {
                width:75px;
            }
            #sidebar .PopularPosts .item-title, #footers .PopularPosts .item-title {
                font-size:0.9em;
            }
            #sidebar .PopularPosts .item-snippet, #footers .PopularPosts .item-snippet {
                display: none;
            }

            #sidebar .Label ul, #footers .Label ul {
            }
            .cloud-label-widget-content {
                color: #fff;
            }
            .cloud-label-widget-content .label-size {
                background-color: #13a5a5;
                margin: 0.05rem;
                padding: 0.2rem;
                border-radius: 5px;
                display: inline-block;
            }
            .cloud-label-widget-content a {
                color: #fff;
            }
            #sidebar-icons a {
                color: #666;
                text-decoration:none;
            }
            .Profile .widget-content {
                text-align:center;
            }
            .Profile ul {
                text-align: left;
            }
            .Profile li a {
                padding: 0 0.5em 0 0.3em;
            }
            .Profile li:before {
                content: &#39;\f2bd&#39;;
                font-family: fontAwesome;
            }
            .Profile li {
                list-style: none;
            }
            .Profile .profile-name-link {
                background-image: none !important;
                font-size: 1.1em;
            }
            .Profile &gt; div:nth-child(2) &gt; a:nth-child(1) img {
                display:block;
                float:none;
                margin: 0.5em auto;
                width: 125px;
                height: 125px !important;
            }
            .Profile .profile-link{
                font-size: 80%;
            }
            #sidebar .btemplates-post, #footers .btemplates-post {
                clear: both;
                margin-bottom:1em;
            }
            #sidebar .btemplates-post:hover .bt-post-thumbnail img, #footers .btemplates-post:hover .bt-post-thumbnail img {
                transform: scale3d(1.1, 1.1, 1.1);
            }
            #sidebar .bt-post-thumbnail, #footers .bt-post-thumbnail {
                margin:0 0.5em 1em 0;
                float:left;
            }
            #sidebar .bt-post-thumbnail img, #footers .bt-post-thumbnail img {
                transition: all 1.5s cubic-bezier(0, 0, .3, 1);
            }
            #sidebar .bt-post-title, #footers .bt-post-title {

            }
            #sidebar .bt-post-content, #footers .bt-post-content {
                display:none;
            }
            #sidebar .bt-post-date, #footers .bt-post-date {
                font-size: 70%;
                float: right;
                color: #999;
            }
            #footers .fa, #sidebar .fa {
                background-color: #efefef;
                color: #fff;
                font-size: 1.75rem;
                width: 2.5rem;
                height: 2.5rem;
                border-radius: 50% !important;
                vertical-align: middle;
                margin: 0 1rem 0.5rem 0;
                float: left;
            }
            #footers .fa:hover, #sidebar .fa:hover {
                opacity: 0.75;
            }
            #footers .fa.fa-500px, #sidebar .fa.fa-500px {
                background-color: #0099e5;
            }
            #footers .fa.fa-adn, #sidebar .fa.fa-adn {
                background-color: #4a484c;
            }
            #footers .fa.fa-amazon, #sidebar .fa.fa-amazon {
                background-color: #ff9900;
            }
            #footers .fa.fa-android, #sidebar .fa.fa-android {
                background-color: #a4c639;
            }
            #footers .fa.fa-angellist, #sidebar .fa.fa-angellist {
                background-color: #000;
            }
            #footers .fa.fa-apple, #sidebar .fa.fa-apple {
                background-color: #979797;
            }
            #footers .fa.fa-behance, #sidebar .fa.fa-behance {
                background-color: #1769ff;
            }
            #footers .fa.fa-behance-square, #sidebar .fa.fa-behance-square {
                background-color: #1769ff;
            }
            #footers .fa.fa-bitbucket, #sidebar .fa.fa-bitbucket {
                background-color: #205081;
            }
            #footers .fa.fa-bitbucket-square, #sidebar .fa.fa-bitbucket-square {
                background-color: #205081;
            }
            #footers .fa.fa-bitcoin, #sidebar .fa.fa-bitcoin {
                background-color: #ee9209;
            }
            #footers .fa.fa-black-tie, #sidebar .fa.fa-black-tie {
                background-color: #222;
            }
            #footers .fa.fa-btc, #sidebar .fa.fa-btc {
                background-color: #ee9209;
            }
            #footers .fa.fa-buysellads, #sidebar .fa.fa-buysellads {
                background-color: #c90100;
            }
            #footers .fa.fa-cc-amex, #sidebar .fa.fa-cc-amex {
                background-color: #007bc1;
            }
            #footers .fa.fa-cc-diners-club, #sidebar .fa.fa-cc-diners-club {
                background-color: #004a97;
            }
            #footers .fa.fa-cc-discover, #sidebar .fa.fa-cc-discover {
                background-color: #f68121;
            }
            #footers .fa.fa-cc-jcb, #sidebar .fa.fa-cc-jcb {
                background-color: #003a8f;
            }
            #footers .fa.fa-cc-mastercard, #sidebar .fa.fa-cc-mastercard {
                background-color: #0a3a82;
            }
            #footers .fa.fa-cc-paypal, #sidebar .fa.fa-cc-paypal {
                background-color: #253b80;
            }
            #footers .fa.fa-cc-stripe, #sidebar .fa.fa-cc-stripe {
                background-color: #00afe1;
            }
            #footers .fa.fa-cc-visa, #sidebar .fa.fa-cc-visa {
                background-color: #0157a2;
            }
            #footers .fa.fa-chrome, #sidebar .fa.fa-chrome {
                background-color: #4587f3;
            }
            #footers .fa.fa-codepen, #sidebar .fa.fa-codepen {
                background-color: #000;
            }
            #footers .fa.fa-connectdevelop, #sidebar .fa.fa-connectdevelop {
                background-color: #391448;
            }
            #footers .fa.fa-contao, #sidebar .fa.fa-contao {
                background-color: #eb8623;
            }
            #footers .fa.fa-creative-commons, #sidebar .fa.fa-creative-commons {
                background-color: #231f20;
            }
            #footers .fa.fa-css3, #sidebar .fa.fa-css3 {
                background-color: #1680c0;
            }
            #footers .fa.fa-dashcube, #sidebar .fa.fa-dashcube {
                background-color: #7f7f7f;
            }
            #footers .fa.fa-delicious, #sidebar .fa.fa-delicious {
                background-color: #3399ff;
            }
            #footers .fa.fa-deviantart, #sidebar .fa.fa-deviantart {
                background-color: #4e6252;
            }
            #footers .fa.fa-digg, #sidebar .fa.fa-digg {
                background-color: #000;
            }
            #footers .fa.fa-dribbble, #sidebar .fa.fa-dribbble {
                background-color: #444444;
            }
            #footers .fa.fa-dropbox, #sidebar .fa.fa-dropbox {
                background-color: #007ee5;
            }
            #footers .fa.fa-drupal, #sidebar .fa.fa-drupal {
                background-color: #0077c0;
            }
            #footers .fa.fa-empire, #sidebar .fa.fa-empire {
                background-color: #000;
            }
            #footers .fa.fa-expeditedssl, #sidebar .fa.fa-expeditedssl {
                background-color: #343433;
            }
            #footers .fa.fa-facebook, #sidebar .fa.fa-facebook {
                background-color: #3b5998;
            }
            #footers .fa.fa-etsy, #sidebar .fa.fa-etsy {
                background-color: #F45700;
            }
            #footers .fa.fa-facebook-official, #sidebar .fa.fa-facebook-official {
                background-color: #3b5998;
            }
            #footers .fa.fa-facebook-square, #sidebar .fa.fa-facebook-square {
                background-color: #3b5998;
            }
            #footers .fa.fa-firefox, #sidebar .fa.fa-firefox {
                background-color: #e66000;
            }
            #footers .fa.fa-flickr, #sidebar .fa.fa-flickr {
                background-color: #ff0084;
            }
            #footers .fa.fa-fonticons, #sidebar .fa.fa-fonticons {
                background-color: #1c1e29;
            }
            #footers .fa.fa-forumbee, #sidebar .fa.fa-forumbee {
                background-color: #83ad13;
            }
            #footers .fa.fa-foursquare, #sidebar .fa.fa-foursquare {
                background-color: #0072b1;
            }
            #footers .fa.fa-ge, #sidebar .fa.fa-ge {
                background-color: #000;
            }
            #footers .fa.fa-get-pocket, #sidebar .fa.fa-get-pocket {
                background-color: #d3505a;
            }
            #footers .fa.fa-gg, #sidebar .fa.fa-gg {
                background-color: #000;
            }
            #footers .fa.fa-gg-circle, #sidebar .fa.fa-gg-circle {
                background-color: #000;
            }
            #footers .fa.fa-git, #sidebar .fa.fa-git {
                background-color: #333;
            }
            #footers .fa.fa-git-square, #sidebar .fa.fa-git-square {
                background-color: #333;
            }
            #footers .fa.fa-github, #sidebar .fa.fa-github {
                background-color: #333;
            }
            #footers .fa.fa-github-alt, #sidebar .fa.fa-github-alt {
                background-color: #333;
            }
            #footers .fa.fa-github-square, #sidebar .fa.fa-github-square {
                background-color: #333;
            }
            #footers .fa.fa-gittip, #sidebar .fa.fa-gittip {
                background-color: #663300;
            }
            #footers .fa.fa-google, #sidebar .fa.fa-google {
                background-color: #4285f4;
            }
            #footers .fa.fa-google-plus, #sidebar .fa.fa-google-plus {
                background-color: #dd4b39;
            }
            #footers .fa.fa-google-plus-square, #sidebar .fa.fa-google-plus-square {
                background-color: #dd4b39;
            }
            #footers .fa.fa-google-wallet, #sidebar .fa.fa-google-wallet {
                background-color: #4285f4;
            }
            #footers .fa.fa-hacker-news, #sidebar .fa.fa-hacker-news {
                background-color: #ff6600;
            }
            #footers .fa.fa-houzz, #sidebar .fa.fa-houzz {
                background-color: #7ac142;
            }
            #footers .fa.fa-html5, #sidebar .fa.fa-html5 {
                background-color: #e34f26;
            }
            #footers .fa.fa-instagram, #sidebar .fa.fa-instagram {
                background-color: #3f729b;
            }
            #footers .fa.fa-internet-explorer, #sidebar .fa.fa-internet-explorer {
                background-color: #1ebbee;
            }
            #footers .fa.fa-ioxhost, #sidebar .fa.fa-ioxhost {
                background-color: #faa729;
            }
            #footers .fa.fa-joomla, #sidebar .fa.fa-joomla {
                background-color: #142849;
            }
            #footers .fa.fa-jsfiddle, #sidebar .fa.fa-jsfiddle {
                background-color: #4679bd;
            }
            #footers .fa.fa-lastfm, #sidebar .fa.fa-lastfm {
                background-color: #c3000d;
            }
            #footers .fa.fa-lastfm-square, #sidebar .fa.fa-lastfm-square {
                background-color: #c3000d;
            }
            #footers .fa.fa-leanpub, #sidebar .fa.fa-leanpub {
                background-color: #0c0c0c;
            }
            #footers .fa.fa-linkedin, #sidebar .fa.fa-linkedin {
                background-color: #0976b4;
            }
            #footers .fa.fa-linkedin-square, #sidebar .fa.fa-linkedin-square {
                background-color: #0976b4;
            }
            #footers .fa.fa-linux, #sidebar .fa.fa-linux {
                background-color: #333333;
            }
            #footers .fa.fa-maxcdn, #sidebar .fa.fa-maxcdn {
                background-color: #ff6600;
            }
            #footers .fa.fa-meanpath, #sidebar .fa.fa-meanpath {
                background-color: #538ed7;
            }
            #footers .fa.fa-medium, #sidebar .fa.fa-medium {
                background-color: #000;
            }
            #footers .fa.fa-odnoklassniki, #sidebar .fa.fa-odnoklassniki {
                background-color: #ed812b;
            }
            #footers .fa.fa-odnoklassniki-square, #sidebar .fa.fa-odnoklassniki-square {
                background-color: #ed812b;
            }
            #footers .fa.fa-opencart, #sidebar .fa.fa-opencart {
                background-color: #2ac2ef;
            }
            #footers .fa.fa-openid, #sidebar .fa.fa-openid {
                background-color: #f78c40;
            }
            #footers .fa.fa-opera, #sidebar .fa.fa-opera {
                background-color: #cc0f16;
            }
            #footers .fa.fa-optin-monster, #sidebar .fa.fa-optin-monster {
                background-color: #83c11f;
            }
            #footers .fa.fa-pagelines, #sidebar .fa.fa-pagelines {
                background-color: #000;
            }
            #footers .fa.fa-paypal, #sidebar .fa.fa-paypal {
                background-color: #253b80;
            }
            #footers .fa.fa-pied-piper, #sidebar .fa.fa-pied-piper {
                background-color: #2f9f46;
            }
            #footers .fa.fa-pied-piper-alt, #sidebar .fa.fa-pied-piper-alt {
                background-color: #2f9f46;
            }
            #footers .fa.fa-pied-piper-square, #sidebar .fa.fa-pied-piper-square {
                background-color: #2f9f46;
            }
            #footers .fa.fa-pinterest, #sidebar .fa.fa-pinterest {
                background-color: #cc2127;
            }
            #footers .fa.fa-pinterest-p, #sidebar .fa.fa-pinterest-p {
                background-color: #cc2127;
            }
            #footers .fa.fa-pinterest-square, #sidebar .fa.fa-pinterest-square {
                background-color: #cc2127;
            }
            #footers .fa.fa-qq, #sidebar .fa.fa-qq {
                background-color: #000;
            }
            #footers .fa.fa-ra, #sidebar .fa.fa-ra {
                background-color: #000;
            }
            #footers .fa.fa-rebel, #sidebar .fa.fa-rebel {
                background-color: #000;
            }
            #footers .fa.fa-reddit, #sidebar .fa.fa-reddit {
                background-color: #ff4500;
            }
            #footers .fa.fa-reddit-square, #sidebar .fa.fa-reddit-square {
                background-color: #ff4500;
            }
            #footers .fa.fa-renren, #sidebar .fa.fa-renren {
                background-color: #005eac;
            }
            #footers .fa.fa-safari, #sidebar .fa.fa-safari {
                background-color: #1b88ca;
            }
            #footers .fa.fa-sellsy, #sidebar .fa.fa-sellsy {
                background-color: #1f78b9;
            }
            #footers .fa.fa-share-alt, #sidebar .fa.fa-share-alt {
                background-color: #01bf01;
            }
            #footers .fa.fa-share-alt-square, #sidebar .fa.fa-share-alt-square {
                background-color: #01bf01;
            }
            #footers .fa.fa-shirtsinbulk, #sidebar .fa.fa-shirtsinbulk {
                background-color: #dd3a26;
            }
            #footers .fa.fa-simplybuilt, #sidebar .fa.fa-simplybuilt {
                background-color: #000;
            }
            #footers .fa.fa-skyatlas, #sidebar .fa.fa-skyatlas {
                background-color: #00adbb;
            }
            #footers .fa.fa-skype, #sidebar .fa.fa-skype {
                background-color: #00aff0;
            }
            #footers .fa.fa-slack, #sidebar .fa.fa-slack {
                background-color: #0f7965;
            }
            #footers .fa.fa-slideshare, #sidebar .fa.fa-slideshare {
                background-color: #e98325;
            }
            #footers .fa.fa-soundcloud, #sidebar .fa.fa-soundcloud {
                background-color: #f80;
            }
            #footers .fa.fa-spotify, #sidebar .fa.fa-spotify {
                background-color: #7ab800;
            }
            #footers .fa.fa-stack-exchange, #sidebar .fa.fa-stack-exchange {
                background-color: #000;
            }
            #footers .fa.fa-stack-overflow, #sidebar .fa.fa-stack-overflow {
                background-color: #fe7a15;
            }
            #footers .fa.fa-steam, #sidebar .fa.fa-steam {
                background-color: #0b0b0b;
            }
            #footers .fa.fa-steam-square, #sidebar .fa.fa-steam-square {
                background-color: #0b0b0b;
            }
            #footers .fa.fa-stumbleupon, #sidebar .fa.fa-stumbleupon {
                background-color: #eb4924;
            }
            #footers .fa.fa-stumbleupon-circle, #sidebar .fa.fa-stumbleupon-circle {
                background-color: #eb4924;
            }
            #footers .fa.fa-tencent-weibo, #sidebar .fa.fa-tencent-weibo {
                background-color: #74af2c;
            }
            #footers .fa.fa-trello, #sidebar .fa.fa-trello {
                background-color: #256a92;
            }
            #footers .fa.fa-tripadvisor, #sidebar .fa.fa-tripadvisor {
                background-color: #589442;
            }
            #footers .fa.fa-tumblr, #sidebar .fa.fa-tumblr {
                background-color: #35465c;
            }
            #footers .fa.fa-tumblr-square, #sidebar .fa.fa-tumblr-square {
                background-color: #35465c;
            }
            #footers .fa.fa-twitch, #sidebar .fa.fa-twitch {
                background-color: #6441a5;
            }
            #footers .fa.fa-twitter, #sidebar .fa.fa-twitter {
                background-color: #55acee;
            }
            #footers .fa.fa-twitter-square, #sidebar .fa.fa-twitter-square {
                background-color: #55acee;
            }
            #footers .fa.fa-viacoin, #sidebar .fa.fa-viacoin {
                background-color: #333;
            }
            #footers .fa.fa-vimeo, #sidebar .fa.fa-vimeo {
                background-color: #1ab7ea;
            }
            #footers .fa.fa-vimeo-square, #sidebar .fa.fa-vimeo-square {
                background-color: #1ab7ea;
            }
            #footers .fa.fa-vine, #sidebar .fa.fa-vine {
                background-color: #00b488;
            }
            #footers .fa.fa-vk, #sidebar .fa.fa-vk {
                background-color: #45668e;
            }
            #footers .fa.fa-wechat, #sidebar .fa.fa-wechat {
                background-color: #93d034;
            }
            #footers .fa.fa-weibo, #sidebar .fa.fa-weibo {
                background-color: #e71d34;
            }
            #footers .fa.fa-weixin, #sidebar .fa.fa-weixin {
                background-color: #93d034;
            }
            #footers .fa.fa-wikipedia-w, #sidebar .fa.fa-wikipedia-w {
                background-color: #000;
            }
            #footers .fa.fa-windows, #sidebar .fa.fa-windows {
                background-color: #00bcf2;
            }
            #footers .fa.fa-wordpress, #sidebar .fa.fa-wordpress {
                background-color: #21759b;
            }
            #footers .fa.fa-xing, #sidebar .fa.fa-xing {
                background-color: #026466;
            }
            #footers .fa.fa-xing-square, #sidebar .fa.fa-xing-square {
                background-color: #026466;
            }
            #footers .fa.fa-y-combinator, #sidebar .fa.fa-y-combinator {
                background-color: #f0652f;
            }
            #footers .fa.fa-yc, #sidebar .fa.fa-yc {
                background-color: #f0652f;
            }
            #footers .fa.fa-yahoo, #sidebar .fa.fa-yahoo {
                background-color: #400191;
            }
            #footers .fa.fa-yelp, #sidebar .fa.fa-yelp {
                background-color: #af0606;
            }
            #footers .fa.fa-youtube, #sidebar .fa.fa-youtube {
                background-color: #e52d27;
            }
            #footers .fa.fa-youtube-play, #sidebar .fa.fa-youtube-play {
                background-color: #e52d27;
            }
            #footers .fa.fa-youtube-square, #sidebar .fa.fa-youtube-square {
                background-color: #e52d27;
            }
            .btemplates-comment {
                clear: both;
            }
            .bt-comment-avatar {

            }
            .bt-comment-avatar img {
                width: 50px;
                height: 50px;
                margin: 0 0.5em 1em 0;
            }
            .bt-comment-author {

            }
            .bt-comment-content {
                font-size: 0.8rem;
            }
            .Label li {
                clear:both;
                margin-bottom: 0.5em;
                list-style: none;
            }
            .Label li::before {
            }
            .Label span[dir=&#39;ltr&#39;] {
                width: 1.5em;
                height: 1.5em;
            }
            .ContactForm input, .ContactForm textarea {
                max-width: 100%;
            }
            .ContactForm input[type=&#39;button&#39;] {
                width: 100%;
                background-color: #43e8d8;
                color: #fff;
                background-image: none;
                border: 0;
            }
            .ContactForm form span {
                color: #43e8d8;
            }
            .Feed li {
                clear:both;
                margin-bottom: 0.5em;
                list-style: none;
            }
            .Feed li::before {
                content: &#39;\f101  &#39;;
                font-family: fontAwesome;
            }
            .Feed .item-date {
                color: #999;
            }
            .bt-comment-date a {
                font-size: 0.8rem;
                float: right;
                color: #999;
            }
            .Image img {
                max-width: 100%;
            }
            /* FOOTER */

            #footers {
                background-color: rgb(17, 70, 105);
                color: #fff;
            }
            #footers a {
                color: #fff;
            }
            #footers h2, #footers .bt-post-date, #footers .bt-comment-date a {
                color: #fff;
            }
            #footer-wrapper a {
                color: rgb(140, 209, 255);
            }
            #footers .section img, #sidebar-wrapper img {
                max-width: 100%;
                height: auto;
            }
            #footers .widget-item-control .quickedit, #btemplates-dropdown-2  .widget-item-control .quickedit {
                opacity: 1;
            }
            #footer-menu h2 {
                display: none;
            }
            #footer-menu ul {
                margin: 0;
                padding: 0;
            }
            #footer-menu li {
                display: inline;
                padding-right: 1rem;
            }
            #footer-menu li:last-child {
                padding-right: 0;
            }

            /* COMMENTS */

            #comments {
                margin-bottom: 1.5rem;
            }
            #top-ra {
                margin-bottom: 2em;
            }
            #top-ra &gt; .comment {
                border: 1px solid #dee2e6;
                margin: 0 0 1em;
                padding: 1em;
            }
            .comment-content {
                word-break: break-word;
            }
            .comments .comments-content .datetime {
                margin-left: 0;
                display: block;
            }
            .comments .comments-content .datetime a{
                color: #999;
                font-size:0.9em;
            }
            a.comment-reply {
                display: inline !important;
                background-color: #3bccce;
                color: #fff;
            }
            .comment-form {
                max-width:100% !important;
            }
            p.comment-footer {
                text-align:center;
            }
            dd.comment-footer, dd.comment-body {
                margin:0;
            }

            .bt-widget-description {
                color: #888;
            }
            #main-wrapper .FollowByEmail {
                background-color: #f8f9fa;
                padding: 2em;
            }
            #main-wrapper .FollowByEmail h2 {
                border-bottom: 1px solid #666;
                padding-bottom: 1em;
                margin-bottom: 1em;
                font-size: 1.75em;
                text-align: center;
            }
            #main-wrapper .FollowByEmail .bt-widget-description {
                text-align: center;
            }
            #main-wrapper .FollowByEmail input[type=text] {
                height: 3em;
                padding: 1em;
                font-size: 0.9em;
            }
            #main-wrapper .FollowByEmail input[type=submit] {
                height: 3em;
                font-size: 0.9em;
                padding: 0;
                font-weight: bold;
                background-color: #43e8d8;
            }

            /* Portfolio */
            .btemplates-portfolio {}
            #portfolio-footer {
                text-align: center;
                width: 100%;
            }
            #portfolio-footer h2 {
                text-align: center;
                font-size:2.5rem;
            }
            .btemplates-portfolio h3 {
                font-size: 1.25rem;
            }
            .btemplates-portfolio .item {
                position: relative;
                width: 100%;
                display: block;
                overflow: hidden;
                z-index: 0;
                cursor: pointer;
            }
            .btemplates-portfolio .item:after {
                position: absolute;
                top: 0;
                left: 0;
                right: 0;
                bottom: 0;
                content: &#39;&#39;;
                background: #000;
                opacity: 0;
                z-index: 1;
                transition: all 0.3s ease;
            }
            .btemplates-portfolio .item:hover:after, .btemplates-portfolio .item:focus:after {
                opacity: .8;
            }
            .btemplates-portfolio .item:hover .item-title, .btemplates-portfolio .item:focus .item-title {
                opacity: 1;
                top: 0;
            }
            .btemplates-portfolio .item:hover img, .btemplates-portfolio .item:focus img {
                transform: scale(1.3);
            }
            .btemplates-portfolio .item img {
                transform: scale(1);
                z-index: -1;
                max-width: 100%;
                height: auto;
                transition: all 0.6s ease;
                padding-right: 0 !important;
            }
            .btemplates-portfolio .item-title {
                position: absolute;
                top: -100px;
                left: 0;
                right: 0;
                padding: 1em;
                opacity: 0;
                z-index: 2;
                transition: all 0.6s ease;
                color: #fff;
                text-align: center;
            }
            .btemplates-portfolio .item-title a {
                color: #fff;
            }
            .btemplates-portfolio .item-title a:hover {
                color: #43e8d8;
            }
            .btemplates-portfolio .item-title span {
                font-size: 14px;
                text-transform: uppercase;
                letter-spacing: 2px;
                color: rgba(255, 255, 255, 0.8);
            }
            .btemplates-portfolio .item-title h3 a {
                color: #fff;
            }
            /* 404 Error page */
            #btemplates-404 h4 {
                font-size:2.5em;
            }
            #btemplates-404 p {
                margin-bottom: 2em;
            }
            #btemplates-404 img {
                margin-bottom: 2em;
                max-width: 100%;
            }
            #btemplates-error-404 h2 {
                text-align: center;
            }

            @keyframes heartbeat
            {
                0%
                {
                    transform: scale( .75 );
                }
                20%
                {
                    transform: scale( 1 );
                }
                40%
                {
                    transform: scale( .75 );
                }
                60%
                {
                    transform: scale( 1 );
                }
                80%
                {
                    transform: scale( .75 );
                }
                100%
                {
                    transform: scale( .75 );
                }
            }
            #thanks-for-keeping-this .fa-heart:hover {
                animation: heartbeat 1s infinite;
            }
            #back-top {
                position: fixed;
                right: 20px;
                bottom: 0;
                z-index: 1041;
                width: 40px;
                height: 40px;
                text-indent: 0;
                -webkit-transition-duration: 0s;
                -moz-transition-duration: 0s;
                -o-transition-duration: 0s;
                color: #e8e8e8;
                font-size: 32px;
                line-height: 26px;
                padding: 4px 0 0;
                text-align: center;
                border-radius: 5px 5px 0 0;
                display: none;
                background-color: rgb(16, 52, 77);
            }
            .introjs-tooltiptext a{
                color: #007bff;
            }
            /* Navigation */

            #blog-pager-newer-link {float: left;}
            #blog-pager-older-link {float: right;}
            #blog-pager {text-align: center; }
            .introjs-donebutton {
                color: green !important;
                font-weight: bold !important;
                background-color: #fff !important;
                background-image: none !important;
            }

            @media (min-width: 576px) {
                #bt-header {
                    height: 35rem;
                }
                .btemplates-tags a img {
                    border: 3px solid #333;
                    width: 100px;
                    height: 100px;
                }
                #testimonials .carousel-inner img {
                    width: 250px;
                    height: 250px;
                }
                #testimonials .bt-post-content {
                    font-size: 1.25rem;
                }
                #bt-subscription input[type=&quot;text&quot;] {
                    width: auto;
                }
                #bt-subscription .input-group-prepend {
                    display: inherit;
                }
                #btemplates-author-box img.rounded-circle{
                    width: 120px;
                    height: 120px;
                }
            }

            @media (min-width: 768px) {
                #btemplates-main-content {
                }
                #btemplates-main-menu .btemplates-dropdown {
                    width: auto;
                }
                #blog-pager .btemplates-post {
                    width: 49%;
                    float: left;
                }

                #header {
                    margin-top: -4rem;
                }

                #btemplates-dropdown-2 {
                    font-size: 0.85rem;
                }

                #bt-header {
                    height: 35rem;
                }

                #btemplates-main-menu .navbar li {
                    margin: 0 0.1rem;
                }
                .btemplates-portfolio h3 {
                    font-style: inherit;
                }
                .btemplates-portfolio .item-title {
                    padding: 2em;
                }
                #btemplates-author-box img.rounded-circle{
                    width: 150px;
                    height: 150px;
                }
            }

            @media (min-width: 992px) {

            }

            @media (min-width: 1200px) {
                #btemplates-main-menu .navbar li {
                    margin: 0 0.25rem;
                }
            }

        </style>
        <link href='https://fonts.googleapis.com/css?family=Rubik&amp;display=swap' rel='stylesheet'/>

    </head>

    <body>
        <div id='outer-wrapper'><div id='wrap2'>

            <!-- skip links for text browsers - saltar a contenido -->
            <span id='skiplinks' style='display:none;'>
                <a href='#main'>skip to main (ir a principal) </a> |
                <a href='#sidebar'>skip to sidebar (ir al sidebar)</a>
            </span>

            <b:section id='settings' maxwidgets='1' name='Template Options' showaddelement='no'/>

            <div class='container-fluid btemplates-dropdown' id='btemplates-dropdown-2'>
                <!-- Menu Link -->
                <div class='d-flex justify-content-between'>
                    <nav class='navbar navbar-expand-lg navbar-light d-none py-0 '>
                        <button aria-controls='navbarNav' aria-expanded='false' aria-label='Toggle navigation' class='navbar-toggler' data-target='#topMenu' data-toggle='collapse' type='button'>
                            <span class='navbar-toggler-icon'/>
                        </button>
                        <b:section class='crosscol collapse navbar-collapse' id='topMenu' maxwidgets='1' name='Top Menu' showaddelement='yes'/>
                    </nav>
                    <div class='navbar-simple d-none' id='btemplates-social'>
                        <b:section id='SocialNetworks' maxwidgets='1' name='Social media icons' showaddelement='yes'>
                          <b:widget id='LinkList68' locked='false' title='Top Links Menu' type='LinkList' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='sorting'>NONE</b:widget-setting>
                              <b:widget-setting name='text-0'>Telegram</b:widget-setting>
                              <b:widget-setting name='link-0'>https://t.me/joinchat/SwbejKmZIwNpSuwF</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>

                                    <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
                                    <div class='widget-content'>
                                        <ul>
                                            <b:loop values='data:links' var='link'>
                                                <li><a expr:href='data:link.target'><data:link.name/></a></li>
                                            </b:loop>
                                        </ul>
                                        <b:include name='quickedit'/>
                                    </div>
                                </b:includable>
                          </b:widget>
                        </b:section>
                    </div>
                </div>
                <!-- /Menu links -->
            </div>


            <div class='container-fluid border-bottom py-2' id='btemplates-main-menu'>
                <div class='container'>
                    <div class='btemplates-dropdown'>
                        <nav class='navbar navbar-light navbar-expand-lg d-none pr-0'>
                            <div class='align-self-center'>
                                <b:section id='logoImage' maxwidgets='1' name='Site Logo' showaddelement='false'/>
                            </div>
                            <button aria-controls='navbarNav' aria-expanded='false' aria-label='Toggle navigation' class='navbar-toggler' data-target='#MainMenu' data-toggle='collapse' type='button'>
                                <span class='navbar-toggler-icon'/>
                            </button>
                            <b:section class='crosscol collapse navbar-collapse justify-content-lg-end' id='MainMenu' maxwidgets='1' name='Main Menu' showaddelement='yes'>
                              <b:widget id='BlogSearch2' locked='false' title='Search Blog' type='BlogSearch'>
                                <b:includable id='main'>
    <!-- only display title if it's non-empty -->
    <b:if cond='data:title != &quot;&quot;'>
      <h2 class='title'><data:title/></h2>
    </b:if>

    <div class='widget-content'>
      <div expr:id='data:widget.instanceId + &quot;_form&quot;'>
        <form class='gsc-search-box' expr:action='data:blog.searchUrl'>
          <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
          <table cellpadding='0' cellspacing='0' class='gsc-search-box'>
            <tbody>
              <tr>
                <td class='gsc-input'>
                  <input autocomplete='off' class='gsc-input' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q' size='10' title='search' type='text'/>
                </td>
                <td class='gsc-search-button'>
                  <input class='gsc-search-button' expr:value='data:messages.search' title='search' type='submit'/>
                </td>
              </tr>
            </tbody>
          </table>
        </form>
      </div>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
                              </b:widget>
                            </b:section>
                        </nav>
                    </div>
                </div>
            </div>

            <b:if cond='data:blog.url == data:blog.homepageUrl'>

                <!-- Header -->
                <div class='container-fluid px-0' id='header-bg-1'>
                    <div class='d-flex justify-content-center' id='header-bg-2'>
                        <div class='px-0' id='bt-header'>
                            <div class='container d-flex justify-content-center justify-content-lg-end align-items-center w-100 h-100' id='header-wrapper'>
                                <b:section class='header' id='header' maxwidgets='2' name='Header' showaddelement='yes'>
                                  <b:widget id='Image98' locked='false' title='Header Background' type='Image' version='1'>
                                    <b:widget-settings>
                                      <b:widget-setting name='displayUrl'>http://3.bp.blogspot.com/-m6RHE7Xjf8I/XS4bl-87OHI/AAAAAAAABOc/hos9vOwUAjcdV5N8pAlmzBGmngL7g4iwwCK4BGAYYCw/s1600/education-header-2.png</b:widget-setting>
                                      <b:widget-setting name='displayHeight'>718</b:widget-setting>
                                      <b:widget-setting name='sectionWidth'>600</b:widget-setting>
                                      <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                                      <b:widget-setting name='displayWidth'>1600</b:widget-setting>
                                      <b:widget-setting name='link'/>
                                      <b:widget-setting name='caption'>Header Background Image. Ideal width 1600px with.</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
                                            <b:if cond='data:title != &quot;&quot;'>
                                                <h2><data:title/></h2>
                                            </b:if>
                                            <div class='widget-content'>
                                                <b:tag cond='data:link' expr:href='data:link' name='a'>
                                                    <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
                                                </b:tag>
                                                <br/>
                                                <b:if cond='data:caption'>
                                                    <span class='caption'><data:caption/></span>
                                                </b:if>
                                            </div>
                                            <b:include name='quickedit'/>
                                        </b:includable>
                                  </b:widget>
                                  <b:widget id='Header1' locked='true' title='Physics Wallahs Arena (Header)' type='Header' version='1'>
                                    <b:widget-settings>
                                      <b:widget-setting name='displayUrl'/>
                                      <b:widget-setting name='displayHeight'>0</b:widget-setting>
                                      <b:widget-setting name='sectionWidth'>-1</b:widget-setting>
                                      <b:widget-setting name='useImage'>false</b:widget-setting>
                                      <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                                      <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
                                      <b:widget-setting name='displayWidth'>0</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>

                                            <b:if cond='data:useImage'>
                                                <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
                                                    <!--
                                                    Show image as background to text. You can't really calculate the width
                                                    reliably in JS because margins are not taken into account by any of
                                                    clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
                                                    width if the user is using shrink to fit.
                                                    This results in a margin-width's worth of pixels being cropped. If the
                                                    user is not using shrink to fit then we expand the header.
                                                    -->
                                                    <b:if cond='data:mobile'>
                                                        <div id='header-inner'>
                                                            <div class='titlewrapper' style='background: transparent'>
                                                                <h1 class='title' style='background: transparent; border-width: 0px'>
                                                                    <b:include name='title'/>
                                                                </h1>
                                                            </div>
                                                            <b:include name='description'/>
                                                        </div>
                                                        <b:else/>
                                                        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
                                                            <div class='titlewrapper' style='background: transparent'>
                                                                <h1 class='title' style='background: transparent; border-width: 0px'>
                                                                    <b:include name='title'/>
                                                                </h1>
                                                            </div>
                                                            <b:include name='description'/>
                                                        </div>
                                                    </b:if>
                                                    <b:else/>
                                                    <!--Show the image only-->
                                                    <div id='header-inner'>
                                                        <a expr:href='data:blog.homepageUrl' style='display: block'>
                                                            <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
                                                        </a>
                                                        <!--Show the description-->
                                                        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
                                                            <b:include name='description'/>
                                                        </b:if>
                                                    </div>
                                                </b:if>
                                                <b:else/>
                                                <!--No header image -->
                                                <div id='header-inner'>
                                                    <div class='titlewrapper justify-content-center'>
                                                        <h1 class='title'>
                                                            <b:include name='title'/>
                                                        </h1>
                                                    </div>
                                                    <b:include name='description'/>
                                                </div>
                                            </b:if>
                                        </b:includable>
                                    <b:includable id='description'>
                                            <div class='descriptionwrapper justify-content-center'>
                                                <p class='description'><span><data:description/></span></p>
                                            </div>
                                        </b:includable>
                                    <b:includable id='title'>
                                            <b:tag cond='data:blog.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
                                                <data:title/>
                                            </b:tag>
                                        </b:includable>
                                  </b:widget>
                                </b:section>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- /Header -->


                <div class='container-fluid'>
                    <b:section class='mb-5' id='blocksMainMenu' maxwidgets='1' name='Blocks Menu' showaddelement='no'>
                      <b:widget id='LinkList63' locked='false' title='Menu based on Icons' type='LinkList' version='1'>
                        <b:widget-settings>
                          <b:widget-setting name='link-5'>#contactForm</b:widget-setting>
                          <b:widget-setting name='link-3'>#</b:widget-setting>
                          <b:widget-setting name='link-4'>#</b:widget-setting>
                          <b:widget-setting name='text-1'>Item</b:widget-setting>
                          <b:widget-setting name='text-0'>Home</b:widget-setting>
                          <b:widget-setting name='text-3'>Item</b:widget-setting>
                          <b:widget-setting name='text-2'>Item</b:widget-setting>
                          <b:widget-setting name='text-5'>Contact us</b:widget-setting>
                          <b:widget-setting name='text-4'>Item</b:widget-setting>
                          <b:widget-setting name='sorting'>NONE</b:widget-setting>
                          <b:widget-setting name='link-1'>#</b:widget-setting>
                          <b:widget-setting name='link-2'>#</b:widget-setting>
                          <b:widget-setting name='link-0'>#bt-home</b:widget-setting>
                        </b:widget-settings>
                        <b:includable id='main'>

                                <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
                                <div class='widget-content'>
                                    <ul>
                                        <b:loop values='data:links' var='link'>
                                            <li><a expr:href='data:link.target'><data:link.name/></a></li>
                                        </b:loop>
                                    </ul>
                                    <b:include name='quickedit'/>
                                </div>
                            </b:includable>
                      </b:widget>
                    </b:section>
                </div>


                <div class='container-fluid mb-5' id='bt-posts-1'>
                    <div class='container'>
                        <b:section id='CoursesList' name='Courses List'>
                          <b:widget id='HTML2' locked='false' title='BEAUTIFUL GOA BY RAWKNEETI' type='HTML'>
                            <b:widget-settings>
                              <b:widget-setting name='content'><![CDATA[<iframe frameborder="0" height="223" marginheight="0" marginwidth="0" scrolling="no" src="https://www.youtube.com/embed/CqUDRLtUbUg?autoplay=0&amp;fs=0&amp;iv_load_policy=3&amp;showinfo=0&amp;rel=0&amp;cc_load_policy=0&amp;start=0&amp;end=0&amp;origin=https://youtubeembedcode.com" type="text/html" width="296.59000000000003"><div><small><a href="https://youtubeembedcode.com/pl/">youtubeembedcode pl</a></small></div><div><small><a href="http://tr3ndygirl.com/">Ultimate web Traffic</a></small></div></iframe>]]></b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
                          </b:widget>
                          <b:widget id='HTML49' locked='false' title='BLOGS' type='HTML' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='content'>6-latest-350px-course</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <!-- only display title if it's non-empty -->
                                    <b:if cond='data:title != &quot;&quot;'>
                                        <h2 class='title'><data:title/></h2>
                                    </b:if>
                                    <div class='widget-content'>
                                        <data:content/>
                                    </div>

                                    <b:include name='quickedit'/>
                                </b:includable>
                          </b:widget>
                        </b:section>
                    </div>
                </div>


                <div class='container-fluid mb-5 parallax p-4 d-flex justify-content-center align-items-center' id='content-1'>
                    <div class='container'>
                        <b:section id='sectionsLabels' name='Labels'>
                          <b:widget id='Image91' locked='false' title='Section Background' type='Image' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='displayUrl'>http://1.bp.blogspot.com/-lkwHuh_LH58/XUY0g-ExCLI/AAAAAAAABQ0/gj5BnawRmJQFtIEGL8c2_hwpyGO-2pI4QCK4BGAYYCw/s1600/work-space-o75w.jpg</b:widget-setting>
                              <b:widget-setting name='displayHeight'>1067</b:widget-setting>
                              <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                              <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                              <b:widget-setting name='displayWidth'>1600</b:widget-setting>
                              <b:widget-setting name='link'/>
                              <b:widget-setting name='caption'>Background image. Ideal width 1600px with.</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <b:if cond='data:title != &quot;&quot;'>
                                        <h2><data:title/></h2>
                                    </b:if>
                                    <div class='widget-content'>
                                        <b:tag cond='data:link' expr:href='data:link' name='a'>
                                            <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
                                        </b:tag>
                                        <br/>
                                        <b:if cond='data:caption'>
                                            <span class='caption'><data:caption/></span>
                                        </b:if>
                                    </div>
                                    <b:include name='quickedit'/>
                                </b:includable>
                          </b:widget>
                        </b:section>
                    </div>
                </div>


                <div class='container-fluid'>
                    <div class='container'>
                        <b:section class='mb-5' id='testimonials' maxwidgets='1' name='Testimonials' showaddelement='no'/>
                    </div>
                </div>


                <div class='container-fluid mb-5 parallax p-4 d-flex justify-content-center align-items-center' id='bt-subscription'>
                    <div class='container'>
                        <b:section class='mb-5' id='emailSubscription' maxwidgets='1' name='Email subscription' showaddelement='no'>
                          <b:widget id='Image93' locked='false' title='Section Background' type='Image' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='displayUrl'>http://4.bp.blogspot.com/-7F09sOv2g94/XUo8NJcz-UI/AAAAAAAABRk/jYvyTN1EtDMob395BTsLjnMttnuPh74QwCK4BGAYYCw/s1600/library-blue.jpg</b:widget-setting>
                              <b:widget-setting name='displayHeight'>1068</b:widget-setting>
                              <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                              <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                              <b:widget-setting name='displayWidth'>1600</b:widget-setting>
                              <b:widget-setting name='link'/>
                              <b:widget-setting name='caption'>Background image. Ideal width 1600px with.</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <b:if cond='data:title != &quot;&quot;'>
                                        <h2><data:title/></h2>
                                    </b:if>
                                    <div class='widget-content'>
                                        <b:tag cond='data:link' expr:href='data:link' name='a'>
                                            <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
                                        </b:tag>
                                        <br/>
                                        <b:if cond='data:caption'>
                                            <span class='caption'><data:caption/></span>
                                        </b:if>
                                    </div>
                                    <b:include name='quickedit'/>
                                </b:includable>
                          </b:widget>
                          <b:widget id='FollowByEmail1' locked='false' title='Subscribe by Email-desc:Subscribe for Free to get all our newest blogs and content on email' type='FollowByEmail' version='1'>
                            <b:includable id='main'>
                                    <b:if cond='data:title != &quot;&quot;'><h2 class='title'><data:title/></h2></b:if>
                                    <div class='widget-content'>
                                        <div class='follow-by-email-inner'>
                                            <form action='https://feedburner.google.com/fb/a/mailverify' expr:onsubmit='&quot;window.open(\&quot;https://feedburner.google.com/fb/a/mailverify?uri=&quot; + data:feedPath + &quot;\&quot;, \&quot;popupwindow\&quot;, \&quot;scrollbars=yes,width=550,height=520\&quot;); return true&quot;' method='post' target='popupwindow'>
                                                <table width='100%'>
                                                    <tr>
                                                        <td>
                                                            <input class='follow-by-email-address' name='email' placeholder='Email address...' type='text'/>
                                                        </td>
                                                        <td width='64px'>
                                                            <input class='follow-by-email-submit' type='submit' value='Submit'/>
                                                        </td>
                                                    </tr>
                                                </table>
                                                <input expr:value='data:feedPath' name='uri' type='hidden'/>
                                                <input name='loc' type='hidden' value='en_US'/>
                                            </form>
                                        </div>
                                    </div>
                                    <span class='item-control blog-admin'>
                                        <b:include name='quickedit'/>
                                    </span>
                                </b:includable>
                          </b:widget>
                        </b:section>
                    </div>
                </div>


                <div class='container-fluid mb-5' id='bt-contact'>
                    <div class='container'>
                        <b:section id='contactForm' name='Contact form'/>
                    </div>
                </div>


                <div class='container-fluid mb-5 parallax p-4 d-flex justify-content-center align-items-center' id='bt-videos'>
                    <div class='container'>
                        <b:section id='latestVideo' name='Latest video'>
                          <b:widget id='Image89' locked='false' title='Section Background' type='Image' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='displayUrl'>http://1.bp.blogspot.com/-Ak4o42F3078/XrlABdN4FjI/AAAAAAAAJgE/1kOAqK5CeoMpTB4nEk3yKEv8wXkxI52hACK4BGAYYCw/s1600/media-learning.jpg</b:widget-setting>
                              <b:widget-setting name='displayHeight'>1065</b:widget-setting>
                              <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                              <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                              <b:widget-setting name='displayWidth'>1600</b:widget-setting>
                              <b:widget-setting name='link'/>
                              <b:widget-setting name='caption'/>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <b:if cond='data:title != &quot;&quot;'>
                                        <h2><data:title/></h2>
                                    </b:if>
                                    <div class='widget-content'>
                                        <b:tag cond='data:link' expr:href='data:link' name='a'>
                                            <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
                                        </b:tag>
                                        <br/>
                                        <b:if cond='data:caption'>
                                            <span class='caption'><data:caption/></span>
                                        </b:if>
                                    </div>
                                    <b:include name='quickedit'/>
                                </b:includable>
                          </b:widget>
                        </b:section>
                    </div>
                </div>



            </b:if>

                <div class='container-fluid'>
                    <div class='container' id='btemplates-main-content'> <!-- Content-wrapper -->

                        <b:if cond='data:blog.pageType != &quot;item&quot;'>
                            <div id='btemplates-first-post'>
                                <b:section id='ContentAfterFirstPost'>
                                  <b:widget id='HTML88' locked='false' title='Ads block' type='HTML' version='1'>
                                    <b:widget-settings>
                                      <b:widget-setting name='content'><![CDATA[<div class="d-flex justify-content-center"><img src="//3.bp.blogspot.com/-9ytRH_q5x6M/VmQXH-c5HiI/AAAAAAAAIqE/F0Flg9iHwKA/s000/728x90.jpg" alt="Banner 728x90px" width="728" height="auto" style="max-width: 100%"/></div>]]></b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
                                            <!-- only display title if it's non-empty -->
                                            <b:if cond='data:title != &quot;&quot;'>
                                                <h2 class='title'><data:title/></h2>
                                            </b:if>
                                            <div class='widget-content'>
                                                <data:content/>
                                            </div>

                                            <b:include name='quickedit'/>
                                        </b:includable>
                                  </b:widget>
                                </b:section>
                            </div>
                        </b:if>

                        <div class='row'>
                            <b:if cond='data:view.isLayoutMode  || data:blog.url != data:blog.homepageUrl'>

                            <div class='col-lg-9' id='content-wrapper'>
                                <!-- Main content -->
                                <div id='main-wrapper'>


                                    <b:if cond='data:blog.pageType == &quot;error_page&quot;'>
                                        <style type='text/css'>
                                            .status-msg-wrap {display: none;}
                                        </style>
                                        <div class='text-center' id='btemplates-404'>
                                            <h4>Error 404<br/>Not Found</h4>
                                            <img alt='Error 404' src='https://1.bp.blogspot.com/-W_8l-L7BARo/Xs0wlcD8GcI/AAAAAAAAJhQ/H5ztSXUAVYIKy2cEynjAOMd1M9qicizcgCLcBGAsYHQ/s1600/404.png'/>
                                            <p>Sorry! The content you were looking for does not exist or changed its url.</p>
                                            <p>Please check if the url is written correctly or try using our search form.</p>
                                        </div>
                                    </b:if>


                                    <b:section class='main' id='main' name='Main' showaddelement='no'>
                                      <b:widget id='Blog1' locked='true' title='Blog posts' type='Blog' version='1'>
                                        <b:widget-settings>
                                          <b:widget-setting name='showDateHeader'>true</b:widget-setting>
                                          <b:widget-setting name='style.textcolor'>#212529</b:widget-setting>
                                          <b:widget-setting name='showShareButtons'>true</b:widget-setting>
                                          <b:widget-setting name='authorLabel'>By</b:widget-setting>
                                          <b:widget-setting name='showCommentLink'>true</b:widget-setting>
                                          <b:widget-setting name='style.urlcolor'>#212529</b:widget-setting>
                                          <b:widget-setting name='showAuthor'>true</b:widget-setting>
                                          <b:widget-setting name='disableGooglePlusShare'>true</b:widget-setting>
                                          <b:widget-setting name='style.linkcolor'>#343a40</b:widget-setting>
                                          <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                                          <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                                          <b:widget-setting name='timestampLabel'>-</b:widget-setting>
                                          <b:widget-setting name='reactionsLabel'/>
                                          <b:widget-setting name='showAuthorProfile'>true</b:widget-setting>
                                          <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                                          <b:widget-setting name='showLabels'>true</b:widget-setting>
                                          <b:widget-setting name='showLocation'>false</b:widget-setting>
                                          <b:widget-setting name='showTimestamp'>true</b:widget-setting>
                                          <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                                          <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                                          <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                                          <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                                          <b:widget-setting name='showReactions'>false</b:widget-setting>
                                        </b:widget-settings>
                                        <b:includable id='main' var='top'>
                                                <b:if cond='!data:mobile'>
                                                    <!-- posts -->
                                                    <div class='blog-posts hfeed'>

                                                        <b:include data='top' name='status-message'/>

                                                        <b:loop values='data:posts' var='post'>
                                                            <b:if cond='data:post.isDateStart and not data:post.isFirstPost'>
                                                                &lt;/div&gt;&lt;/div&gt;
                                                            </b:if>
                                                            <b:if cond='data:post.isDateStart'>
                                                                &lt;div class=&quot;date-outer&quot;&gt;
                                                            </b:if>
                                                            <b:if cond='data:post.dateHeader'>
                                                                <!--<h2 class='date-header'><span><data:post.dateHeader/></span></h2>-->
                                                            </b:if>
                                                            <b:if cond='data:post.isDateStart'>
                                                                &lt;div class=&quot;date-posts&quot;&gt;
                                                            </b:if>
                                                            <div class='post-outer'>
                                                                <b:include data='post' name='post'/>
                                                                <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
                                                            </div>

                                                            <!-- Ad -->
                                                            <b:if cond='data:post.includeAd'>
                                                                <div class='inline-ad'>
                                                                    <data:adCode/>
                                                                </div>
                                                            </b:if>
                                                        </b:loop>
                                                        <b:if cond='data:numPosts != 0'>
                                                            &lt;/div&gt;&lt;/div&gt;
                                                        </b:if>
                                                    </div>

                                                    <!-- navigation -->
                                                    <b:include name='nextprev'/>

                                                    <b:else/>
                                                    <b:include name='mobile-main'/>
                                                </b:if>

                                                <b:include cond='data:top.showPlusOne' name='googlePlusBootstrap'/>
                                            </b:includable>
                                        <b:includable id='backlinkDeleteIcon' var='backlink'>
                                                <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
                                                    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
                                                        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
                                                    </a>
                                                </span>
                                            </b:includable>
                                        <b:includable id='backlinks' var='post'>
                                                <a name='links'/><h4><data:post.backlinksLabel/></h4>
                                                <b:if cond='data:post.numBacklinks != 0'>
                                                    <dl class='comments-block' id='comments-block'>
                                                        <b:loop values='data:post.backlinks' var='backlink'>
                                                            <div class='collapsed-backlink backlink-control'>
                                                                <dt class='comment-title'>
                                                                    <span class='backlink-toggle-zippy'>&#160;</span>
                                                                    <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
                                                                    <b:include data='backlink' name='backlinkDeleteIcon'/>
                                                                </dt>
                                                                <dd class='comment-body collapseable'>
                                                                    <data:backlink.snippet/>
                                                                </dd>
                                                                <dd class='comment-footer collapseable'>
                                                                    <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
                                                                    <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
                                                                </dd>
                                                            </div>
                                                        </b:loop>
                                                    </dl>
                                                </b:if>
                                                <p class='comment-footer'>
                                                    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
                                                </p>
                                            </b:includable>
                                        <b:includable id='btemplates-breadcrumbs' var='post'>
                                                <b:if cond='data:blog.pageType == &quot;item&quot;'>
                                                    <nav aria-label='breadcrumb' role='navigation'>
                                                        <ol class='breadcrumb'>
                                                            <li aria-current='page' class='breadcrumb-item'>
                                                                <a expr:href='data:blog.homepageUrl' rel='tag'><data:messages.home/></a>
                                                            </li>
                                                            <b:if cond='data:post.labels'>
                                                                <li aria-current='page' class='breadcrumb-item'>
                                                                    <a class='b-label' expr:href='data:post.labels.first.url'>
                                                                        <data:post.labels.first.name/>
                                                                    </a>
                                                                </li>
                                                            </b:if>
                                                            <li aria-current='page' class='breadcrumb-item active'>
                                                                <data:post.title/>
                                                            </li>
                                                        </ol>
                                                    </nav>
                                                </b:if>
                                            </b:includable>
                                        <b:includable id='btemplates-post-content' var='post'>
                                                <b:if cond='data:post.body'>
                                                    <b:if cond='data:blog.pageType == &quot;item&quot; || data:blog.pageType == &quot;static_page&quot;'>
                                                        <!-- Then use the post body as the schema.org description, for good G+/FB snippeting. -->
                                                        <div class='post-body entry-content mb-4 pb-4' expr:id='&quot;post-body-&quot; + data:post.id' expr:itemprop='(data:blog.metaDescription ? &quot;&quot; : &quot;description &quot;) + &quot;articleBody&quot;'>
                                                            <data:post.body/>
                                                            <div style='clear: both;'/> <!-- clear for photos floats -->
                                                        </div>
                                                        <b:else/>
                                                        <b:if cond='data:post.firstImageUrl'>
                                                            <div class='post-thumb mb-4 text-center'>
                                                                <a expr:href='data:post.link ? data:post.link : data:post.url'>
                                                                    <img expr:alt='data:post.title' expr:src='data:post.firstImageUrl resizeImage 850' expr:srcset='sourceSet(data:post.firstImageUrl, [200,400,600,800])'/>
                                                                </a>
                                                            </div>
                                                        </b:if>
                                                        <div class='post-summary entry-content mb-4 pb-4 border-bottom' expr:id='&quot;post-body-&quot; + data:post.id' expr:itemprop='(data:blog.metaDescription ? &quot;&quot; : &quot;description &quot;) + &quot;articleBody&quot;'>
                                                            <b:eval expr='snippet(data:post.longSnippet, {length: 160, links: true, linebreaks: false})'/>
                                                            <div style='clear: both;'/> <!-- clear for photos floats -->
                                                            <b:if cond='data:post.longSnippet != &quot;&quot;'>
                                                                <a class='read-more float-right' expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'><data:post.jumpText/></a>
                                                            </b:if>
                                                            <div style='clear: both;'/>
                                                        </div>
                                                    </b:if>
                                                </b:if>
                                            </b:includable>
                                        <b:includable id='btemplates-seo-title' var='post'>
                                                <b:if cond='data:post.title'>
                                                    <b:if cond='data:blog.pageType == &quot;item&quot;'>
                                                        <h1 class='post-title entry-title text-center' itemprop='name'>
                                                            <data:post.title/>
                                                        </h1>
                                                        <b:else/>
                                                        <h2 class='post-title entry-title text-center' itemprop='name'>
                                                            <a expr:href='data:post.link ? data:post.link : data:post.url'><data:post.title/></a>
                                                        </h2>
                                                    </b:if>
                                                </b:if>
                                            </b:includable>
                                        <b:includable id='comment-form' var='post'>
                                                <div class='comment-form'>
                                                    <a name='comment-form'/>
                                                    <b:if cond='data:mobile'>
                                                        <h4 id='comment-post-message'>
                                                            <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
                                                        <p><data:blogCommentMessage/></p>
                                                        <data:blogTeamBlogMessage/>
                                                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                                                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                                                        <b:else/>
                                                        <h4 id='comment-post-message'><data:postCommentMsg/></h4>
                                                        <p><data:blogCommentMessage/></p>
                                                        <data:blogTeamBlogMessage/>
                                                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                                                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
                                                    </b:if>
                                                    <data:post.cmtfpIframe/>
                                                    <script type='text/javascript'>
                                                        BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
                                                    </script>
                                                </div>
                                            </b:includable>
                                        <b:includable id='commentDeleteIcon' var='comment'>
                                                <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
                                                    <b:if cond='data:showCmtPopup'>
                                                        <div class='goog-toggle-button'>
                                                            <div class='goog-inline-block comment-action-icon'/>
                                                        </div>
                                                        <b:else/>
                                                        <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
                                                            <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
                                                        </a>
                                                    </b:if>
                                                </span>
                                            </b:includable>
                                        <b:includable id='comment_count_picker' var='post'>
                                                <b:if cond='data:post.commentSource == 1'>
                                                    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.url.canonical.http'>
                                                    </span>
                                                    <b:else/>
                                                    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                                                        <i aria-hidden='true' class='fa fa-comment-o fa-flip-horizontal'/> <data:post.commentLabelFull/>.
                                                    </a>
                                                </b:if>
                                            </b:includable>
                                        <b:includable id='comment_picker' var='post'>
                                                <b:if cond='data:post.commentSource == 1'>
                                                    <b:include data='post' name='iframe_comments'/>
                                                    <b:elseif cond='data:post.showThreadedComments'/>
                                                    <b:include data='post' name='threaded_comments'/>
                                                    <b:else/>
                                                    <b:include data='post' name='comments'/>
                                                </b:if>
                                            </b:includable>
                                        <b:includable id='comments' var='post'>
                                                <div class='comments' id='comments'>
                                                    <a name='comments'/>
                                                    <b:if cond='data:post.allowComments'>
                                                        <h4><data:post.commentLabelFull/>:</h4>

                                                        <b:if cond='data:post.commentPagingRequired'>
                                                            <span class='paging-control-container'>
                                                                <b:if cond='data:post.hasOlderLinks'>
                                                                    <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
                                                                    &#160;
                                                                    <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
                                                                    &#160;
                                                                </b:if>

                                                                <data:post.commentRangeText/>

                                                                <b:if cond='data:post.hasNewerLinks'>
                                                                    &#160;
                                                                    <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
                                                                    &#160;
                                                                    <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
                                                                </b:if>
                                                            </span>
                                                        </b:if>

                                                        <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
                                                            <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
                                                                <b:loop values='data:post.comments' var='comment'>
                                                                    <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
                                                                        <b:if cond='data:comment.favicon'>
                                                                            <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
                                                                        </b:if>
                                                                        <a expr:name='data:comment.anchorName'/>
                                                                        <b:if cond='data:blog.enabledCommentProfileImages'>
                                                                            <data:comment.authorAvatarImage/>
                                                                        </b:if>
                                                                        <b:if cond='data:comment.authorUrl'>
                                                                            <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
                                                                            <b:else/>
                                                                            <data:comment.author/>
                                                                        </b:if>
                                                                        <data:commentPostedByMsg/>
                                                                    </dt>
                                                                    <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
                                                                        <b:if cond='data:comment.isDeleted'>
                                                                            <span class='deleted-comment'><data:comment.body/></span>
                                                                            <b:else/>
                                                                            <p>
                                                                                <data:comment.body/>
                                                                            </p>
                                                                        </b:if>
                                                                    </dd>
                                                                    <dd class='comment-footer'>
                                                                        <span class='comment-timestamp'>
                                                                            <a expr:href='data:comment.url' title='comment permalink'>
                                                                                <data:comment.timestamp/>
                                                                            </a>
                                                                            <b:include data='comment' name='commentDeleteIcon'/>
                                                                        </span>
                                                                    </dd>
                                                                </b:loop>
                                                            </dl>
                                                        </div>

                                                        <b:if cond='data:post.commentPagingRequired'>
                                                            <span class='paging-control-container'>
                                                                <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                                                                    <data:post.oldestLinkText/>
                                                                </a>
                                                                <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                                                                    <data:post.olderLinkText/>
                                                                </a>
                                                                &#160;
                                                                <data:post.commentRangeText/>
                                                                &#160;
                                                                <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                                                                    <data:post.newerLinkText/>
                                                                </a>
                                                                <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                                                                    <data:post.newestLinkText/>
                                                                </a>
                                                            </span>
                                                        </b:if>

                                                        <p class='comment-footer'>
                                                            <b:if cond='data:post.embedCommentForm'>
                                                                <b:if cond='data:post.allowNewComments'>
                                                                    <b:include data='post' name='comment-form'/>
                                                                    <b:else/>
                                                                    <data:post.noNewCommentsText/>
                                                                </b:if>
                                                                <b:elseif cond='data:post.allowComments'/>
                                                                <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
                                                            </b:if>
                                                        </p>
                                                    </b:if>
                                                    <b:if cond='data:showCmtPopup'>
                                                        <div id='comment-popup'>
                                                            <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                                                            </iframe>
                                                        </div>
                                                    </b:if>

                                                    <div id='backlinks-container'>
                                                        <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                                                            <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
                                                        </div>
                                                    </div>
                                                </div>
                                            </b:includable>
                                        <b:includable id='feedLinks'>
                                                <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
                                                    <b:if cond='data:feedLinks'>
                                                        <div class='blog-feeds'>
                                                            <b:include data='feedLinks' name='feedLinksBody'/>
                                                        </div>
                                                    </b:if>

                                                    <b:else/> <!--Post feed links -->
                                                    <div class='post-feeds'>
                                                        <b:loop values='data:posts' var='post'>
                                                            <b:include cond='data:post.allowComments and data:post.feedLinks' data='post.feedLinks' name='feedLinksBody'/>
                                                        </b:loop>
                                                    </div>
                                                </b:if>
                                            </b:includable>
                                        <b:includable id='feedLinksBody' var='links'>
                                                <div class='feed-links'>
                                                    <data:feedLinksMsg/>
                                                    <b:loop values='data:links' var='f'>
                                                        <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
                                                    </b:loop>
                                                </div>
                                            </b:includable>
                                        <b:includable id='iframe_comments' var='post'>

                                                <b:if cond='data:post.allowIframeComments'>
                                                    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
                                                    <div class='cmt_iframe_holder' expr:data-href='data:post.url.canonical' expr:data-viewtype='data:post.viewType'/>

                                                    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
                                                        <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
                                                    </b:if>
                                                </b:if>
                                            </b:includable>
                                        <b:includable id='mobile-index-post' var='post'>
                                                <div class='mobile-date-outer date-outer'>
                                                    <b:if cond='data:post.dateHeader'>
                                                        <div class='date-header'>
                                                            <span><data:post.dateHeader/></span>
                                                        </div>
                                                    </b:if>

                                                    <div class='mobile-post-outer'>
                                                        <a expr:href='data:post.url'>
                                                            <h3 class='mobile-index-title entry-title' itemprop='name'>
                                                                <data:post.title/>
                                                            </h3>

                                                            <div class='mobile-index-arrow'>&amp;rsaquo;</div>

                                                            <div class='mobile-index-contents'>
                                                                <b:if cond='data:post.thumbnailUrl'>
                                                                    <div class='mobile-index-thumbnail'>
                                                                        <div class='Image'>
                                                                            <img expr:src='data:post.thumbnailUrl'/>
                                                                        </div>
                                                                    </div>
                                                                </b:if>

                                                                <div class='post-body'>
                                                                    <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
                                                                </div>
                                                            </div>

                                                            <div style='clear: both;'/>
                                                        </a>

                                                        <div class='mobile-index-comment'>
                                                            <b:include cond='data:blog.pageType != &quot;static_page&quot;                          and data:post.allowComments                          and data:post.numComments != 0' data='post' name='comment_count_picker'/>
                                                        </div>
                                                    </div>
                                                </div>
                                            </b:includable>
                                        <b:includable id='mobile-main' var='top'>
                                                <!-- posts -->
                                                <div class='blog-posts hfeed'>

                                                    <b:include data='top' name='status-message'/>

                                                    <b:if cond='data:blog.pageType == &quot;index&quot;'>
                                                        <b:loop values='data:posts' var='post'>
                                                            <b:include data='post' name='mobile-index-post'/>
                                                        </b:loop>
                                                        <b:else/>
                                                        <b:loop values='data:posts' var='post'>
                                                            <b:include data='post' name='mobile-post'/>
                                                        </b:loop>
                                                    </b:if>
                                                </div>

                                                <b:include name='mobile-nextprev'/>
                                            </b:includable>
                                        <b:includable id='mobile-nextprev'>
                                                <div class='blog-pager' id='blog-pager'>
                                                    <b:if cond='data:newerPageUrl'>
                                                        <div class='mobile-link-button' id='blog-pager-newer-link'>
                                                            <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
                                                        </div>
                                                    </b:if>

                                                    <b:if cond='data:olderPageUrl'>
                                                        <div class='mobile-link-button' id='blog-pager-older-link'>
                                                            <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
                                                        </div>
                                                    </b:if>

                                                    <div class='mobile-link-button' id='blog-pager-home-link'>
                                                        <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
                                                    </div>

                                                    <div class='mobile-desktop-link'>
                                                        <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
                                                    </div>

                                                </div>
                                                <div class='clear'/>
                                            </b:includable>
                                        <b:includable id='mobile-post' var='post'>
                                                <div class='date-outer'>
                                                    <b:if cond='data:post.dateHeader'>
                                                        <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
                                                    </b:if>
                                                    <div class='date-posts'>
                                                        <div class='post-outer'>

                                                            <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
                                                                <b:if cond='data:post.thumbnailUrl'>
                                                                    <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
                                                                </b:if>
                                                                <meta expr:content='data:blog.blogId' itemprop='blogId'/>
                                                                <meta expr:content='data:post.id' itemprop='postId'/>

                                                                <a expr:name='data:post.id'/>
                                                                <b:if cond='data:post.title'>
                                                                    <h3 class='post-title entry-title' itemprop='name'>
                                                                        <b:if cond='data:post.link'>
                                                                            <a expr:href='data:post.link'><data:post.title/></a>
                                                                            <b:elseif cond='data:post.url and data:blog.url != data:post.url'/>
                                                                            <a expr:href='data:post.url'><data:post.title/></a>
                                                                            <b:else/>
                                                                            <data:post.title/>
                                                                        </b:if>
                                                                    </h3>
                                                                </b:if>

                                                                <div class='post-header'>
                                                                    <div class='post-header-line-1'/>
                                                                </div>

                                                                <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
                                                                    <data:post.body/>
                                                                    <div style='clear: both;'/> <!-- clear for photos floats -->
                                                                </div>

                                                                <div class='post-footer'>
                                                                    <div class='post-footer-line post-footer-line-1'>
                                                                        <span class='post-author vcard'>
                                                                            <b:if cond='data:top.showAuthor'>
                                                                                <b:if cond='data:post.authorProfileUrl'>
                                                                                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                                                                        <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                                                                                        <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                                                                            <span itemprop='name'><data:post.author/></span>
                                                                                        </a>
                                                                                    </span>
                                                                                    <b:else/>
                                                                                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                                                                        <span itemprop='name'><data:post.author/></span>
                                                                                    </span>
                                                                                </b:if>
                                                                            </b:if>
                                                                        </span>

                                                                        <span class='post-timestamp'>
                                                                            <b:if cond='data:top.showTimestamp'>
                                                                                <data:top.timestampLabel/>
                                                                                <b:if cond='data:post.url'>
                                                                                    <meta expr:content='data:post.url.canonical' itemprop='url'/>
                                                                                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                                                                                </b:if>
                                                                            </b:if>
                                                                        </span>

                                                                        <span class='post-comment-link'>
                                                                            <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                                  and data:post.allowComments' data='post' name='comment_count_picker'/>
                                                                        </span>
                                                                    </div>

                                                                    <div class='post-footer-line post-footer-line-2'>
                                                                        <b:if cond='data:top.showMobileShare'>
                                                                            <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                                                                                <a href='javascript:void(0);'><data:shareMsg/></a>
                                                                            </div>
                                                                        </b:if>
                                                                        <b:if cond='data:top.showDummy'>
                                                                            <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
                                                                        </b:if>
                                                                    </div>

                                                                </div>
                                                            </div>

                                                            <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
                                                        </div>
                                                    </div>
                                                </div>
                                            </b:includable>
                                        <b:includable id='nextprev'>
                                                <div class='blog-pager' id='blog-pager'>
                                                    <b:if cond='data:newerPageUrl'>
                                                        <span id='blog-pager-newer-link'>
                                                            <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
                                                        </span>
                                                    </b:if>

                                                    <b:if cond='data:olderPageUrl'>
                                                        <span id='blog-pager-older-link'>
                                                            <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
                                                        </span>
                                                    </b:if>

                                                    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

                                                    <b:if cond='data:mobileLinkUrl'>
                                                        <div class='blog-mobile-link'>
                                                            <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
                                                        </div>
                                                    </b:if>

                                                </div>
                                                <div class='clear'/>
                                            </b:includable>
                                        <b:includable id='post' var='post'>
                                                <div class='post hentry uncustomized-post-template mb-5' itemprop='blogPost' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
                                                    <b:if cond='data:post.firstImageUrl'>
                                                        <meta expr:content='data:post.firstImageUrl' itemprop='image_url'/>
                                                    </b:if>
                                                    <meta expr:content='data:blog.blogId' itemprop='blogId'/>
                                                    <meta expr:content='data:post.id' itemprop='postId'/>
                                                    <b:include cond='data:view.isPost' data='post' name='btemplates-breadcrumbs'/>
                                                    <a expr:name='data:post.id'/>
                                                    <b:include data='post' name='btemplates-seo-title'/>

                                                    <hr class='title-separator mb-4'/>

                                                    <div class='post-header mb-4'>
                                                        <div class='post-header-line-1 text-center mb-4'>
                                                            <span class='post-author vcard'>
                                                                <b:if cond='data:top.showAuthor'>
                                                                    <span class='rounded-circle border border-secondary text-center'>
                                                                        <i aria-hidden='true' class='fa fa-user-o'/>
                                                                    </span>
                                                                    <data:top.authorLabel/>
                                                                    <b:if cond='data:post.authorProfileUrl'>
                                                                        <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                                                            <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                                                                            <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                                                                                <span itemprop='name'><data:post.author/></span>
                                                                            </a>
                                                                        </span>
                                                                        <b:else/>
                                                                        <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                                                            <span itemprop='name'><data:post.author/></span>
                                                                        </span>
                                                                    </b:if>
                                                                </b:if>
                                                            </span>
                                                            <span class='post-labels'>
                                                                <span class='rounded-circle border border-secondary text-center'>
                                                                    <i aria-hidden='true' class='fa fa-bookmark-o'/>
                                                                </span>
                                                                <b:if cond='data:top.showPostLabels and data:post.labels'>
                                                                    <!--<data:postLabelsLabel/>-->
                                                                    <b:loop values='data:post.labels' var='label'>
                                                                        <a expr:href='data:label.url' rel='tag'>
                                                                            <data:label.name/>
                                                                        </a>
                                                                        <b:if cond='not data:label.isLast'> &amp;middot; </b:if>
                                                                    </b:loop>
                                                                </b:if>
                                                            </span>
                                                        </div>
                                                    </div>

                                                    <b:include data='post' name='btemplates-post-content'/>

                                                    <div class='container mb-4'>
                                                        <div class='post-footer text-center'>
                                                            <div class='post-footer-line post-footer-line-1'>

                                                                <!-- share buttons -->
                                                                <b:if cond='data:post.sharePostUrl'>
                                                                    <div class='bt-post-share-buttons'>
                                                                        <b:if cond='data:top.showEmailButton'>
                                                                            <a class='' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'>
                                                                                <i aria-hidden='true' class='fa fa-envelope-open-o'/>
                                                                            </a>
                                                                        </b:if>
                                                                        <b:if cond='data:top.showTwitterButton'>
                                                                            <a class='' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'>
                                                                                <i aria-hidden='true' class='fa fa-twitter'/>
                                                                            </a>
                                                                        </b:if>
                                                                        <b:if cond='data:top.showFacebookButton'>
                                                                            <a class='' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'>
                                                                                <i aria-hidden='true' class='fa fa-facebook'/>
                                                                            </a>
                                                                        </b:if>
                                                                        <b:if cond='data:top.showPinterestButton'>
                                                                            <a class='' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'>
                                                                                <i aria-hidden='true' class='fa fa-pinterest-p'/>
                                                                            </a>
                                                                        </b:if>
                                                                        <a class='' expr:href='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title + &quot;: &quot; + data:post.url' target='_blank'>
                                                                            <i aria-hidden='true' class='fa fa-whatsapp'/>
                                                                        </a>
                                                                    </div>
                                                                </b:if>
                                                            </div>

                                                            <div class='post-footer-line post-footer-line-2'>

                                                                <span class='post-timestamp'>
                                                                    <b:if cond='data:top.showTimestamp'>
                                                                        <!--data:top.timestampLabel/-->
                                                                        <b:if cond='data:post.url'>
                                                                            <meta expr:content='data:post.url.canonical' itemprop='url'/>
                                                                            <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                                                                        </b:if>
                                                                    </b:if>
                                                                </span>

                                                                <span class='reaction-buttons'>
                                                                    <b:if cond='data:top.showReactions'>
                                                                        <table border='0' cellpadding='0' cellspacing='0' width='100%'><tr>
                                                                            <td class='reactions-label-cell' nowrap='nowrap' valign='top' width='1%'>
                                                                                <span class='reactions-label'>
                                                                                    <data:top.reactionsLabel/></span>&#160;</td>
                                                                            <td><iframe allowtransparency='true' class='reactions-iframe' expr:src='data:post.reactionsUrl' frameborder='0' name='reactions' scrolling='no'/></td>
                                                                        </tr></table>
                                                                    </b:if>
                                                                </span>



                                                                <!-- backlinks -->
                                                                <span class='post-backlinks post-comment-link'>
                                                                    <b:if cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                      and data:post.showBacklinks'>
                                                                        <a class='comment-link' expr:href='data:post.url + &quot;#links&quot;'><data:top.backlinkLabel/></a>
                                                                    </b:if>
                                                                </span>

                                                                <span class='post-icons'>
                                                                    <!-- email post links -->
                                                                    <b:if cond='data:post.emailPostUrl'>
                                                                        <span class='item-action'>
                                                                            <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
                                                                                <img alt='' class='icon-action' height='13' src='https://resources.blogblog.com/img/icon18_email.gif' width='18'/>
                                                                            </a>
                                                                        </span>
                                                                    </b:if>

                                                                    <!-- quickedit pencil -->
                                                                    <b:include data='post' name='postQuickEdit'/>
                                                                </span>

                                                            </div>

                                                            <div class='post-footer-line post-footer-line-3'>
                                                                <span class='post-comment-link'>
                                                                    <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;} and data:post.allowComments' data='post' name='comment_count_picker'/>
                                                                </span>
                                                                <span class='post-location'>
                                                                    <b:if cond='data:top.showLocation and data:post.location'>
                                                                        <data:postLocationLabel/>
                                                                        <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
                                                                    </b:if>
                                                                </span>
                                                            </div>

                                                        </div>
                                                    </div>
                                                    <b:if cond='data:blog.pageType == &quot;item&quot;'>
                                                        <b:if cond='data:post.authorAboutMe'>
                                                            <div class='container' id='btemplates-author-box'>
                                                                <div class='row'>
                                                                    <div class='author-profile col-12' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                                                                        <b:if cond='data:post.authorPhoto.url'>
                                                                            <img class='rounded-circle' expr:src='data:post.authorPhoto.url resizeImage 150' itemprop='image'/>
                                                                        </b:if>
                                                                        <div>
                                                                            <a class='g-profile' expr:href='data:post.authorProfileUrl' itemprop='url' rel='author' title='author profile'>
                                                                                <span itemprop='name'><data:post.author/></span>
                                                                            </a>
                                                                        </div>
                                                                        <span itemprop='description'><data:post.authorAboutMe/></span>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </b:if>

                                                    </b:if>
                                                </div>
                                            </b:includable>
                                        <b:includable id='postQuickEdit' var='post'>
                                                <b:if cond='data:post.editUrl'>
                                                    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
                                                        <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
                                                            <img alt='' class='icon-action' height='18' src='https://resources.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
                                                        </a>
                                                    </span>
                                                </b:if>
                                            </b:includable>
                                        <b:includable id='shareButtons' var='post'>
                                                <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showPinterestButton'><a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a></b:if><b:if cond='data:top.showPlusOne'><div class='goog-inline-block google-plus-share-container'><data:post.googlePlusShareTag/></div></b:if>
                                            </b:includable>
                                        <b:includable id='status-message'>
                                                <b:if cond='data:navMessage'>
                                                    <div class='status-msg-wrap'>
                                                        <div class='status-msg-body'>
                                                            <data:navMessage/>
                                                        </div>
                                                        <div class='status-msg-border'>
                                                            <div class='status-msg-bg'>
                                                                <div class='status-msg-hidden'><data:navMessage/></div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div style='clear: both;'/>
                                                </b:if>
                                            </b:includable>
                                        <b:includable id='threaded-comment-form' var='post'>
                                                <div class='comment-form'>
                                                    <a name='comment-form'/>
                                                    <b:if cond='data:mobile'>
                                                        <p><data:blogCommentMessage/></p>
                                                        <data:blogTeamBlogMessage/>
                                                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                                                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                                                        <b:else/>
                                                        <p><data:blogCommentMessage/></p>
                                                        <data:blogTeamBlogMessage/>
                                                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                                                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
                                                    </b:if>
                                                    <data:post.cmtfpIframe/>
                                                    <script type='text/javascript'>
                                                        BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
                                                    </script>
                                                </div>
                                            </b:includable>
                                        <b:includable id='threaded_comment_js' var='post'>
                                                <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

                                                <script type='text/javascript'>
                                                    (function() {
                                                    var items = <data:post.commentJso/>;
                                                    var msgs = <data:post.commentMsgs/>;
                                                    var config = <data:post.commentConfig/>;

                                                    // <![CDATA[
          var cursor = null;
          if (items && items.length > 0) {
            cursor = parseInt(items[items.length - 1].timestamp) + 1;
          }

          var bodyFromEntry = function(entry) {
            var text = (entry &&
                        ((entry.content && entry.content.$t) ||
                         (entry.summary && entry.summary.$t))) ||
                '';
            if (entry && entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
                  return '<span class="deleted-comment">' + text + '</span>';
                }
              }
            }
            return text;
          }

          var parse = function(data) {
            cursor = null;
            var comments = [];
            if (data && data.feed && data.feed.entry) {
              for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
                var comment = {};
                // comment ID, parsed out of the original id format
                var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
                comment.id = id ? id[2] : null;
                comment.body = bodyFromEntry(entry);
                comment.timestamp = Date.parse(entry.published.$t) + '';
                if (entry.author && entry.author.constructor === Array) {
                  var auth = entry.author[0];
                  if (auth) {
                    comment.author = {
                      name: (auth.name ? auth.name.$t : undefined),
                      profileUrl: (auth.uri ? auth.uri.$t : undefined),
                      avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                    };
                  }
                }
                if (entry.link) {
                  if (entry.link[2]) {
                    comment.link = comment.permalink = entry.link[2].href;
                  }
                  if (entry.link[3]) {
                    var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                    if (pid && pid[1]) {
                      comment.parentId = pid[1];
                    }
                  }
                }
                comment.deleteclass = 'item-control blog-admin';
                if (entry.gd$extendedProperty) {
                  for (var k in entry.gd$extendedProperty) {
                    if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                      comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                    } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                      comment.displayTime = entry.gd$extendedProperty[k].value;
                    }
                  }
                }
                comments.push(comment);
              }
            }
            return comments;
          };

          var paginator = function(callback) {
            if (hasMore()) {
              var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
              if (cursor) {
                url += '&published-min=' + new Date(cursor).toISOString();
              }
              window.bloggercomments = function(data) {
                var parsed = parse(data);
                cursor = parsed.length < 50 ? null
                    : parseInt(parsed[parsed.length - 1].timestamp) + 1
                callback(parsed);
                window.bloggercomments = null;
              }
              url += '&callback=bloggercomments';
              var script = document.createElement('script');
              script.type = 'text/javascript';
              script.src = url;
              document.getElementsByTagName('head')[0].appendChild(script);
            }
          };
          var hasMore = function() {
            return !!cursor;
          };
          var getMeta = function(key, comment) {
            if ('iswriter' == key) {
              var matches = !!comment.author
                  && comment.author.name == config.authorName
                  && comment.author.profileUrl == config.authorUrl;
              return matches ? 'true' : '';
            } else if ('deletelink' == key) {
              return config.baseUri + '/delete-comment.g?blogID='
                   + config.blogId + '&postID=' + comment.id;
            } else if ('deleteclass' == key) {
              return comment.deleteclass;
            }
            return '';
          };

          var replybox = null;
          var replyUrlParts = null;
          var replyParent = undefined;

          var onReply = function(commentId, domId) {
            if (replybox == null) {
              // lazily cache replybox, and adjust to suit this style:
              replybox = document.getElementById('comment-editor');
              if (replybox != null) {
                replybox.height = '250px';
                replybox.style.display = 'block';
                replyUrlParts = replybox.src.split('#');
              }
            }
            if (replybox && (commentId !== replyParent)) {
              replybox.src = '';
              document.getElementById(domId).insertBefore(replybox, null);
              replybox.src = replyUrlParts[0]
                  + (commentId ? '&parentID=' + commentId : '')
                  + '#' + replyUrlParts[1];
              replyParent = commentId;
            }
          };

          var hash = (window.location.hash || '#').substring(1);
          var startThread, targetComment;
          if (/^comment-form_/.test(hash)) {
            startThread = hash.substring('comment-form_'.length);
          } else if (/^c[0-9]+$/.test(hash)) {
            targetComment = hash.substring(1);
          }

          // Configure commenting API:
          var configJso = {
            'maxDepth': config.maxThreadDepth
          };
          var provider = {
            'id': config.postId,
            'data': items,
            'loadNext': paginator,
            'hasMore': hasMore,
            'getMeta': getMeta,
            'onReply': onReply,
            'rendered': true,
            'initComment': targetComment,
            'initReplyThread': startThread,
            'config': configJso,
            'messages': msgs
          };

          var render = function() {
            if (window.goog && window.goog.comments) {
              var holder = document.getElementById('comment-holder');
              window.goog.comments.render(holder, provider);
            }
          };

          // render now, or queue to render when library loads:
          if (window.goog && window.goog.comments) {
            render();
          } else {
            window.goog = window.goog || {};
            window.goog.comments = window.goog.comments || {};
            window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
            window.goog.comments.loadQueue.push(render);
          }
        })();
    // ]]>
                                                </script>
                                            </b:includable>
                                        <b:includable id='threaded_comments' var='post'>
                                                <div class='comments' id='comments'>
                                                    <a name='comments'/>
                                                    <h4><data:post.commentLabelFull/>:</h4>

                                                    <div class='comments-content'>
                                                        <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
                                                        <div id='comment-holder'>
                                                            <data:post.commentHtml/>
                                                        </div>
                                                    </div>

                                                    <p class='comment-footer'>
                                                        <b:if cond='data:post.allowNewComments'>
                                                            <b:include data='post' name='threaded-comment-form'/>
                                                            <b:else/>
                                                            <data:post.noNewCommentsText/>
                                                        </b:if>
                                                    </p>

                                                    <b:if cond='data:showCmtPopup'>
                                                        <div id='comment-popup'>
                                                            <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                                                            </iframe>
                                                        </div>
                                                    </b:if>

                                                    <div id='backlinks-container'>
                                                        <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                                                            <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
                                                        </div>
                                                    </div>
                                                </div>
                                            </b:includable>
                                      </b:widget>
                                    </b:section>

                                </div>
                                <!-- /Main content -->
                            </div>

                            <div class='col-lg-3' id='sidebar-wrapper'>
                                <b:section class='sidebar' id='sidebar' name='Sidebar' preferred='yes'>
                                  <b:widget id='BlogSearch43' locked='false' title='SEARCH' type='BlogSearch' version='1'>
                                    <b:includable id='main'>
                                            <!-- only display title if it's non-empty -->
                                            <b:if cond='data:title != &quot;&quot;'>
                                                <h2 class='title'><data:title/></h2>
                                            </b:if>

                                            <div class='widget-content'>
                                                <div expr:id='data:widget.instanceId + &quot;_form&quot;'>
                                                    <form class='gsc-search-box' expr:action='data:blog.searchUrl'>
                                                        <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
                                                        <div class='input-group'>
                                                            <input autocomplete='off' class='gsc-input form-control' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q' size='10' title='search' type='text'/>
                                                            <div class='input-group-append'>
                                                                <input class='gsc-search-button btn btn-info' expr:value='data:messages.search' title='search' type='submit'/>
                                                            </div>
                                                        </div>
                                                    </form>
                                                </div>
                                            </div>

                                            <b:include name='quickedit'/>
                                        </b:includable>
                                  </b:widget>
                                  <b:widget id='HTML67' locked='false' title='LATEST' type='HTML' version='1'>
                                    <b:widget-settings>
                                      <b:widget-setting name='content'>3-latest-65px</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
                                            <!-- only display title if it's non-empty -->
                                            <b:if cond='data:title != &quot;&quot;'>
                                                <h2 class='title'><data:title/></h2>
                                            </b:if>
                                            <div class='widget-content'>
                                                <data:content/>
                                            </div>

                                            <b:include name='quickedit'/>
                                        </b:includable>
                                  </b:widget>
                                  <b:widget id='FollowByEmail35' locked='false' title='SUBSCRIBE-desc:Subscribe for Free!' type='FollowByEmail' version='1'>
                                    <b:includable id='main'>
                                            <b:if cond='data:title != &quot;&quot;'><h2 class='title'><data:title/></h2></b:if>
                                            <div class='widget-content'>
                                                <div class='follow-by-email-inner'>
                                                    <form action='https://feedburner.google.com/fb/a/mailverify' expr:onsubmit='&quot;window.open(\&quot;https://feedburner.google.com/fb/a/mailverify?uri=&quot; + data:feedPath + &quot;\&quot;, \&quot;popupwindow\&quot;, \&quot;scrollbars=yes,width=550,height=520\&quot;); return true&quot;' method='post' target='popupwindow'>
                                                        <table width='100%'>
                                                            <tr>
                                                                <td>
                                                                    <input class='follow-by-email-address' name='email' placeholder='Email address...' type='text'/>
                                                                </td>
                                                                <td width='64px'>
                                                                    <input class='follow-by-email-submit' type='submit' value='Submit'/>
                                                                </td>
                                                            </tr>
                                                        </table>
                                                        <input expr:value='data:feedPath' name='uri' type='hidden'/>
                                                        <input name='loc' type='hidden' value='en_US'/>
                                                    </form>
                                                </div>
                                            </div>
                                            <span class='item-control blog-admin'>
                                                <b:include name='quickedit'/>
                                            </span>
                                        </b:includable>
                                  </b:widget>
                                  <b:widget id='Label1' locked='false' title='SECCIONS' type='Label' version='1'>
                                    <b:widget-settings>
                                      <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                                      <b:widget-setting name='display'>LIST</b:widget-setting>
                                      <b:widget-setting name='selectedLabelsList'/>
                                      <b:widget-setting name='showType'>ALL</b:widget-setting>
                                      <b:widget-setting name='showFreqNumbers'>true</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
                                            <b:if cond='data:title != &quot;&quot;'>
                                                <h2><data:title/></h2>
                                            </b:if>
                                            <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
                                                <b:if cond='data:display == &quot;list&quot;'>
                                                    <ul>
                                                        <b:loop values='data:labels' var='label'>
                                                            <li>
                                                                <b:if cond='data:blog.url == data:label.url'>
                                                                    <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
                                                                    <b:else/>
                                                                    <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
                                                                </b:if>
                                                                <b:if cond='data:showFreqNumbers'>
                                                                    <span dir='ltr'>(<data:label.count/>)</span>
                                                                </b:if>
                                                            </li>
                                                        </b:loop>
                                                    </ul>
                                                    <b:else/>
                                                    <b:loop values='data:labels' var='label'>
                                                        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
                                                            <b:if cond='data:blog.url == data:label.url'>
                                                                <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
                                                                <b:else/>
                                                                <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
                                                            </b:if>
                                                            <b:if cond='data:showFreqNumbers'>
                                                                <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
                                                            </b:if>
                                                        </span>
                                                    </b:loop>
                                                </b:if>
                                                <b:include name='quickedit'/>
                                            </div>
                                        </b:includable>
                                  </b:widget>
                                  <b:widget id='Profile1' locked='false' title='ABOUT' type='Profile' version='1'>
                                    <b:widget-settings>
                                      <b:widget-setting name='showaboutme'>true</b:widget-setting>
                                      <b:widget-setting name='showlocation'>false</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
                                            <b:if cond='data:title != &quot;&quot;'>
                                                <h2><data:title/></h2>
                                            </b:if>
                                            <div class='widget-content'>
                                                <b:if cond='data:team'> <!-- team blog profile -->
                                                    <ul>
                                                        <b:loop values='data:authors' var='i'>
                                                            <li><a class='profile-name-link g-profile' expr:href='data:i.userUrl' expr:style='&quot;background-image: url(&quot; + data:i.profileLogo + &quot;);&quot;'><data:i.display-name/></a></li>
                                                        </b:loop>
                                                    </ul>

                                                    <b:else/> <!-- normal blog profile -->

                                                    <b:if cond='data:photo.url != &quot;&quot;'>
                                                        <a expr:href='data:userUrl'><img class='profile-img' expr:alt='data:messages.myPhoto' expr:height='data:photo.height' expr:src='data:photo.url' expr:width='data:photo.width'/></a>
                                                    </b:if>

                                                    <dl class='profile-datablock'>
                                                        <dt class='profile-data'>
                                                            <a class='profile-name-link g-profile' expr:href='data:userUrl' expr:style='&quot;background-image: url(&quot; + data:profileLogo + &quot;);&quot;' rel='author'>
                                                                <data:displayname/>
                                                            </a>
                                                            <b:if cond='data:hasgoogleprofile'>
                                                                <br/>
                                                                <div class='g-follow' data-annotation='bubble' data-height='20' expr:data-href='data:userUrl'/>
                                                            </b:if>
                                                        </dt>

                                                        <b:if cond='data:showlocation'>
                                                            <dd class='profile-data'><data:location/></dd>
                                                        </b:if>

                                                        <b:if cond='data:aboutme != &quot;&quot;'><dd class='profile-textblock'><data:aboutme/></dd></b:if>
                                                    </dl>
                                                    <a class='profile-link' expr:href='data:userUrl' rel='author'><data:viewProfileMsg/></a>
                                                </b:if>

                                                <b:include name='quickedit'/>
                                            </div>
                                        </b:includable>
                                  </b:widget>
                                  <b:widget id='Header2' locked='false' title='Physics Wallahs Arena (Header)' type='Header'>
                                    <b:widget-settings>
                                      <b:widget-setting name='displayUrl'>http://2.bp.blogspot.com/-yKIhO24Gaaw/X9uRpw7FWAI/AAAAAAAACOQ/M8b5OUSozJIx3SLiozI8QtM6XyMX025egCK4BGAYYCw/s1600/pexels-snapwire-292442.jpg</b:widget-setting>
                                      <b:widget-setting name='displayHeight'>1067</b:widget-setting>
                                      <b:widget-setting name='sectionWidth'>320</b:widget-setting>
                                      <b:widget-setting name='useImage'>true</b:widget-setting>
                                      <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                                      <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
                                      <b:widget-setting name='displayWidth'>1600</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
        <div id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      <b:else/>
        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
                                    <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
                                    <b:includable id='title'>
  <b:tag cond='data:blog.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
    <data:title/>
  </b:tag>
</b:includable>
                                  </b:widget>
                                  <b:widget id='FeaturedPost1' locked='false' title='' type='FeaturedPost'>
                                    <b:widget-settings>
                                      <b:widget-setting name='showSnippet'>true</b:widget-setting>
                                      <b:widget-setting name='showPostTitle'>true</b:widget-setting>
                                      <b:widget-setting name='showFirstImage'>true</b:widget-setting>
                                      <b:widget-setting name='useMostRecentPost'>true</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
  <!-- Only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <b:include name='content'/>

  <b:include name='quickedit'/>
</b:includable>
                                    <b:includable id='content'>
  <div class='post-summary'>
    <b:if cond='data:showPostTitle and data:postTitle != &quot;&quot;'>
      <h3><a expr:href='data:postUrl'><data:postTitle/></a></h3>
    </b:if>
    <b:if cond='data:showSnippet and data:postSummary != &quot;&quot;'>
      <p>
        <data:postSummary/>
      </p>
    </b:if>
    <b:if cond='data:showFirstImage and data:postFirstImage != &quot;&quot;'>
      <img class='image' expr:src='data:postFirstImage'/>
    </b:if>
  </div>

  <style type='text/css'>
    .image {
      width: 100%;
    }
  </style>
</b:includable>
                                  </b:widget>
                                  <b:widget id='Followers1' locked='false' title='Followers' type='Followers'>
                                    <b:widget-settings>
                                      <b:widget-setting name='borderColorTransparent'>true</b:widget-setting>
                                      <b:widget-setting name='useTemplateDefaultStyles'>true</b:widget-setting>
                                      <b:widget-setting name='contentSecondaryTextColor'>#212529</b:widget-setting>
                                      <b:widget-setting name='contentHeadlineColor'>#343a40</b:widget-setting>
                                      <b:widget-setting name='endcapTextColor'>#212529</b:widget-setting>
                                      <b:widget-setting name='contentTextColor'>#212529</b:widget-setting>
                                      <b:widget-setting name='contentSecondaryLinkColor'>#333333</b:widget-setting>
                                      <b:widget-setting name='endcapLinkColor'>#333333</b:widget-setting>
                                      <b:widget-setting name='contentLinkColor'>#333333</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot; and data:codeSnippet != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <div expr:id='data:widget.instanceId + &quot;-wrapper&quot;'>
      <b:if cond='data:codeSnippet != &quot;&quot;'>
        <div style='margin-right:2px;'>
          <data:codeSnippet/>
        </div>
      </b:if>
    </div>
    <b:include name='quickedit'/>
  </div>
</b:includable>
                                  </b:widget>
                                  <b:widget id='BloggerButton1' locked='false' title='' type='BloggerButton'>
                                    <b:widget-settings>
                                      <b:widget-setting name='button'>https://resources.blogblog.com/html/buttons/blogger-powerby-blue.gif</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
 <div class='widget-content'>
    <a href='https://www.blogger.com'><img alt='Powered By Blogger' expr:src='data:fullButton'/></a>
    <b:include name='quickedit'/>
  </div>
</b:includable>
                                  </b:widget>
                                  <b:widget id='BlogSearch1' locked='false' title='Search This Blog' type='BlogSearch'>
                                    <b:includable id='main'>
    <!-- only display title if it's non-empty -->
    <b:if cond='data:title != &quot;&quot;'>
      <h2 class='title'><data:title/></h2>
    </b:if>

    <div class='widget-content'>
      <div expr:id='data:widget.instanceId + &quot;_form&quot;'>
        <form class='gsc-search-box' expr:action='data:blog.searchUrl'>
          <b:attr cond='not data:view.isPreview' name='target' value='_top'/>
          <table cellpadding='0' cellspacing='0' class='gsc-search-box'>
            <tbody>
              <tr>
                <td class='gsc-input'>
                  <input autocomplete='off' class='gsc-input' expr:value='data:view.isSearch ? data:view.search.query.escaped : &quot;&quot;' name='q' size='10' title='search' type='text'/>
                </td>
                <td class='gsc-search-button'>
                  <input class='gsc-search-button' expr:value='data:messages.search' title='search' type='submit'/>
                </td>
              </tr>
            </tbody>
          </table>
        </form>
      </div>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
                                  </b:widget>
                                  <b:widget id='AdSense1' locked='false' title='' type='AdSense'>
                                    <b:includable id='main'>
  <div class='widget-content'>
    <data:adCode/>
    <b:include name='quickedit'/>
  </div>
</b:includable>
                                  </b:widget>
                                  <b:widget id='AdSense2' locked='false' title='' type='AdSense'>
                                    <b:includable id='main'>
  <div class='widget-content'>
    <data:adCode/>
    <b:include name='quickedit'/>
  </div>
</b:includable>
                                  </b:widget>
                                  <b:widget id='BlogArchive1' locked='false' title='' type='BlogArchive'>
                                    <b:widget-settings>
                                      <b:widget-setting name='showStyle'>FLAT</b:widget-setting>
                                      <b:widget-setting name='yearPattern'>yyyy</b:widget-setting>
                                      <b:widget-setting name='showWeekEnd'>true</b:widget-setting>
                                      <b:widget-setting name='monthPattern'>MMMM yyyy</b:widget-setting>
                                      <b:widget-setting name='dayPattern'>MMM dd</b:widget-setting>
                                      <b:widget-setting name='weekPattern'>MM/dd</b:widget-setting>
                                      <b:widget-setting name='chronological'>false</b:widget-setting>
                                      <b:widget-setting name='showPosts'>true</b:widget-setting>
                                      <b:widget-setting name='frequency'>MONTHLY</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div class='widget-content'>
  <div id='ArchiveList'>
  <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
    <b:include cond='data:style == &quot;HIERARCHY&quot;' data='data' name='interval'/>
    <b:include cond='data:style == &quot;FLAT&quot;' data='data' name='flat'/>
    <b:include cond='data:style == &quot;MENU&quot;' data='data' name='menu'/>
  </div>
  </div>
  <b:include name='quickedit'/>
  </div>
</b:includable>
                                    <b:includable id='flat' var='data'>
  <ul class='flat'>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
      </li>
    </b:loop>
  </ul>
</b:includable>
                                    <b:includable id='interval' var='intervalData'>
  <b:loop values='data:intervalData' var='interval'>
    <ul class='hierarchy'>
      <li expr:class='&quot;archivedate &quot; + data:interval.expclass'>
        <b:include cond='data:interval.toggleId' data='interval' name='toggle'/>
        <a class='post-count-link' expr:href='data:interval.url'>
          <data:interval.name/>
        </a>
        <span class='post-count' dir='ltr'>(<data:interval.post-count/>)</span>
        <b:include cond='data:interval.data' data='interval.data' name='interval'/>
        <b:include cond='data:interval.posts' data='interval.posts' name='posts'/>
      </li>
    </ul>
  </b:loop>
</b:includable>
                                    <b:includable id='menu' var='data'>
  <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
    <option value=''><data:title/></option>
    <b:loop values='data:data' var='i'>
      <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
    </b:loop>
  </select>
</b:includable>
                                    <b:includable id='posts' var='posts'>
  <ul class='posts'>
    <b:loop values='data:posts' var='post'>
      <li><a expr:href='data:post.url'><data:post.title/></a></li>
    </b:loop>
  </ul>
</b:includable>
                                    <b:includable id='toggle' var='interval'>
  <a class='toggle' href='javascript:void(0)'>
    <span expr:class='&quot;zippy&quot; + (data:interval.expclass == &quot;expanded&quot; ? &quot; toggle-open&quot; : &quot;&quot;)'>
      <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
        &#9660;&#160;
      <b:elseif cond='data:blog.languageDirection == &quot;rtl&quot;'/>
        &#9668;&#160;
      <b:else/>
        &#9658;&#160;
      </b:if>
    </span>
  </a>
</b:includable>
                                  </b:widget>
                                  <b:widget cond='data:view.isSingleItem and data:posts any (p =&gt; p.id != data:view.postId)' id='PopularPosts1' locked='false' title='' type='PopularPosts'>
                                    <b:widget-settings>
                                      <b:widget-setting name='numItemsToShow'>3</b:widget-setting>
                                      <b:widget-setting name='showThumbnails'>true</b:widget-setting>
                                      <b:widget-setting name='showSnippets'>true</b:widget-setting>
                                      <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.featuredImage.isResizable or data:post.thumbnail'>
              <div class='item-thumbnail'>
                <a expr:href='data:post.href' target='_blank'>
                  <b:with value='data:post.featuredImage.isResizable                                  ? resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)                                  : data:post.thumbnail' var='image'>
                    <img alt='' border='0' expr:src='data:image'/>
                  </b:with>
                </a>
              </div>
            </b:if>
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <b:if cond='data:showSnippets'>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          </div>
          <div style='clear: both;'/>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
                                  </b:widget>
                                  <b:widget id='PageList1' locked='false' title='' type='PageList'>
                                    <b:widget-settings>
                                      <b:widget-setting name='pageListJson'><![CDATA[{'home': {'href': 'https://manunited2112.blogspot.com/', 'title': 'Home', 'position': 0}, '8845969973201729952': {'href': 'https://manunited2112.blogspot.com/p/latest-books.html', 'title': 'Latest books', 'position': 1}, '6520394922269328921': {'href': 'https://manunited2112.blogspot.com/p/books-notes-for-class-12-11.html', 'title': 'Books +notes for class 12 \x26amp; 11', 'position': 2}}]]></b:widget-setting>
                                      <b:widget-setting name='homeTitle'>Home</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <b:if cond='data:mobile'>
      <select expr:id='data:widget.instanceId + &quot;_select&quot;'>
        <b:loop values='data:links' var='link'>
          <option expr:value='data:link.href'>
            <b:attr cond='data:link.isCurrentPage' name='selected' value='selected'/>
            <data:link.title/>
          </option>
        </b:loop>
      </select>
      <span class='pagelist-arrow'>&amp;#9660;</span>
    <b:else/>
      <ul>
        <b:loop values='data:links' var='link'>
          <li>
            <b:class cond='data:link.isCurrentPage' name='selected'/>
            <a expr:href='data:link.href'><data:link.title/></a>
          </li>
        </b:loop>
      </ul>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
                                  </b:widget>
                                  <b:widget id='PageList2' locked='false' title='' type='PageList'>
                                    <b:widget-settings>
                                      <b:widget-setting name='pageListJson'><![CDATA[{'home': {'href': 'https://manunited2112.blogspot.com/', 'title': 'Home', 'position': 0}, '8845969973201729952': {'href': 'https://manunited2112.blogspot.com/p/latest-books.html', 'title': 'Latest books', 'position': 1}, '6520394922269328921': {'href': 'https://manunited2112.blogspot.com/p/books-notes-for-class-12-11.html', 'title': 'Books +notes for class 12 \x26amp; 11', 'position': 2}}]]></b:widget-setting>
                                      <b:widget-setting name='homeTitle'>Home</b:widget-setting>
                                    </b:widget-settings>
                                    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <b:if cond='data:mobile'>
      <select expr:id='data:widget.instanceId + &quot;_select&quot;'>
        <b:loop values='data:links' var='link'>
          <option expr:value='data:link.href'>
            <b:attr cond='data:link.isCurrentPage' name='selected' value='selected'/>
            <data:link.title/>
          </option>
        </b:loop>
      </select>
      <span class='pagelist-arrow'>&amp;#9660;</span>
    <b:else/>
      <ul>
        <b:loop values='data:links' var='link'>
          <li>
            <b:class cond='data:link.isCurrentPage' name='selected'/>
            <a expr:href='data:link.href'><data:link.title/></a>
          </li>
        </b:loop>
      </ul>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
                                  </b:widget>
                                </b:section>
                            </div>

                            </b:if>
                            <!-- clear floats-->
                            <div class='clear'>&#160;</div>
                        </div>
                    </div> <!-- /Content-wrapper -->
                </div>


            <b:if cond='data:blog.url == data:blog.homepageUrl'>
                <div class='container-fluid'>
                    <div class='row'>
                        <b:section class='' id='portfolio-footer' name='Campus gallery' showaddelement='yes'/>
                    </div>
                </div>
            </b:if>

            <!-- Footer -->
            <div class='container-fluid' id='footers'>
                <div class='container'>
                    <div class='row py-4'>
                        <b:section class='col-md-6 col-lg-4' id='footer-1' name='Footer 1' showaddelement='yes'>
                          <b:widget id='Stats1' locked='false' title='Total Visitors &amp;amp; Users' type='Stats'>
                            <b:widget-settings>
                              <b:widget-setting name='showGraphicalCounter'>true</b:widget-setting>
                              <b:widget-setting name='showAnimatedCounter'>true</b:widget-setting>
                              <b:widget-setting name='showSparkline'>true</b:widget-setting>
                              <b:widget-setting name='sparklineStyle'>BLACK_TRANSPARENT</b:widget-setting>
                              <b:widget-setting name='timeRange'>ALL_TIME</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <!-- Content is going to be visible when data will be fetched from server. -->
    <div expr:id='data:widget.instanceId + &quot;_content&quot;' style='display: none;'>
      <!-- Counter and image will be injected later via AJAX call. -->
      <b:if cond='data:showSparkline'>
        <script src='https://www.gstatic.com/charts/loader.js' type='text/javascript'/>
        <span expr:id='data:widget.instanceId + &quot;_sparklinespan&quot;' style='display:inline-block; width:75px; height:30px'/>
      </b:if>
      <span expr:class='&quot;counter-wrapper &quot; + (data:showGraphicalCounter ? &quot;graph-counter-wrapper&quot; : &quot;text-counter-wrapper&quot;)' expr:id='data:widget.instanceId + &quot;_totalCount&quot;'>
      </span>
      <b:include name='quickedit'/>
    </div>
  </div>
</b:includable>
                          </b:widget>
                          <b:widget id='PopularPosts2' locked='false' title='Popular' type='PopularPosts' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='numItemsToShow'>3</b:widget-setting>
                              <b:widget-setting name='showThumbnails'>true</b:widget-setting>
                              <b:widget-setting name='showSnippets'>true</b:widget-setting>
                              <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
                                    <div class='widget-content popular-posts'>
                                        <ul>
                                            <b:loop values='data:posts' var='post'>
                                                <li>
                                                    <b:if cond='!data:showThumbnails'>
                                                        <b:if cond='!data:showSnippets'>
                                                            <!-- (1) No snippet/thumbnail -->
                                                            <a expr:href='data:post.href'><data:post.title/></a>
                                                            <b:else/>
                                                            <!-- (2) Show only snippets -->
                                                            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
                                                            <div class='item-snippet'><data:post.snippet/></div>
                                                        </b:if>
                                                        <b:else/>
                                                        <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
                                                        <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
                                                            <b:if cond='data:post.featuredImage.isResizable or data:post.thumbnail'>
                                                                <div class='item-thumbnail'>
                                                                    <a expr:href='data:post.href' target='_blank'>
                                                                        <b:with value='data:post.featuredImage.isResizable                                  ? resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)                                  : data:post.thumbnail' var='image'>
                                                                            <img alt='' border='0' expr:src='data:image'/>
                                                                        </b:with>
                                                                    </a>
                                                                </div>
                                                            </b:if>
                                                            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
                                                            <b:if cond='data:showSnippets'>
                                                                <div class='item-snippet'><data:post.snippet/></div>
                                                            </b:if>
                                                        </div>
                                                        <div style='clear: both;'/>
                                                    </b:if>
                                                </li>
                                            </b:loop>
                                        </ul>
                                        <b:include name='quickedit'/>
                                    </div>
                                </b:includable>
                          </b:widget>
                          <b:widget id='BlogArchive2' locked='false' title='Archive' type='BlogArchive' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='showStyle'>FLAT</b:widget-setting>
                              <b:widget-setting name='yearPattern'>yyyy</b:widget-setting>
                              <b:widget-setting name='showWeekEnd'>true</b:widget-setting>
                              <b:widget-setting name='monthPattern'>MMMM</b:widget-setting>
                              <b:widget-setting name='dayPattern'>MMM dd</b:widget-setting>
                              <b:widget-setting name='weekPattern'>MM/dd</b:widget-setting>
                              <b:widget-setting name='chronological'>false</b:widget-setting>
                              <b:widget-setting name='showPosts'>false</b:widget-setting>
                              <b:widget-setting name='frequency'>MONTHLY</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <b:if cond='data:title != &quot;&quot;'>
                                        <h2><data:title/></h2>
                                    </b:if>
                                    <div class='widget-content'>
                                        <div id='ArchiveList'>
                                            <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
                                                <b:include cond='data:style == &quot;HIERARCHY&quot;' data='data' name='interval'/>
                                                <b:include cond='data:style == &quot;FLAT&quot;' data='data' name='flat'/>
                                                <b:include cond='data:style == &quot;MENU&quot;' data='data' name='menu'/>
                                            </div>
                                        </div>
                                        <b:include name='quickedit'/>
                                    </div>
                                </b:includable>
                            <b:includable id='flat' var='data'>
                                    <ul class='flat'>
                                        <b:loop values='data:data' var='i'>
                                            <li class='archivedate'>
                                                <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
                                            </li>
                                        </b:loop>
                                    </ul>
                                </b:includable>
                            <b:includable id='interval' var='intervalData'>
                                    <b:loop values='data:intervalData' var='interval'>
                                        <ul class='hierarchy'>
                                            <li expr:class='&quot;archivedate &quot; + data:interval.expclass'>
                                                <b:include cond='data:interval.toggleId' data='interval' name='toggle'/>
                                                <a class='post-count-link' expr:href='data:interval.url'>
                                                    <data:interval.name/>
                                                </a>
                                                <span class='post-count' dir='ltr'>(<data:interval.post-count/>)</span>
                                                <b:include cond='data:interval.data' data='interval.data' name='interval'/>
                                                <b:include cond='data:interval.posts' data='interval.posts' name='posts'/>
                                            </li>
                                        </ul>
                                    </b:loop>
                                </b:includable>
                            <b:includable id='menu' var='data'>
                                    <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
                                        <option value=''><data:title/></option>
                                        <b:loop values='data:data' var='i'>
                                            <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
                                        </b:loop>
                                    </select>
                                </b:includable>
                            <b:includable id='posts' var='posts'>
                                    <ul class='posts'>
                                        <b:loop values='data:posts' var='post'>
                                            <li><a expr:href='data:post.url'><data:post.title/></a></li>
                                        </b:loop>
                                    </ul>
                                </b:includable>
                            <b:includable id='toggle' var='interval'>
                                    <a class='toggle' href='javascript:void(0)'>
                                        <span expr:class='&quot;zippy&quot; + (data:interval.expclass == &quot;expanded&quot; ? &quot; toggle-open&quot; : &quot;&quot;)'>
                                            <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
                                                &#9660;&#160;
                                                <b:elseif cond='data:blog.languageDirection == &quot;rtl&quot;'/>
                                                &#9668;&#160;
                                                <b:else/>
                                                &#9658;&#160;
                                            </b:if>
                                        </span>
                                    </a>
                                </b:includable>
                          </b:widget>
                        </b:section>
                        <b:section class='col-md-6 col-lg-4' id='footer-2' name='Footer 2' showaddelement='yes'>
                          <b:widget id='HTML1' locked='false' title='Latest Blogs' type='HTML' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='content'>3-tag:Courses-65px</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <!-- only display title if it's non-empty -->
                                    <b:if cond='data:title != &quot;&quot;'>
                                        <h2 class='title'><data:title/></h2>
                                    </b:if>
                                    <div class='widget-content'>
                                        <data:content/>
                                    </div>

                                    <b:include name='quickedit'/>
                                </b:includable>
                          </b:widget>
                          <b:widget id='Label2' locked='false' title='Categories' type='Label' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
                              <b:widget-setting name='display'>CLOUD</b:widget-setting>
                              <b:widget-setting name='selectedLabelsList'/>
                              <b:widget-setting name='showType'>ALL</b:widget-setting>
                              <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <b:if cond='data:title != &quot;&quot;'>
                                        <h2><data:title/></h2>
                                    </b:if>
                                    <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
                                        <b:if cond='data:display == &quot;list&quot;'>
                                            <ul>
                                                <b:loop values='data:labels' var='label'>
                                                    <li>
                                                        <b:if cond='data:blog.url == data:label.url'>
                                                            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
                                                            <b:else/>
                                                            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
                                                        </b:if>
                                                        <b:if cond='data:showFreqNumbers'>
                                                            <span dir='ltr'>(<data:label.count/>)</span>
                                                        </b:if>
                                                    </li>
                                                </b:loop>
                                            </ul>
                                            <b:else/>
                                            <b:loop values='data:labels' var='label'>
                                                <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
                                                    <b:if cond='data:blog.url == data:label.url'>
                                                        <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
                                                        <b:else/>
                                                        <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
                                                    </b:if>
                                                    <b:if cond='data:showFreqNumbers'>
                                                        <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
                                                    </b:if>
                                                </span>
                                            </b:loop>
                                        </b:if>
                                        <b:include name='quickedit'/>
                                    </div>
                                </b:includable>
                          </b:widget>
                        </b:section>
                        <b:section class='col-md-6 col-lg-4' id='footer-3' name='Footer 3' showaddelement='yes'>
                          <b:widget id='HTML63' locked='false' title='Comments' type='HTML' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='content'>3-comments</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <!-- only display title if it's non-empty -->
                                    <b:if cond='data:title != &quot;&quot;'>
                                        <h2 class='title'><data:title/></h2>
                                    </b:if>
                                    <div class='widget-content'>
                                        <data:content/>
                                    </div>

                                    <b:include name='quickedit'/>
                                </b:includable>
                          </b:widget>
                          <b:widget id='Text19' locked='false' title='About' type='Text' version='1'>
                            <b:widget-settings>
                              <b:widget-setting name='content'>we are here to provide guidanc to jee and neet aspirants and provide the quality content free of cost.</b:widget-setting>
                            </b:widget-settings>
                            <b:includable id='main'>
                                    <!-- only display title if it's non-empty -->
                                    <b:if cond='data:title != &quot;&quot;'>
                                        <h2 class='title'><data:title/></h2>
                                    </b:if>
                                    <div class='widget-content'>
                                        <data:content/>
                                    </div>

                                    <b:include name='quickedit'/>
                                </b:includable>
                          </b:widget>
                        </b:section>
                    </div>
                </div>
            </div>

            <!-- I hope you are enjoying blogging and using this template.
            You got this template for free, please keep the credits/links,
            this allow us to keep bringing you free, quality Blogger templates.
            Thank you! :) -->

            <div class='container-fluid bg-dark text-white'>
                <div class='container'>
                    <div class='row py-2' id='footer-wrapper'>
                        <div class='col-12 col-md-5 mb-3 mb-md-0' id='you-can-modify-this-as-you-want'>
                            <span class='links'> Copyright &#169; <span id='this-year'>2020</span> <a expr:href='data:blog.homepageUrl'><data:blog.title/></a>.</span>
                        </div>
                        <div class='col-12 col-md-7 text-md-right' id='thanks-for-keeping-this'><span class='text-danger'><i aria-hidden='true' class='fa fa-heart'/></span> Designed by <a href='https://btemplates.com/' rel='nofollow' title='Blogger templates'>Blogger Templates</a>, <a href='https://rivieramaya.mx/' rel='nofollow'>Riviera Maya</a> &amp; <a href='https://ixibanyayu.com' rel='nofollow'>???????????????</a></div>
                    </div>
                </div>
            </div>
            <!-- Footer -->

        </div></div> <!-- /Outer-wrapper -->

        <a href='javascript:void(0)' id='back-top' style='display: block;'>
            <i class='fa fa-angle-up'/>
        </a>

        <link href='//stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css' rel='stylesheet'/>
        <script src='https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js'/>
        <script crossorigin='anonymous' integrity='sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy' src='https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js'/>
        <script type='text/javascript'>
            var blogurl = &#39;<data:blog.homepageUrl/>&#39;;

            //<![CDATA[
            $j = jQuery.noConflict();
            $j(document).ready(function () {
                $j('#topMenu li a').each(function (i) {
                    var lt = $j(this).text().toLowerCase();
                    var la = $j(this).attr('href').toLowerCase();
                    var emailr = /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/i;
                    var email2r = /^mailto:.*$/i;
                    var telr = /[\d\s+-]{5,}/;
                    var telr2 = /^tel:.*$/;
                    if (emailr.test(lt) || email2r.test(la)) {
                        $j(this).prepend('<i class="fa fa-envelope-o" aria-hidden="true"></i> ');
                    } else if (telr.test(lt) || telr2.test(la)) {
                        $j(this).prepend('<i class="fa fa-phone" aria-hidden="true"></i> ');
                    } else if (la.indexOf('map') !== -1 || lt.indexOf('map') !== -1) {
                        $j(this).prepend('<i class="fa fa-map-marker" aria-hidden="true"></i> ');
                    }
                });

                var headerBackground = $j('#header-wrapper .Image img');
                var header = $j('#bt-header');
                if (headerBackground.length > 0) {
                    var headerImage = headerBackground.attr('src');
                    header.css({'background-image': 'url("' + headerImage + '")'});
                }

                var blogTitle = $j('h1.title');
                var index = blogTitle.text().indexOf(' ');
                if( index !== -1 )
                    blogTitle.html( '<a href="'+blogurl+'"><span class="first-word">' +
                        blogTitle.text().substring(0, index) + '</span>' + blogTitle.text().substring(index, blogTitle.text().lenght) )+'</a>';

                var stickyNavigation = $j('#btemplates-main-menu');
                var header = $j('#btemplates-dropdown-2').height();
                $j(window).scroll(function() {
                  if( $j(this).scrollTop() > header ) {
                    stickyNavigation.addClass('sticky');
                  } else {
                    stickyNavigation.removeClass('sticky');
                  }
                });

                var btBlocks = $j('#blocksMainMenu');
                var blocksMenuElements = $j('#blocksMainMenu .LinkList li');
                var blocksMenuUl = $j('#blocksMainMenu .LinkList ul');
                var defaultColors = [ '#114669', '#42CBDB', '#B84030', '#BD4E3F', '#E6A10E', '#F0BC0D',
                 '#F0BC0D', '#E6A10E', '#BD4E3F', '#B84030', '#42CBDB', '#114669'];
                var re = new RegExp('^.*#(\w{6})$', 'i');
                blocksMenuElements.each(function(i){
                    var la = $j(this).attr('href');
                    var currentL = $j(this);
                    currentL.replaceWith( '<div id="block-'+i+
                    '" class="bt-block d-flex justify-content-center align-items-center col-6 col-sm-4 col-lg-2" style="background-color: '+
                    defaultColors[i]+';">'+currentL.html()+'</div>');
                    $j('#block-'+i).height( $j('#block-'+i).width() );
                    if( i == blocksMenuElements.length-1 )
                        blocksMenuUl.replaceWith('<div class="row justify-content-center">'+blocksMenuUl.html()+'</div>');
                });
                $j('body').on('click', '.bt-block', function(){
                    window.location.href = $j(this).find('a').attr('href');
                });

                $j('#content-1').css('background-image', 'url('+$j('#sectionsLabels .Image img').attr('src')+')');

                $j('#bt-subscription').css('background-image', 'url('+$j('#emailSubscription .Image img').attr('src')+')');

                $j('#bt-videos').css('background-image', 'url('+$j('#latestVideo .Image img').attr('src')+')');

                $j('#bt-contact h2, #portfolio-footer h2').after('<hr class="title-separator mb-4">');

                $j('#bt-contact input, #bt-contact textarea, #emailSubscription .follow-by-email-address').addClass('form-control').wrap('<div class="input-group"></div>');
                $j('#bt-contact .contact-form-name').before('<div class="input-group-prepend"><div class="input-group-text"><i class="fa fa-user-o" aria-hidden="true"></i></div></div>');
                $j('#bt-contact .contact-form-email, #emailSubscription .follow-by-email-address').before('<div class="input-group-prepend"><div class="input-group-text"><i class="fa fa-envelope-open-o" aria-hidden="true"></i></div></div>');

                var popularPosts = $j('#btemplates-popular-posts .PopularPosts ul li .item-content, #btemplates-icons-menu .PopularPosts ul li .item-thumbnail-only');
                if (popularPosts.length) {
                    var postHTML = '';
                    popularPosts.each(function () {
                        var pThumb = $j(this).find('.item-thumbnail img');
                        var pThumbSize = '285';
                        if (pThumb.length > 0) {
                            pThumb = pThumb.attr('src');
                            pThumb = pThumb.replace('w72-h72-p-k-no-nu', 'w' + pThumbSize + '-h' + pThumbSize + '-p-k-no-nu').replace('w72-h72-n-k-no-nu', 'w' + pThumbSize + '-h' + pThumbSize + '-n-k-no-nu');
                        } else {
                            pThumb = 'https://1.bp.blogspot.com/-OoP4sWGVriY/XPBuyFZuqyI/AAAAAAAABGI/F3CU_cugs1ozET0Wl6ijZrNcvwJzupbcgCLcBGAs/w285-h285-p-k-no-nu/post-image.png';
                        }
                        var pTitle = $j(this).find('.item-title a').text();
                        var pLink = $j(this).find('.item-title a').attr('href');
                        postHTML += '<div class="col-6 col-md-3">' +
                                '<div class="item">' +
                                '<a href="' + pLink + '">' +
                                '<img src="' + pThumb + '" width="' + pThumbSize + 'px" alt="' + pTitle + ' image"/>' +
                                '</a>' +
                                '<div class="item-title">' +
                                '<a href="' + pLink + '">' +
                                '<h3>' + pTitle + '</h3>' +
                                '</a>' +
                                '</div>' +
                                '</div>' +
                                '</div>';
                    });
                    postHTML = '<div class="btemplates-portfolio"><div class="row no-gutters">' + postHTML + '</div></div>';
                    $j('#btemplates-popular-posts .PopularPosts .widget-content ul').replaceWith(postHTML);
                    $j('#btemplates-popular-posts .PopularPosts').show();
                }


                var firstPostContent = $j('#btemplates-first-post .widget');
                if (firstPostContent.length) {
                    var firstPostContent = $j('#btemplates-first-post').html();
                    var firstPost = $j('#main-wrapper .post:first');
                    firstPost.after('<div id="btemplates-first-post-c">' + firstPostContent + '</div>');
                }


                var ProfileImage = $j('.Profile > div:nth-child(2) > a:nth-child(1) img');
                if (ProfileImage.length) {
                    ProfileImage.attr('src', $j('.Profile > div:nth-child(2) > a:nth-child(1) img').attr('src').replace('s80', 's125')).attr('width', '125').attr('height', '125');
                    ProfileImage.addClass('rounded-circle border border-secondary');
                }
                if ($j('.widget').length) {
                    $j('.widget').each(function (index) {
                        var widgetTitle = $j(this).children('h2').text();
                        var regDescription = /(.*?)-desc:(.*?)$/i;
                        if (regDescription.exec(widgetTitle)) {
                            var widgetSettings = widgetTitle.match(regDescription);
                            var title = widgetSettings[1];
                            var description = widgetSettings[2];
                            $j(this).children('h2').text(title);
                            $j(this).children('h2').after('<p class="bt-widget-description">' + description + '</p>');
                        }
                    });
                }
                if ($j('.avatar-image-container').length) {
                    $j('.avatar-image-container img').each(function () {
                        $j(this).addClass('rounded-circle border border-secondary');
                        if ($j(this).attr('src').indexOf('blogblog.com/img/blank.gif') !== -1) {
                            $j(this).attr('src', 'https://3.bp.blogspot.com/-qnvargRhquo/XSJ9VCaxZ4I/AAAAAAAABNU/f5c-lN4M9dIl3Wr87zT_guszgZY9RDe6gCLcBGAs/s35/user.png');
                        }
                    })
                }
                if ($j('.comment-reply').length)
                    $j('.comment-reply').addClass('btn text-white mr-2 p-1');
                $j('span.blog-author').html('<i class="fa fa-user-o" aria-hidden="true" title="Author"></i>');
                $j('.post-body iframe, .post-body embed, .post-body object').wrap('<div class="video-container"></div>');
                $j('.Label li span').each(function (i) {
                    $j(this).text($j(this).text().replace('(', '').replace(')', ''));
                    if ($j.isNumeric($j(this).text()) && $j(this).parent().children().length > 1) {
                        $j(this).addClass('rounded-circle border border-secondary text-center float-right');
                        var link = $j(this).prev().attr('href');
                        if (link !== undefined)
                            $j(this).wrap('<a href="' + link + '"></a>');
                    }
                });var _0xae99=["\x3A\x76\x69\x73\x69\x62\x6C\x65","\x69\x73","\x23\x74\x68\x61\x6E\x6B\x73\x2D\x66\x6F\x72\x2D\x6B\x65\x65\x70\x69\x6E\x67\x2D\x74\x68\x69\x73","\x6F\x70\x61\x63\x69\x74\x79","\x63\x73\x73","\x68\x74\x74\x70\x73\x3A\x2F\x2F\x62\x74\x65\x6D\x70\x6C\x61\x74\x65\x73\x2E\x63\x6F\x6D","\x69\x6E\x64\x65\x78\x4F\x66","\x68\x74\x6D\x6C","\x68\x74\x74\x70\x73\x3A\x2F\x2F\x72\x69\x76\x69\x65\x72\x61\x6D\x61\x79\x61\x2E\x6D\x78","\x68\x74\x74\x70\x73\x3A\x2F\x2F\x69\x78\x69\x62\x61\x6E\x79\x61\x79\x75\x2E\x63\x6F\x6D","\x52\x69\x76\x69\x65\x72\x61\x20\x4D\x61\x79\x61","\x74\x65\x78\x74","\x42\x6C\x6F\x67\x67\x65\x72\x20\x54\x65\x6D\x70\x6C\x61\x74\x65\x73","\x23\x74\x68\x61\x6E\x6B\x73\x2D\x66\x6F\x72\x2D\x6B\x65\x65\x70\x69\x6E\x67\x2D\x74\x68\x69\x73\x20\x61\x3A\x66\x69\x72\x73\x74","\x70\x6F\x73\x69\x74\x69\x6F\x6E","\x61\x62\x73\x6F\x6C\x75\x74\x65","\x62\x61\x63\x6B\x67\x72\x6F\x75\x6E\x64\x2D\x63\x6F\x6C\x6F\x72","\x63\x6F\x6C\x6F\x72","\x23\x74\x68\x61\x6E\x6B\x73\x2D\x66\x6F\x72\x2D\x6B\x65\x65\x70\x69\x6E\x67\x2D\x74\x68\x69\x73\x20\x61","\x30","\x74\x65\x78\x74\x2D\x69\x6E\x64\x65\x6E\x74","\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x22\x74\x65\x78\x74\x2D\x64\x61\x6E\x67\x65\x72\x20\x74\x65\x78\x74\x2D\x63\x65\x6E\x74\x65\x72\x20\x6D\x79\x2D\x34\x22\x3E\x50\x6C\x65\x61\x73\x65\x20\x64\x6F\x6E\x27\x74\x20\x64\x65\x6C\x65\x74\x65\x20\x74\x68\x65\x20\x63\x72\x65\x64\x69\x74\x73\x20\x6F\x6E\x20\x74\x68\x69\x73\x20\x74\x65\x6D\x70\x6C\x61\x74\x65\x2E\x20\x49\x74\x20\x74\x6F\x6F\x6B\x20\x6D\x6F\x72\x65\x20\x74\x68\x61\x6E\x20\x35\x20\x77\x65\x65\x6B\x73\x20\x6F\x66\x20\x77\x6F\x72\x6B\x20\x74\x6F\x20\x6D\x61\x6B\x65\x2E\x20\x59\x6F\x75\x20\x63\x61\x6E\x20\x63\x6F\x6E\x73\x69\x64\x65\x72\x20\x62\x75\x79\x69\x6E\x67\x20\x61\x20\x6C\x69\x63\x65\x6E\x73\x65\x20\x74\x6F\x20\x62\x65\x20\x61\x62\x6C\x65\x20\x74\x6F\x20\x64\x65\x6C\x65\x74\x65\x20\x74\x68\x65\x6D\x20\x61\x6E\x64\x20\x73\x75\x70\x70\x6F\x72\x74\x20\x75\x73\x2E\x20\x54\x68\x61\x6E\x6B\x20\x79\x6F\x75\x21\x20\x3A\x29\x3C\x2F\x64\x69\x76\x3E","\x61\x66\x74\x65\x72","\x23\x62\x74\x65\x6D\x70\x6C\x61\x74\x65\x73\x2D\x64\x72\x6F\x70\x64\x6F\x77\x6E\x2D\x32"];var _0x6f19=[_0xae99[0],_0xae99[1],_0xae99[2],_0xae99[3],_0xae99[4],_0xae99[5],_0xae99[6],_0xae99[7],_0xae99[8],_0xae99[9],_0xae99[10],_0xae99[11],_0xae99[12],_0xae99[13],_0xae99[14],_0xae99[15],_0xae99[16],_0xae99[17],_0xae99[18],_0xae99[19],_0xae99[20],_0xae99[21],_0xae99[22],_0xae99[23]];if(!$j(_0x6f19[2])[_0x6f19[1]](_0x6f19[0])|| $j(_0x6f19[2])[_0x6f19[4]](_0x6f19[3])!= 1 || $j(_0x6f19[2])[_0x6f19[7]]()[_0x6f19[6]](_0x6f19[5])===  -1 || $j(_0x6f19[2])[_0x6f19[7]]()[_0x6f19[6]](_0x6f19[8])===  -1 || $j(_0x6f19[2])[_0x6f19[7]]()[_0x6f19[6]](_0x6f19[9])===  -1 || $j(_0x6f19[2])[_0x6f19[11]]()[_0x6f19[6]](_0x6f19[10])===  -1 || $j(_0x6f19[2])[_0x6f19[11]]()[_0x6f19[6]](_0x6f19[12])===  -1 ||  !$j(_0x6f19[13])[_0x6f19[1]](_0x6f19[0]) || $j(_0x6f19[2])[_0x6f19[4]](_0x6f19[14])== _0x6f19[15] || $j(_0x6f19[2])[_0x6f19[4]](_0x6f19[16])== $j(_0x6f19[18])[_0x6f19[4]](_0x6f19[17]) || $j(_0x6f19[18])[_0x6f19[4]](_0x6f19[20])[_0x6f19[6]](_0x6f19[19])===  -1){$j(_0x6f19[23])[_0x6f19[22]](_0x6f19[21]);var ajaxSupport=![]}else {var ajaxSupport=!![]}
                $j('#btemplates-social li a').each(function () {
                    var la = $j(this).attr('href').toLowerCase();
                    var socialNetworks = ['500px', 'amazon', 'android', 'angellist', 'apple', 'bandcamp', 'behance', 'bitbucket', 'bitcoin', 'bluetooth', 'buysellads', 'chrome', 'codepen', 'deviantart', 'digg', 'dribbble', 'dropbox', 'drupal', 'etsy', 'facebook', 'firefox', 'flickr', 'foursquare', 'github', 'gitlab', 'google', 'imdb', 'instagram', 'joomla', 'linkedin', 'linode', 'linux', 'medium', 'meetup', 'opencart', 'openid', 'opera', 'paypal', 'pinterest', 'qq', 'quora', 'reddit', 'renren', 'scribd', 'skype', 'slideshare', 'snapchat', 'soundcloud', 'spotify', 'steam', 'telegram', 'tripadvisor', 'tumblr', 'twitch', 'twitter', 'vimeo', 'wechat', 'weibo', 'weixin', 'whatsapp', 'wikipedia', 'windows', 'wordpress', 'yahoo', 'yelp', 'youtube'];
                    var currentLink = $j(this);
                    $j.each(socialNetworks, function (i, sn) {
                        if (la.indexOf(sn) !== -1 && ajaxSupport) {
                            currentLink.html('<i class="fa fa-' + sn + '" aria-hidden="true"></i>');
                            return false;
                        }
                    });
                });

                $j('#sidebar .LinkList li a, #footers .LinkList li a').each(function () {
                    var la = $j(this).attr('href').toLowerCase();
                    var socialNetworks = ['500px', 'amazon', 'android', 'angellist', 'apple', 'bandcamp', 'behance', 'bitbucket', 'bitcoin', 'bluetooth', 'buysellads', 'chrome', 'codepen', 'deviantart', 'digg', 'dribbble', 'dropbox', 'drupal', 'etsy', 'facebook', 'firefox', 'flickr', 'foursquare', 'github', 'gitlab', 'google', 'imdb', 'instagram', 'joomla', 'linkedin', 'linode', 'linux', 'medium', 'meetup', 'opencart', 'openid', 'opera', 'paypal', 'pinterest', 'qq', 'quora', 'reddit', 'renren', 'scribd', 'skype', 'slideshare', 'snapchat', 'soundcloud', 'spotify', 'steam', 'telegram', 'tripadvisor', 'tumblr', 'twitch', 'twitter', 'vimeo', 'wechat', 'weibo', 'weixin', 'whatsapp', 'wikipedia', 'windows', 'wordpress', 'yahoo', 'yelp', 'youtube'];
                    var currentLink = $j(this);
                    $j.each(socialNetworks, function (i, sn) {
                        if (la.indexOf(sn) !== -1 && ajaxSupport) {
                            currentLink.html('<i class="fa fa-' + sn + '  d-flex justify-content-center align-items-center" aria-hidden="true"></i>');
                            currentLink.parent().replaceWith(currentLink);
                            return false;
                        }
                    });
                });

                $j('.LinkList a, .Text a, .Image a, .post-body a').each(function () {
                    var hashlink = $j(this).attr('href');
                    if( typeof hashlink !== typeof undefined && hashlink !== false ) {
                        if (hashlink.indexOf('#bt-tags') !== -1) {
                            $j(this).attr({'data-toggle': 'modal', 'data-target': '#bt-labels'});
                        } else if(hashlink.indexOf('#bt-home') !== -1){
                            $j(this).attr('href', blogurl);
                        }
                    }
                });

                $j('.widget.Label').each(function () {
                    var re = /^.*-BTLabels$/i;
                    var widgetTitle = $j(this).find('h2');
                    if (re.test(widgetTitle.text())) {
                        widgetTitle.text(widgetTitle.text().replace('-BTLabels', ''));
                        var list = $j(this).find('ul');
                        list.replaceWith('<hr class="title-separator"/><div class="btemplates-tags">' + list.html() + '</div>');
                        $j(this).find('li').each(function () {
                            var link = $j(this).find('a');
                            if (link.length)
                                var tag = link.eq(0).text();
                            else if ($j(this).find('span').length)
                                var tag = $j(this).find('span').eq(0).text();
                            btemplatesGetTagThumbJquery($j(this), tag);
                        });
                    }
                });


                function btemplatesJqueryGetPosts(el, postsToDisplay, postsType, postsThumbnailSize, postsStyle, exclude) {
                    postsToDisplay = parseInt(postsToDisplay);
                    postsStyle = typeof postsStyle !== 'undefined' ? postsStyle : 'list';
                    exclude = typeof exclude !== 'undefined' ? exclude : false;
                    postsToDisplay = exclude ? postsToDisplay + 1 : postsToDisplay;
                    var tag = tagName = '';
                    regex = /tag\:(.*?)$/i;
                    if (regex.exec(postsType)) {
                        var tagName = postsType.match(regex);
                        postsType = tagName[1];
                        tag = '/-/' + encodeURI(tagName[1]);
                    }
                    $j.get( blogurl + '/feeds/posts/default' + tag, { 'alt': 'json', 'max-results': postsToDisplay }, function(data){
                        if( typeof data === 'undefined' ){
                            console.log(data);
                            return data;
                        }
                        var code = btemplatesProcessPosts(data, postsToDisplay, postsThumbnailSize, postsStyle, postsType, exclude);
                        el.html(code);
                        if( postsStyle === 'video' )
                            $j('.post-body iframe, .post-body embed, .post-body object').wrap('<div class="video-container"></div>');
                    })
                }


                function btemplatesJqueryNextPosts(el, newerPostUrl, olderPostUrl, postsThumbnailSize) {
                    postsThumbnailSize = parseInt(postsThumbnailSize);
                    var startIndex = 1;
                    var foundPosts = 0;
                    $j.get(blogurl + '/feeds/posts/summary/', { 'alt':'json', 'max-results':'500', 'start-index':startIndex }, function(data){
                        for (var i = 0; i < data.feed.entry.length; i++) {
                            post = data.feed.entry[i];
                            for (var j = 0; j < post.link.length; j++) {
                                if (post.link[j].rel === 'alternate') {
                                    if (post.link[j].href !== newerPostUrl && post.link[j].href !== olderPostUrl)
                                        delete data.feed.entry[i];
                                    else
                                        foundPosts++;
                                }
                            }
                        }
                        if (foundPosts > 0) {
                            var code = btemplatesProcessPosts(data, 500, postsThumbnailSize);
                            el.html(code);
                        }
                    })
                }

                function btemplatesProcessPosts(json, postsToDisplay, postsThumbnailSize, postsStyle, postsType, exclude) {
                    if (typeof json.feed.entry === 'undefined')
                        return 'No posts found';
                    postsToDisplay = parseInt(postsToDisplay);
                    var postSummaryLength = 160;
                    var postThumbnailWidth = parseInt(postsThumbnailSize);
                    var postHTML = '';
                    var months = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];
                    var olderPostDate = Date.now();
                    for (var i = 0; i < postsToDisplay; i++) {
                        var post = postTitle = postDateTime = postDate = postYear = postMonth = postMonthName = postDay =
                                postUrl = postLabelsList = postCommentsCount = postThumbnail = postContent = postTags =
                                postSummary = postsThumbnailSquare = postAuthor = postAuthorAvatar = postId = postLocation = '';
                        post = json.feed.entry[i];
                        if (post === undefined)
                            continue;

                        postId = post.id.$t;
                        if (exclude && postId.indexOf(exclude) !== -1)
                            continue;

                        postTitle = post.title.$t != null ? post.title.$t : '';
                        postCommentsCount = post.thr$total;
                        postDateTime = post.published.$t;
                        if( new Date(olderPostDate) > new Date(postDateTime) )
                            olderPostDate = postDateTime;
                        olderPostDate = olderPostDate === null ? '' : olderPostDate;
                        olderPostDate = olderPostDate.replace( /\.\d{3}/, '' );
                        postDate = postDateTime.substring(0, 10);
                        postYear = postDate.substring(0, 4);
                        postMonth = postDate.substring(5, 7);
                        postMonthName = months[parseInt(postMonth) - 1];
                        postDay = postDate.substring(8, 10);
                        postDateStr = postDay + ' ' + postMonthName + ' ' + postYear;
                        postAuthor = post.author[0].name.$t;
                        postAuthorAvatar = ( 'gd$image' in post.author[0] ) ? post.author[0].gd$image.src : 'https://3.bp.blogspot.com/-qnvargRhquo/XSJ9VCaxZ4I/AAAAAAAABNU/f5c-lN4M9dIl3Wr87zT_guszgZY9RDe6gCLcBGAs/s35/user.png';
                        postLocation = ( 'georss$featurename' in post ) ? post.georss$featurename.$t : '';

                        for (var j = 0; j < post.link.length; j++) {
                            if (post.link[j].rel === 'alternate') {
                                postUrl = post.link[j].href;
                                break;
                            }
                        }
                        if ('category' in post) {
                            for (var c = 0; c < post.category.length; c++) {
                                var comma = (c === post.category.length - 1) ? '' : ', ';
                                postTags += post.category[c].term + comma;
                            }
                        }
                        if ('content' in post) {
                            postContent = post.content.$t;
                            postSummary = postContent.replace(/<\/?[^>]+(>|$)/g, "").substring(0, postSummaryLength) + '...';
                        } else {
                            postContent = postSummary = post.summary.$t;
                        }

                        var imagesRegex = /https?:\/\/[^\s\#\?]*\.(jpe?g|gif|png)/ig;
                        var images = postContent.match(imagesRegex);
                        if( images !== null && images.length > 0 ){
                            postThumbnail = images[0].replace(/(https?:\/\/[^\s\#\?]*\/)(s\d+|w\d+-h\d+|w\d+)(\/[^\s\#\?\/]*\.)(jpe?g|png|gif)/i, function(match, g1, g2, g3, g4){return g1+'w'+postThumbnailWidth+g3+g4});
                            postThumbnailSquare = postThumbnail.replace('/w'+postThumbnailWidth+'/', '/s'+postThumbnailWidth+'-c/');
                        } else if(post.media$thumbnail) {
                            var rawThumbnail = post.media$thumbnail;
                            var youTubePreviewRegex = /img\.youtube\.com\/vi\/.*\/default\.jpg/i;
                            if(youTubePreviewRegex.test(rawThumbnail.url)){
                                postThumbnail = postThumbnailSquare = rawThumbnail.url.replace('default.jpg', 'maxresdefault.jpg');
                            } else {
                                postThumbnail = rawThumbnail.url.replace('s72-c', 'w' + postThumbnailWidth);
                                postThumbnailSquare = rawThumbnail.url.replace('s72-c', 's' + postThumbnailWidth + '-c');
                            }
                        } else {
                            postThumbnail = 'https://1.bp.blogspot.com/-OoP4sWGVriY/XPBuyFZuqyI/AAAAAAAABGI/F3CU_cugs1ozET0Wl6ijZrNcvwJzupbcgCLcBGAs/w' + postThumbnailWidth + '/post-image.png';
                            postThumbnailSquare = 'https://1.bp.blogspot.com/-OoP4sWGVriY/XPBuyFZuqyI/AAAAAAAABGI/F3CU_cugs1ozET0Wl6ijZrNcvwJzupbcgCLcBGAs/s' + postThumbnailWidth + '-c/post-image.png';
                        }

                        if (postsStyle === 'slider') {
                            var active = (i === 0) ? ' active ' : '';
                            postHTML += '<div class="btemplates-post carousel-item' + active + '">' +
                                    '<img class="d-block w-100" src="' + postThumbnail + '" alt="' + postTitle + '"/>' +
                                    '<div class="carousel-caption d-none d-md-block">' +
                                    '<div class="bt-post-title">' +
                                    '<a href="' + postUrl + '"><h5>' +
                                    postTitle +
                                    '</h5></a>' +
                                    '</div>' +
                                    '<div class="bt-post-content">' +
                                    '<p><a href="' + postUrl + '">' +
                                    postSummary +
                                    '</a></p>' +
                                    '</div>' +
                                    '</div>' +
                                    '</div>';
                        } else if (postsStyle === 'testimonial') {
                            var active = i === 0 ? ' active ' : '';
                            postLocation = postLocation !== '' ? '<div class="bt-post-location d-none d-sm-block"><i class="fa fa-map-marker" aria-hidden="true"></i> '+postLocation+'</div>' : '';
                            postHTML += '<div class="btemplates-post carousel-item' + active + '">' +
                                    '<img class="rounded-circle mb-2" src="' + postThumbnailSquare + '" alt="' + postTitle + '"/>' +
                                    '<div class="caption d-block">' +
                                    '<div class="bt-post-title">' +
                                    '<a href="' + postUrl + '"><h5>' +
                                    postTitle +
                                    '</h5></a>' +
                                    '</div>' +
                                    '<div class="bt-post-content">' +
                                    '<p>' +
                                    postSummary +
                                    '</p>' +
                                    '</div>' +
                                    postLocation +
                                    '</div>' +
                                    '</div>';
                        } else if (postsStyle === 'menulist') {
                            var menuThumbnails = postsThumbnailSize === 0 ? '' : '<img src="' + postThumbnail + '" width="100%" alt="' + postTitle + '"/><br />';
                            postHTML += '<a class="dropdown-item" href="' + postUrl + '">' + menuThumbnails + postTitle + '</a>';
                        } else if (postsStyle === 'mosaic') {
                            postHTML += '<div class="col-md-6 col-lg-3">' +
                                    '<div class="item">' +
                                    '<a href="' + postUrl + '">' +
                                    '<img src="' + postThumbnailSquare + '" width="' + postThumbnailWidth + 'px" alt="' + postTitle + '"/>' +
                                    '</a>' +
                                    '<div class="item-title">' +
                                    '<span>' + postTags + '</span>' +
                                    '<a href="' + postUrl + '">' +
                                    '<h3>' + postTitle + '</h3>' +
                                    '</a>' +
                                    '</div>' +
                                    '</div>' +
                                    '</div>';
                        } else if(postsStyle === 'course'){
                            postLocation = postLocation !== '' ? '<div class="bt-post-location"><i class="fa fa-map-marker" aria-hidden="true"></i> '+postLocation+'</div>' : '';
                            postHTML += '<div class="col-12 col-sm-6 col-lg-4 mb-4"><div class="btemplates-post h-100">' +
                                    '<div class="bt-post-thumbnail">' +
                                    '<a href="' + postUrl + '">' +
                                    '<img src="' + postThumbnail + '" width="' + postThumbnailWidth + 'px" alt="' + postTitle + '"/>' +
                                    '</a>' +
                                    '</div>' +
                                    '<div class="bt-post-author-avatar">' +
                                    '<img class="rounded-circle border" alt="By '+postAuthor+'" title="By '+postAuthor+'" width="50px" src="'+postAuthorAvatar+'"/>' +
                                    '</div>' +
                                    '<div class="bt-post-title">' +
                                    '<a href="' + postUrl + '">' +
                                    postTitle +
                                    '</a>' +
                                    '</div><hr class="subtitle-separator"/>' +
                                    '<div class="bt-post-content">' +
                                    postSummary +
                                    '</div>' +
                                    postLocation +
                                    '<div class="bt-post-date">' +
                                    postDate +
                                    '</div>' +
                                    '</div></div>';
                        } else if(postsStyle === 'bloglist'){
                            postHTML += '<div class="col-12 col-sm-6 col-lg-4 mb-4"><div class="btemplates-post h-100">' +
                                    '<div class="bt-post-thumbnail">' +
                                    '<a href="' + postUrl + '">' +
                                    '<img src="' + postThumbnail + '" width="' + postThumbnailWidth + 'px" alt="' + postTitle + '"/>' +
                                    '</a>' +
                                    '</div>' +
                                    '<div class="bt-post-title">' +
                                    '<a href="' + postUrl + '">' +
                                    postTitle +
                                    '</a>' +
                                    '</div>' +
                                    '<div class="bt-post-date">' +
                                    postDateStr +
                                    '</div>' +
                                    '<hr class="subtitle-separator"/>' +
                                    '<div class="bt-post-content">' +
                                    postSummary +
                                    '</div>' +
                                    '</div></div>';
                        } else if(postsStyle === 'simplelist'){
                            postHTML += '<li class="row">' +
                             '<div class="col-1"><i class="fa fa-file-o" aria-hidden="true"></i></div>' +
                              '<div class="col-10"><a href="'+postUrl+'">'+postTitle+'</a></div>' +
                               '<div class="col-1"><a class="btn btn-light" href="'+postUrl+'" role="button"><i class="fa fa-chevron-right" aria-hidden="true"></i></a></div>' +
                                '</li>';
                        } else if( postsStyle === 'video' ){
                            postHTML += '<div class="bt-post-title"><a href="'+postUrl+'"><h3>'+postTitle+'</h3></a></div>';
                            var youtubeRegex = /((?:https?:)?\/\/)?((?:www|m)\.)?((?:youtube\.com|youtu.be))(\/(?:[\w\-]+\?v=|embed\/|v\/)?)([\w\-]+)(\S+)?/i
                            if( youtubeRegex.exec( postContent ) ) {
                                var youtubeUrlArray = postContent.match( youtubeRegex );
                                var youtubeUrl = 'https://www.youtube.com/embed/'+youtubeUrlArray[5];
                                postHTML += '<div class="video-container"><iframe src="'+youtubeUrl+'" frameborder="0" allowfullscreen></iframe></div>'
                                postHTML += '<div class="bt-post-content">' +
                                    '<a href="' + postUrl + '">' +
                                    postSummary +
                                    '</a>' +
                                    '</div>';
                            } else {
                                postHTML = '<div class="post-body">'+postContent+'</div>'
                            }
                        } else {
                            postHTML += '<div class="btemplates-post">' +
                                    '<div class="bt-post-thumbnail">' +
                                    '<a href="' + postUrl + '">' +
                                    '<img src="' + postThumbnail + '" width="' + postThumbnailWidth + 'px" alt="' + postTitle + '"/>' +
                                    '</a>' +
                                    '</div>' +
                                    '<div class="bt-post-title">' +
                                    '<a href="' + postUrl + '">' +
                                    postTitle +
                                    '</a>' +
                                    '</div>' +
                                    '<div class="bt-post-content">' +
                                    '<a href="' + postUrl + '">' +
                                    postSummary +
                                    '</a>' +
                                    '</div>' +
                                    '<div class="bt-post-date">' +
                                    postDate +
                                    '</div>' +
                                    '</div>';
                        }
                    }
                    nextPostsUrl = ( postsType !== 'latest' ) ?
                                    blogurl+'search/label/'+encodeURI(postsType)+'?update-max='+olderPostDate+'&max-results='+postsToDisplay :
                                    blogurl+'search?update-max='+olderPostDate+'&max-results='+postsToDisplay;
                    if (postsStyle === 'slider') {
                        var indicatorHTML = '';
                        for (var l = 0; l < postsToDisplay; l++) {
                            var active = l === 0 ? ' active ' : '';
                            indicatorHTML += '<li data-target="#btemplates-posts-slider" data-slide-to="' + l + '" class="' + active + '"></li>';
                        }
                        indicatorHTML = '<ol class="carousel-indicators">' + indicatorHTML + '</ol>';

                        postHTML = '<div id="btemplates-posts-slider" class="carousel slide" data-ride="carousel">' +
                                indicatorHTML +
                                '<div class="carousel-inner">' +
                                postHTML +
                                '</div>' +
                                '<a class="carousel-control-prev" href="#btemplates-posts-slider" role="button" data-slide="prev">' +
                                '<span class="carousel-control-prev-icon" aria-hidden="true"></span>' +
                                '<span class="sr-only">Previous</span>' +
                                '</a>' +
                                '<a class="carousel-control-next" href="#btemplates-posts-slider" role="button" data-slide="next">' +
                                '<span class="carousel-control-next-icon" aria-hidden="true"></span>' +
                                '<span class="sr-only">Next</span>' +
                                '</a>' +
                                '</div>';
                    } else if (postsStyle === 'testimonial') {
                        var indicatorHTML = '';
                        for (var l = 0; l < postsToDisplay; l++) {
                            var active = l === 0 ? ' active ' : '';
                            indicatorHTML += '<li data-target="#btemplates-posts-slider" data-slide-to="' + l + '" class="' + active + '"></li>';
                        }
                        indicatorHTML = '<ol class="carousel-indicators">' + indicatorHTML + '</ol>';

                        postHTML = '<hr class="title-separator"/><div id="btemplates-posts-slider" class="carousel slide" data-ride="carousel">' +
                                //indicatorHTML +
                                '<div class="carousel-inner">' +
                                postHTML +
                                '</div>' +
                                '<a class="carousel-control-prev" href="#btemplates-posts-slider" role="button" data-slide="prev">' +
                                '<span class="carousel-control-prev-icon" aria-hidden="true"></span>' +
                                '<span class="sr-only">Previous</span>' +
                                '</a>' +
                                '<a class="carousel-control-next" href="#btemplates-posts-slider" role="button" data-slide="next">' +
                                '<span class="carousel-control-next-icon" aria-hidden="true"></span>' +
                                '<span class="sr-only">Next</span>' +
                                '</a>' +
                                '</div>';
                    } else if (postsStyle === 'menulist') {
                        var menuId = postsType.toLowerCase().replace(/[^a-z0-9]/, '');
                        postHTML = '<a class="nav-link dropdown-toggle" href="#" id="' + menuId + '" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">' +
                                postsType +
                                '</a>' +
                                '<div class="dropdown-menu" aria-labelledby="' + menuId + '">' +
                                postHTML +
                                '</div>';
                    } else if (postsStyle === 'mosaic') {
                        postHTML = '<div class="btemplates-portfolio"><div class="row no-gutters">' + postHTML + '</div></div>';
                    } else if (postsStyle === 'course') {
                        postHTML = '<hr class="title-separator mb-4"/>' +
                         '<div class="btemplates-courses">' +
                          '<div class="row">' +
                         postHTML +
                         '</div>' +
                          '<div class="row justify-content-center">' +
                          '<div class="col-12 col-sm-6 col-lg-4">' +
                          '<a href="'+nextPostsUrl+'" class="btn btn-block btn-outline-info">' +
                           '<i class="fa fa-angle-double-right" aria-hidden="true"></i>' +
                            '</a>' +
                          '</div>' +
                          '</div>' +
                          '</div>';
                    } else if (postsStyle === 'bloglist') {
                        postHTML = '<hr class="title-separator mb-4"/>' +
                         '<div class="btemplates-blog">' +
                          '<div class="row">' +
                          postHTML +
                          '</div>' +
                          '<div class="row justify-content-center">' +
                          '<div class="col-12 col-sm-6 col-lg-4">' +
                          '<a href="'+nextPostsUrl+'" class="btn btn-block btn-outline-info">' +
                           '<i class="fa fa-angle-double-right" aria-hidden="true"></i>' +
                            '</a>' +
                          '</div>' +
                          '</div>' +
                           '</div>';
                    } else if (postsStyle === 'simplelist') {
                        postHTML = '<ul>'+postHTML+'</ul>';
                    } else if (postsStyle === 'video') {
                        postHTML = '<hr class="title-separator mb-4"/><div class="btemplates-videos">' + postHTML + '</div>';
                    } else {
console.log(postsStyle);
                    }

                    return postHTML;
                }

                function btemplatesJqueryGetComments(el, commentsToDisplay) {
                    commentsToDisplay = parseInt(commentsToDisplay);
                    $j.get( blogurl + '/feeds/comments/summary', { 'alt':'json', 'max-results':commentsToDisplay }, function(data) {
                        var code = btemplatesProcessComments(data, commentsToDisplay);
                        el.html(code);
                    });
                }

                function btemplatesProcessComments(json, commentsToDisplay) {
                    if (json.feed.entry === undefined)
                        return 'No comments found';
                    var commentHTML = '';
                    var months = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];

                    for (var i = 0; i < commentsToDisplay; i++) {
                        var comment = commentDateTime = commentDate = commentYear = commentMonth = commentMonthName =
                                commentDay = commentUrl = commentContent = commentSummary = commentAuthor =
                                        commentAuthorAvatar = postTitle = '';
                        comment = json.feed.entry[i];
                        if (comment === undefined)
                            continue;
                        commentDateTime = comment.published.$t;
                        commentDate = commentDateTime.substring(0, 10);
                        commentYear = commentDate.substring(0, 4);
                        commentMonth = commentDate.substring(5, 7);
                        commentMonthName = months[parseInt(commentMonth) - 1];
                        commentDay = commentDate.substring(8, 10);
                        commentAuthor = comment.author[0].name.$t;
                        for (var j = 0; j < comment.link.length; j++) {
                            if (comment.link[j].rel === 'alternate') {
                                commentUrl = comment.link[j].href;
                                break;
                            }
                        }
                        commentContent = commentSummary = comment.summary.$t;
                        commentAuthorAvatar = comment.author[0].gd$image.src;
                        if (commentAuthorAvatar.indexOf('blogblog.com/img/blank.gif') !== -1 ) {
                            commentAuthorAvatar = 'https://3.bp.blogspot.com/-qnvargRhquo/XSJ9VCaxZ4I/AAAAAAAABNU/f5c-lN4M9dIl3Wr87zT_guszgZY9RDe6gCLcBGAs/s100/user.png';
                        }
                        postTitle = comment.title.$t;

                        commentHTML += '<div class="btemplates-comment">' +
                                '<div class="bt-comment-avatar">' +
                                '<a href="' + commentUrl + '">' +
                                '<img class="profile-img rounded-circle border border-secondary" src="' + commentAuthorAvatar + '" alt="' + commentAuthor + '"/>' +
                                '</a>' +
                                '</div>' +
                                '<div class="bt-comment-author">' +
                                '<a href="' + commentUrl + '">' +
                                commentAuthor +
                                '</a>:' +
                                '<div class="bt-comment-content">' +
                                postTitle +
                                '</div>' +
                                '<div class="bt-comment-date">' +
                                '<a href="' + commentUrl + '">' +
                                commentDate +
                                '</a>' +
                                '</div>' +
                                '</div>';
                    }
                    return commentHTML;
                }


                linkListUl = $j('.navbar .section ul').each(function(){ $j(this).addClass('navbar-nav') });
                $j('.navbar .section li').each(function(i){
                    var navItemText = $j(this).children('a').text();
                    $j(this).addClass('nav-item align-self-lg-center');
                    $j(this).children('a').addClass('nav-link');
                    var re = /^-([^-]+)/i;
                    var resub = /^--([^-]+)/i;
                    var retag = /^(tag:[^-]+)-?(\d+)?-?(true|false)?/i;
                    if (re.exec(navItemText) && ajaxSupport) {
                        var previousNavItem = $j(this).prev();
                        if(previousNavItem.length){
                            var navItemLink = $j(this).children('a').attr('href');
                            var navItemNewText = navItemText.replace(/^-/i, '');
                            var nextNavItem = $j(this).next();
                            var nextNavItemText = nextNavItem.text();
                            var previousNavItemLink = previousNavItem.children('a').attr('href');
                            var previousNavItemText = previousNavItem.children('a').text();
                            var newLink = subitems = '';
                            while( resub.exec($j(this).next().text()) ) {
                                subitems += '<a class="dropdown-item" href="' + $j(this).next().children('a').attr('href') + '">' +
                                 '' + $j(this).next().text().replace('--', '') + '</a>';
                                $j(this).next().remove();
                            }
                            $j(this).remove();

                            if( resub.exec(nextNavItemText) ) {
                                newLink = '<div class="dropdown-submenu">' +
                                 '<a id="sub-dropdown-'+i+'" role="button" class="dropdown-item dropdown-toggle" ' +
                                  'data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" ' +
                                   'href="'+navItemLink+'">'+navItemNewText+'</a>' +
                                    '<div class="dropdown-menu" aria-labelledby="sub-dropdown-'+i+'">' +
                                     subitems +
                                     '</div>' +
                                      '</div>';
                            } else {
                                newLink = '<a class="dropdown-item" href="' + navItemLink + '">' + navItemNewText + '</a>';
                            }
                            if (previousNavItem.hasClass('dropdown')) {
                                var dropdownList = previousNavItem.find('.dropdown-menu').first();
                                dropdownList.append(newLink);
                            } else {
                                previousNavItem.className += ' ' + 'dropdown';
                                previousNavItem.addClass('dropdown');
                                previousNavItem.html('<a class="nav-link dropdown-toggle" href="' + previousNavItemLink +
                                        '" role="button" data-toggle="dropdown" id="dropdown-' + i + '" aria-haspopup="true" aria-expanded="false">' +
                                        previousNavItemText +
                                        '</a>' +
                                        '<div class="dropdown-menu" aria-labelledby="dropdown-' + i + '">' +
                                        newLink +
                                        '</div>');
                            }
                        }
                    } else if (retag.exec(navItemText) && ajaxSupport) {
                        var dropdownSettings = navItemText.match(retag);
                        var postsType = dropdownSettings[1];
                        var postsToDisplay = parseInt(dropdownSettings[2]);
                        var postsThumbnailSize = dropdownSettings[3] === 'true' ? 200 : 0;
                        $j(this).addClass('dropdown');
                        $j(this).children('a').html(postsType.replace(/tag:|-\d/, ''));
                        btemplatesJqueryGetPosts($j(this), postsToDisplay, postsType, postsThumbnailSize, 'menulist');
                    }
                });
                $j('#topMenu').removeClass('d-none');

                $j(function() {
                    $j("div.dropdown-menu [data-toggle='dropdown']").on("click", function(event) {
                        event.preventDefault();
                        event.stopPropagation();

                        $j(this).siblings().toggleClass("show");


                        if (!$j(this).next().hasClass('show')) {
                            $j(this).parents('.dropdown-menu').first().find('.show').removeClass("show");
                        }
                        $j(this).parents('li.nav-item.dropdown.show').on('hidden.bs.dropdown', function(e) {
                            $j('.dropdown-submenu .show').removeClass("show");
                        });

                    });
                });

                $j('.navbar-simple .section').each(function(){
                    if($j(this).find('.widget-content').length)
                        $j(this).html($j(this).find('.widget-content').html());
                });
                $j('.navbar-simple .section li').each(function(){
                    var navItemText = $j(this).children('a').text();
                    $j(this).addClass('nav-item');
                    $j(this).children('a').addClass('nav-link');
                });
                $j('.navbar-simple .section ul').each(function(){
                    $j(this).addClass('nav');
                });

                $j('.btemplates-dropdown nav, .btemplates-dropdown .navbar-simple').each(function(){
                    $j(this).removeClass('d-none');
                });


                $j('.HTML .widget-content').each(function(i){
                    var re = /^\s?(\d+)-(.*?)-(\d+)p?x?-?(list|slider|menulist|mosaic|course|testimonial|bloglist|video)?-?(\d*)?\s?$/i;
                    var commentsre = /(\d+)-comments/i;
                    if (re.exec($j(this).html()) && ajaxSupport) {
                        var postsSettings = $j(this).html().match(re);
                        var postsToDisplay = postsSettings[1];
                        var postsType = postsSettings[2];
                        var postsThumbnailSize = postsSettings[3];
                        var postsStyle = postsSettings[4] ? postsSettings[4] : 'list';
                        var postsExclude = postsSettings[5] ? postsSettings[5] : false;
                        $j(this).html('<img src="https://4.bp.blogspot.com/-VWY5-YJq0v4/XO4Y_HXklkI/AAAAAAAABE0/8G7P03z0YrgxKQx3cMrdagfB9K5GjkJ6ACLcBGAs/s1600/ajax-loader.gif" />');
                        btemplatesJqueryGetPosts($j(this), postsToDisplay, postsType, postsThumbnailSize, postsStyle, postsExclude);
                    } else if (commentsre.exec($j(this).html()) && ajaxSupport) {
                        var commentsSettings = $j(this).html().split('-');
                        var commentsToDisplay = parseInt(commentsSettings[0]);
                        $j(this).html('<img src="https://4.bp.blogspot.com/-VWY5-YJq0v4/XO4Y_HXklkI/AAAAAAAABE0/8G7P03z0YrgxKQx3cMrdagfB9K5GjkJ6ACLcBGAs/s1600/ajax-loader.gif" />');
                        btemplatesJqueryGetComments($j(this), commentsToDisplay);
                    }
                });

                $j('.post .post-body').each( function(i){
                    var re = /\[posts--(tag\:.*?)--(\d+)\]/i
                    if (re.exec($j(this).html()) && ajaxSupport) {
                        var postsSettings = $j(this).html().match(re);
                        var postsShortcode = postsSettings[0];
                        var postsTag = postsSettings[1];
                        var postsToDisplay = postsSettings[2];
                        var loading = '<div id="posts-list-tag" class="posts-list-tag"><img src="https://4.bp.blogspot.com/-VWY5-YJq0v4/XO4Y_HXklkI/AAAAAAAABE0/8G7P03z0YrgxKQx3cMrdagfB9K5GjkJ6ACLcBGAs/s1600/ajax-loader.gif" /></div>';
                        $j(this).html( $j(this).html().replace( postsShortcode, loading ) );
                        var postsContainerId = $j('#posts-list-tag');
                        btemplatesJqueryGetPosts( postsContainerId, postsToDisplay, postsTag, 0, 'simplelist' );
                    }
                });

                var newerPost = $j(".blog-pager-newer-link");
                var olderPost = $j(".blog-pager-older-link");
                if (newerPost.length || olderPost.length) {
                    newerPost = newerPost.length ? newerPost.attr('href') : '';
                    olderPost = olderPost.length ? olderPost.attr('href') : '';
                    btemplatesJqueryNextPosts($j('#blog-pager'), newerPost, olderPost, 400);
                }
                $j('body').on('click', '.btemplates-portfolio .item', function () {
                    window.location = $j(this).find('a').attr('href');
                });
                $j('#btemplates-search-icon').on('shown.bs.modal', function () {
                    $j('#btemplates-search .BlogSearch input[type="text"]').trigger('focus');
                });
                var btDate = new Date();
                $j('#this-year').text(btDate.getFullYear());

                $j(window).scroll(function () {
                    $j(this).scrollTop() > 400 ? $j("#back-top").fadeIn() : $j("#back-top").fadeOut()
                });
                $j("#back-top").click(function () {
                    return $j("body,html").animate({scrollTop: 0}, 800), !1
                });

                $j('#bt-subscription .FollowByEmail h2').after('<hr class="title-separator"/>');
            });
            //]]>
        </script>
    </body>
</html>