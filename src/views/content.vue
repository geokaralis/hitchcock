<template>
  <div class="content">

    <div class="controls">
         <label>
  <select name="pets">
    <optgroup label="Sort by">
      <option value="dog">Trending</option>
      <option value="cat">Popularity</option>
      <option value="hamster" disabled>Last added</option>
      <option value="hamster" >Title</option>
      <option value="hamster" >Year</option>
      <option value="hamster" >Rating</option>
    </optgroup>
    <optgroup label="Flying pets">
      <option value="parrot">Parrot</option>
      <option value="macaw">Macaw</option>
      <option value="albatross">Albatross</option>
    </optgroup>
  </select>
</label>
 <label>
  <select name="pets">
    <optgroup label="Genre">
      <option value="dog">All genres</option>
      <option value="cat">Action</option>
      <option value="hamster" disabled>Last added</option>
      <option value="hamster" >Title</option>
      <option value="hamster" >Year</option>
      <option value="hamster" >Rating</option>
    </optgroup>
    <optgroup label="Flying pets">
      <option value="parrot">Parrot</option>
      <option value="macaw">Macaw</option>
      <option value="albatross">Albatross</option>
    </optgroup>
  </select>
</label>

<button class="top-button time">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50" width="18px" height="18px">
    <path style="line-height:normal;text-indent:0;text-align:start;text-decoration-line:none;text-decoration-style:solid;text-decoration-color:#000;text-transform:none;block-progression:tb;isolation:auto;mix-blend-mode:normal" d="M 25 2 C 12.309295 2 2 12.309295 2 25 C 2 37.690705 12.309295 48 25 48 C 37.690705 48 48 37.690705 48 25 C 48 12.309295 37.690705 2 25 2 z M 25 4 C 36.609824 4 46 13.390176 46 25 C 46 36.609824 36.609824 46 25 46 C 13.390176 46 4 36.609824 4 25 C 4 13.390176 13.390176 4 25 4 z M 24.984375 6.9863281 A 1.0001 1.0001 0 0 0 24 8 L 24 22.173828 A 3 3 0 0 0 22 25 A 3 3 0 0 0 22.294922 26.291016 L 16.292969 32.292969 A 1.0001 1.0001 0 1 0 17.707031 33.707031 L 23.708984 27.705078 A 3 3 0 0 0 25 28 A 3 3 0 0 0 28 25 A 3 3 0 0 0 26 22.175781 L 26 8 A 1.0001 1.0001 0 0 0 24.984375 6.9863281 z"  fill="#fff" font-weight="400" font-family="sans-serif" white-space="normal" overflow="visible"/>
</svg>

</button>

<button class="top-button">
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 50 50" version="1.1" width="18px" height="18px">
<g id="surface1">
<path fill="rgba(255,255,255,0.4)" style=" " d="M 22.78125 0 C 21.605469 -0.00390625 20.40625 0.164063 19.21875 0.53125 C 12.902344 2.492188 9.289063 9.269531 11.25 15.59375 L 11.25 15.65625 C 11.507813 16.367188 12.199219 18.617188 12.625 20 L 9 20 C 7.355469 20 6 21.355469 6 23 L 6 47 C 6 48.644531 7.355469 50 9 50 L 41 50 C 42.644531 50 44 48.644531 44 47 L 44 23 C 44 21.355469 42.644531 20 41 20 L 14.75 20 C 14.441406 19.007813 13.511719 16.074219 13.125 15 L 13.15625 15 C 11.519531 9.722656 14.5 4.109375 19.78125 2.46875 C 25.050781 0.832031 30.695313 3.796875 32.34375 9.0625 C 32.34375 9.066406 32.34375 9.089844 32.34375 9.09375 C 32.570313 9.886719 33.65625 13.40625 33.65625 13.40625 C 33.746094 13.765625 34.027344 14.050781 34.386719 14.136719 C 34.75 14.226563 35.128906 14.109375 35.375 13.832031 C 35.621094 13.550781 35.695313 13.160156 35.5625 12.8125 C 35.5625 12.8125 34.433594 9.171875 34.25 8.53125 L 34.25 8.5 C 32.78125 3.761719 28.601563 0.542969 23.9375 0.0625 C 23.550781 0.0234375 23.171875 0 22.78125 0 Z M 9 22 L 41 22 C 41.554688 22 42 22.445313 42 23 L 42 47 C 42 47.554688 41.554688 48 41 48 L 9 48 C 8.445313 48 8 47.554688 8 47 L 8 23 C 8 22.445313 8.445313 22 9 22 Z M 25 30 C 23.300781 30 22 31.300781 22 33 C 22 33.898438 22.398438 34.6875 23 35.1875 L 23 38 C 23 39.101563 23.898438 40 25 40 C 26.101563 40 27 39.101563 27 38 L 27 35.1875 C 27.601563 34.6875 28 33.898438 28 33 C 28 31.300781 26.699219 30 25 30 Z "/>
</g>
</svg>
</button>
    </div>
 

    <!-- <div class="empty-state">
<svg width="400px" height="240px" viewBox="0 0 400 240" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <title>Artboard</title>
    <desc>Created with Sketch.</desc>
    <g id="Artboard" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
        <polygon id="Star" stroke="#D8D8D8" fill-rule="nonzero" points="200 160 152.97718 184.72136 161.957739 132.36068 123.915479 95.2786405 176.48859 87.6393202 200 40 223.51141 87.6393202 276.084521 95.2786405 238.042261 132.36068 247.02282 184.72136"></polygon>
        <circle id="Oval" fill="#D8D8D8" fill-rule="nonzero" cx="175" cy="107" r="3"></circle>
        <circle id="Oval-Copy" fill="#D8D8D8" fill-rule="nonzero" cx="224" cy="109" r="3"></circle>
        <path d="M195,138 C195,136 196.833333,135 200.5,135 C204.166667,135 206,136 206,138" id="Path" stroke="#D8D8D8" fill-rule="nonzero"></path>
        <circle id="Oval" fill="#D8D8D8" fill-rule="nonzero" cx="97" cy="175" r="3"></circle>
        <circle id="Oval-Copy-2" fill="#D8D8D8" fill-rule="nonzero" cx="112" cy="150" r="3"></circle>
        <circle id="Oval-Copy-3" fill="#D8D8D8" fill-rule="nonzero" cx="91" cy="120" r="3"></circle>
        <circle id="Oval-Copy-4" fill="#D8D8D8" fill-rule="nonzero" cx="138" cy="69" r="3"></circle>
        <circle id="Oval-Copy-5" fill="#D8D8D8" fill-rule="nonzero" cx="285" cy="172" r="3"></circle>
        <circle id="Oval-Copy-6" fill="#D8D8D8" fill-rule="nonzero" cx="277" cy="141" r="3"></circle>
        <circle id="Oval-Copy-7" fill="#D8D8D8" fill-rule="nonzero" cx="300" cy="120" r="3"></circle>
        <circle id="Oval-Copy-8" fill="#D8D8D8" fill-rule="nonzero" cx="255" cy="59" r="3"></circle>
        <ellipse id="Oval" fill="#313134" fill-rule="nonzero" cx="200" cy="197" rx="36" ry="3"></ellipse>
        <path d="M106.245339,82.5598798 L104.18054,83.4523886 C103.673587,83.6715185 103.084981,83.4381923 102.865852,82.9312401 C102.756409,82.6780474 102.756409,82.3908934 102.865852,82.1377007 L103.75836,80.0729008 L102.865852,78.0081009 C102.646722,77.5011487 102.880048,76.9125428 103.387,76.693413 C103.640193,76.5839705 103.927347,76.5839705 104.18054,76.693413 L106.245339,77.5859218 L108.310139,76.693413 C108.817092,76.4742831 109.405697,76.7076092 109.624827,77.2145614 C109.73427,77.4677541 109.73427,77.7549082 109.624827,78.0081009 L108.732318,80.0729008 L109.624827,82.1377007 C109.843957,82.6446529 109.610631,83.2332587 109.103679,83.4523886 C108.850486,83.561831 108.563332,83.561831 108.310139,83.4523886 L106.245339,82.5598798 Z" id="Star" fill="#54545A" fill-rule="nonzero" transform="translate(106.072901, 80.072901) rotate(-45.000000) translate(-106.072901, -80.072901) "></path>
        <path d="M268.245339,82.5598798 L266.18054,83.4523886 C265.673587,83.6715185 265.084981,83.4381923 264.865852,82.9312401 C264.756409,82.6780474 264.756409,82.3908934 264.865852,82.1377007 L265.75836,80.0729008 L264.865852,78.0081009 C264.646722,77.5011487 264.880048,76.9125428 265.387,76.693413 C265.640193,76.5839705 265.927347,76.5839705 266.18054,76.693413 L268.245339,77.5859218 L270.310139,76.693413 C270.817092,76.4742831 271.405697,76.7076092 271.624827,77.2145614 C271.73427,77.4677541 271.73427,77.7549082 271.624827,78.0081009 L270.732318,80.0729008 L271.624827,82.1377007 C271.843957,82.6446529 271.610631,83.2332587 271.103679,83.4523886 C270.850486,83.561831 270.563332,83.561831 270.310139,83.4523886 L268.245339,82.5598798 Z" id="Star-Copy" fill="#54545A" fill-rule="nonzero" transform="translate(268.072901, 80.072901) rotate(-45.000000) translate(-268.072901, -80.072901) "></path>
        <path d="M233.245339,48.5598798 L231.18054,49.4523886 C230.673587,49.6715185 230.084981,49.4381923 229.865852,48.9312401 C229.756409,48.6780474 229.756409,48.3908934 229.865852,48.1377007 L230.75836,46.0729008 L229.865852,44.0081009 C229.646722,43.5011487 229.880048,42.9125428 230.387,42.693413 C230.640193,42.5839705 230.927347,42.5839705 231.18054,42.693413 L233.245339,43.5859218 L235.310139,42.693413 C235.817092,42.4742831 236.405697,42.7076092 236.624827,43.2145614 C236.73427,43.4677541 236.73427,43.7549082 236.624827,44.0081009 L235.732318,46.0729008 L236.624827,48.1377007 C236.843957,48.6446529 236.610631,49.2332587 236.103679,49.4523886 C235.850486,49.561831 235.563332,49.561831 235.310139,49.4523886 L233.245339,48.5598798 Z" id="Star-Copy-2" fill="#54545A" fill-rule="nonzero" transform="translate(233.072901, 46.072901) rotate(-45.000000) translate(-233.072901, -46.072901) "></path>
        <path d="M264.245339,168.55988 L262.18054,169.452389 C261.673587,169.671518 261.084981,169.438192 260.865852,168.93124 C260.756409,168.678047 260.756409,168.390893 260.865852,168.137701 L261.75836,166.072901 L260.865852,164.008101 C260.646722,163.501149 260.880048,162.912543 261.387,162.693413 C261.640193,162.583971 261.927347,162.583971 262.18054,162.693413 L264.245339,163.585922 L266.310139,162.693413 C266.817092,162.474283 267.405697,162.707609 267.624827,163.214561 C267.73427,163.467754 267.73427,163.754908 267.624827,164.008101 L266.732318,166.072901 L267.624827,168.137701 C267.843957,168.644653 267.610631,169.233259 267.103679,169.452389 C266.850486,169.561831 266.563332,169.561831 266.310139,169.452389 L264.245339,168.55988 Z" id="Star-Copy-3" fill="#54545A" fill-rule="nonzero" transform="translate(264.072901, 166.072901) rotate(-45.000000) translate(-264.072901, -166.072901) "></path>
        <path d="M135.245339,165.55988 L133.18054,166.452389 C132.673587,166.671518 132.084981,166.438192 131.865852,165.93124 C131.756409,165.678047 131.756409,165.390893 131.865852,165.137701 L132.75836,163.072901 L131.865852,161.008101 C131.646722,160.501149 131.880048,159.912543 132.387,159.693413 C132.640193,159.583971 132.927347,159.583971 133.18054,159.693413 L135.245339,160.585922 L137.310139,159.693413 C137.817092,159.474283 138.405697,159.707609 138.624827,160.214561 C138.73427,160.467754 138.73427,160.754908 138.624827,161.008101 L137.732318,163.072901 L138.624827,165.137701 C138.843957,165.644653 138.610631,166.233259 138.103679,166.452389 C137.850486,166.561831 137.563332,166.561831 137.310139,166.452389 L135.245339,165.55988 Z" id="Star-Copy-4" fill="#54545A" fill-rule="nonzero" transform="translate(135.072901, 163.072901) rotate(-45.000000) translate(-135.072901, -163.072901) "></path>
    </g>
</svg>
    </div> -->

<div class="details">
  <button class="close-button" @click="close">Close</button>
</div>

    <div class="movies-container">
      <div class="movie-item" @click="click"></div>
    </div>
    
  </div>
</template>

<script>

export default {
  name: 'content-view',
  methods: {
    click() {
      var datailsView = document.querySelector('.details');
      datailsView.classList.add('show');
    },
    close() {
      var datailsView = document.querySelector('.details');
      datailsView.classList.remove('show');
    }
  }
}
</script>

<style scoped>
.close-button {
  position: absolute;
  left: 12px;
  bottom: 24px;
  /* background: rgba(255, 255, 255, 0.25); */
  background: transparent;
  border: 1pt solid rgba(255, 255, 255, 0.1);
  /* box-shadow: rgba(255, 255, 255, 0.2) 0 0.6pt 0 inset; */
  border-radius: 4px;
  color: #fff;
  font-size: 13px;
}
.controls {
  padding-top: 28px;
  padding-left: 12px;
  padding-right: 12px;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 56px;
  /* background: linear-gradient(to top, #333436, #3D4042);
  border-bottom: 1px solid #000; */
  display: flex;
  align-items: flex-end;
  justify-content: flex-end;
}
.empty-state {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.content {
  position: relative;
  width: 100%;
  padding-top: 24px;
  padding-left: 12px;
  background: #1f1f21;
  color: #fff;
  font-size: 13px;
  overflow-y: scroll;
}

.movies-container {
  padding-top: 24px;
}

.movie-item {
  width: 180px;
  height: 260px;
  background: rgba(0, 0, 0, 0.5) url(https://image.tmdb.org/t/p/w1280/gbmkFWdtihe1VfydTDsieQ6VfGL.jpg) no-repeat center;
  background-size: cover;
  border-radius: 6px;
}

select {
  margin-right: 4px;
  height: 24px;
  background: rgba(255, 255, 255, 0.25);
  border: 0.2pt solid rgba(0, 0, 0, 1);
  box-shadow: rgba(255, 255, 255, 0.2) 0 0.6pt 0 inset;
  color: #fff;
  font-size: 13px;
}

.top-button {
  margin-right: 4px;
  width: 24px;
  height: 24px;
  background: transparent;
  border: none;
   /* background: rgba(255, 255, 255, 0.25);
  border: 0.2pt solid rgba(0, 0, 0, 1);
  box-shadow: rgba(255, 255, 255, 0.2) 0 0.6pt 0 inset; */
  border-radius: 4px;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0;
}

.details {
  position: fixed;
  right: 0;
  top: 0;
  width: 400px;
  height: 100%;
  background: #262629;
  transform: translate3d(100%, 0, 0);
  transition: all 0.4s ease-in-out;
  box-shadow: rgba(0, 0, 0, 0.4) 0 0 8px;
}

.details.show {
  transform: translate3d(0, 0, 0);
}
</style>


