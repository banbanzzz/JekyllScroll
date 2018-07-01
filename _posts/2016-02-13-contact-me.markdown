---
layout: post
title: 联系
date: 2016-02-13 02:34:03.000000000 +08:00
---
班级：16软件开发C班<br>
2016030403133<br>
翁修杰<br>
[GitHub](https://github.com/banbanzzz)<br>
<h1>
<a href="https://github.com/banbanzzz" target="blank" class="fa fa-github"></a>

 <style>
    #wt{
     color: #fff;
    background: white;
    top: 50px;
    left: 200px;
    width: 450px;
    height: 300px;
    box-shadow: -1px 1px 8px rgba(0, 0, 0, 0.4);
    border-radius: 10px;
    position: relative;
    border-radius: 10px;
    margin: 20 auto;
    padding: 0px;
	visibility:hidden;
	}
</style>

 <input type="image" src="assets/images/wc.png" onclick="display()" >
 <div id="wt" >
<img id="wc" src="assets/images/me.png" style="height: 200px;width:200px; position: relative; top: 30px; left: 120px;display:none;" target="blank">
<button id="zz" style="background-color: black; color: white; font-weight: bold; border-radius: 4px; width: 60px; height: 40px;top:60px;left:-30px; position: relative;display:none;" onclick="zclose()">close</button>
 </div>
 </h1>
<script>
function display(){
	wt=document.getElementById('wt');
	wt.style.visibility='visible';
	img=document.getElementById('wc');
	button=document.getElementById('zz');
	img.style.display='';
	button.style.display='';
}
function zclose(){
	wt=document.getElementById('wt');
	wt.style.visibility='hidden';
	img=document.getElementById('wc');
	button=document.getElementById('zz');
	img.style.display='none';
	zz.style.display='none';
}
</script>
