<template>
  <div>
    <img src="@/assets/ddTitle.png" alt="Dub Dub" height="200">
    <p style="margin-left: 20px">&nbsp;&nbsp;&nbsp;&nbsp; My friends and I have been working on this game this semester. We created it to learn the skills of game development and to earn school credit whilst making something interesting.</p>

      <!--  Video of map -->
    <video style="width: 100%;" aspect-ratio="16/9" controls>
        <source :src='require("@/assets/videos/gameplay.mp4")' type="video/mp4" />
        Your browser does not support the video tag.
    </video>
    <video style="width: 100%;" aspect-ratio="16/9" controls>
        <source :src='require("@/assets/videos/mapShowcase.mp4")' type="video/mp4" />
        Your browser does not support the video tag.
    </video>
    <div class="features">
      <div>
        <h2 style="width: 100%; text-align: center;">Features</h2>
        <ul>
            <li>Basic AI</li>
            <li>Ruhzi(Gun)</li>
            <li>1x Map</li>
            <li>FPS Shooting</li>
            <li>Curve Based Recoil</li>
            <li>Inventory System</li>
        </ul>
      </div>
      <div>
        <h2>What's to come</h2>
        <ul>
            <li>Better AI</li>
            <li>New Title Screen</li>
            <li>Sound Effects</li>
            <li>More maps</li>
            <li>More guns</li>
            <li>AI Models</li>
            <li>Vehicles</li>
            <li>Weapon Attachments</li>
            <li>Multiplayer</li>
        </ul>
      </div>
    </div>
    <a href="/dubdub.zip" class="download">Download</a>
  </div>
</template>

<script>
export default {};
</script>
    
<style>
.features {
    display: flex;
    width: 100%;
    flex-direction: row;
    align-content: space-around;
    justify-content: space-around;
}
.download {
  background: rgb(71, 71, 71);
  width: 20vw;
  height: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 10px;
  text-decoration: none;
  color: #3cc3f0;
  margin: auto;
}
.download:hover{
  background: grey;
}
</style>