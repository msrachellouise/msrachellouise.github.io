<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Tiny Search Thing</title>
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha256-k2WSCIexGzOj3Euiig+TlR8gA0EmPjuc79OEeY5L45g=" crossorigin="anonymous"></script>
    <!-- <script type="text/javascript" src="js/gtm.js"></script> If you use Google Tag Manager, uncomment this line-->
<style>
body {
  background-color: teal;
}
h2   {
	font-family: Tahoma, Geneva, sans-serif;
	size: 28px;
  color: white;
}
#search-box
{
	width:400px;
	height: 43px;
	margin:0 auto;
	border-radius: 40px;
	overflow: hidden;
}

.gsc-search-box .gsc-input
{
	border: 2px solid color: white;
	border-right-width: 0px;
	border-radius: 20px 2px 2px 20px;
	padding: 2px 12px !important;
}

#gsc-i-id1
{
	color:white;
}

button.gsc-search-button
{
	padding: 15px !important;
	background-color: green !important;
}
.gsc-control-cse
{
	padding:0px !important;
	border-width:0px !important;
}

form.gsc-search-box,table.gsc-search-box
{
	margin-bottom:0px !important;
}

.gsc-search-box .gsc-input
{
	padding:0px 4px 0px 6px !important;
}

#gsc-iw-id1
{
        height: auto !important;
        padding: 0px !important;
        border-width: 0px !important;
        box-shadow:none !important;
}

#gs_tti50
{
	padding:0px !important;
}

#gsc-i-id1
{
	height:33px !important;
	padding:0px !important;
	background:none !important;
	text-indent:0px !important;
}

.gsib_b
{
	display:none;
}

button.gsc-search-button
{
        display:block;
        width:13px !important;
        height:13px !important;
        border-width:0px !important;
        margin:0px !important;
        padding: 10px 6px 10px 13px !important;
        outline:none;
        cursor:pointer;
        box-shadow:none !important;
        box-sizing: content-box !important;
}

.gsc-branding
{
	display:none !important;
}

.gsc-control-cse,#gsc-iw-id1
{
	background-color:transparent !important;
}
</style>
<!-- <script type="text/javascript" src="js/options.js"></script> -->
</head>
<body>
<h2>Rachel's tiny search thingy</h2>

<!-- <script async src="js/scripttest.js"></script> -->


  <div id="search-box">
<script  integrity="sha256-k2WSCIexGzOj3Euiig+TlR8gA0EmPjuc79OEeY5L45g=" crossorigin="anonymous">
(function() {
var cx = "010391021890985609619:txywclsdsx4";
var gcse = document.createElement("script");
gcse.type = "text/javascript";
gcse.async = true;
gcse.src = "https://cse.google.com/cse.js?cx=" + cx;
var s = document.getElementsByTagName("script")[0];
s.parentNode.insertBefore(gcse, s);
})();
window.onload = function()
{
var searchBox =  document.getElementById("gsc-i-id1");
searchBox.placeholder="alma troubleshooting";
searchBox.title="Search Primo and Alma community documentation";
}
</script>
     <gcse:search></gcse:search>
  </div>
</body>
</html>
