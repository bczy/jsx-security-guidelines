<script>
	const meme = { top: "XSS", bottom: "XSS EVERYWHERE"}
</script>

<div class="meme">
  <p class="top">{meme.top}</p>
  <p class="bottom">{meme.bottom}</p>
</div>

<style>
.meme {
  width: 450px;
	height: 250px;
  background-image: url('https://i.kym-cdn.com/entries/icons/original/000/002/868/XXEverywhere.jpg');
  background-size: 100%; 
  text-align: center;
  position: relative;
}

p {
  position: absolute; 
  left: 0;
  right: 0; 
  margin: 15px 0;
  font-size: 2.5em;
  color: white;
  -webkit-text-stroke: 1px black;
}

.bottom {
   bottom: 0;
 }

.top {
   top: 0;
 }
</style>