您当前使用的客户端为：<span style="color:#6600CC">移动端</span><br>
<br>
由于B站客服改版，现新版客服已经变为站内私信且暂时没有社区相关人工客服<br>
此页面将带你唤起旧版哔哩哔哩所使用的智齿客服页面<br>
<br>
<span style="color:red">注意：请不要泛滥本接口或页面地址，否则大量流量可能导致B站直接关停隐藏的相关服务，且行且珍惜！</span><br>
<span id="time">37</span>秒后跳转到客服界面
<a href = "https://service.bilibili.com/v2/chat/h5/index.html?sysNum=102d1b48515346ec8e9fb543b54ec454"> 等不及了，立即前往>> </a>

<script>
    //const Http = new XMLHttpRequest();
//const url='https://service.bilibili.com/v2/chat/h5/index.html?sysNum=102d1b48515346ec8e9fb543b54ec454';
//Http.open("GET", url);
//Http.send();

//Http.onreadystatechange = (e) => {
  //console.log(Http.responseText)
    //document.write(Http.responseText);
//}     

//$.ajax({
            //url: "https://service.bilibili.com/v2/chat/pc/index.html?sysNum=102d1b48515346ec8e9fb543b54ec454",
            //method: "GET",
            //success : function(data) { // ajax返回的数据
                //$("#iframe").attr("srcdoc",data);
            //}
        //});

var second=37;
    var time = document.getElementById("time");
    function show() {
        second--;
        if(second==0){
            //跳转页面
            location.href="https://service.bilibili.com/v2/chat/h5/index.html?sysNum=102d1b48515346ec8e9fb543b54ec454";
        }
        //用来动态设置里面的内容
        time.innerHTML=second+"";

    }
    //用来实现这个一秒实现一次这个方法
    setInterval(show,1000);
    
</script>

