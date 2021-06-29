#Three.js学び
##ICS
###入門編
1. 基本はcanvas要素。idを設定する。
2. JSはCDNで読み込むのが手軽
3. WebGL本体の処理は、ページの読み込み後に行う。
~~~
<script>
window.addEventListener('load', init);
function init(){
  // 処理
}
</script>
~~~