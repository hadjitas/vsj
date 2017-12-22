<script>
//<![CDATA[
function getQueryParam(param) {
var result =  window.location.search.match(new RegExp("(\\?|&)" + param + "(\\[\\])?=([^&]*)")); return result ? result[3] : false;}
var topVideo = getQueryParam("s");
var playerElement = document.getElementById("player");
var player = new Clappr.Player({height: "100%", width: "100%", plugins: {'core': [LevelSelector]}, hlsjsConfig: {xhrSetup: function(xhr, url) {xhr.withCredentials = false;}}, playbackConfig: {crossorigin: 'use-credentials'}}); player.attachTo(playerElement);
player.load({source: topVideo, mimeType: 'application/x-mpegURL'});
player.play();
//]]>
</script>
