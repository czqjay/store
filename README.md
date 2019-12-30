# store
var script = document.createElement("script");
script.setAttribute("type","text/javascript");
script.onload = function() {
    alert("done！");
$('div.info-list li[name]').each(function(i,el){ var n=  $(el).attr('name'); console.log( n,n>9000 || n == '9.5' || n =='18.5' );  n>9000 || n == '9.5' || n =='18.5' || n == '9.75' ?'':$(el).remove()  })
}
script.setAttribute("src","http://code.jquery.com/jquery-latest.js");
document.head.appendChild(script)





