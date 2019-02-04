<template>
  <aside class="sidebar">

    <label for="sidebar-search" class="sidebar-search-field">
      <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14">
        <path fill="rgba(255,255,255,0.8)" fill-rule="nonzero" d="M12.829 12.134l-3.33-3.36a4.77 4.77 0 0 0-3.728-7.745 4.77 4.77 0 1 0 0 9.54c1.142 0 2.186-.4 3.009-1.066l3.307 3.338a.51.51 0 0 0 .723.019.516.516 0 0 0 .019-.726zm-7.057-2.59c-1 0-1.942-.39-2.65-1.098A3.72 3.72 0 0 1 2.026 5.8c0-1 .39-1.942 1.098-2.646a3.723 3.723 0 0 1 2.649-1.097c1 0 1.942.39 2.65 1.097A3.72 3.72 0 0 1 9.517 5.8c0 1-.39 1.942-1.097 2.646a3.723 3.723 0 0 1-2.65 1.097z"/>
      </svg>
      <input type="text" id="sidebar-search" class="sidebar-search-input" placeholder="Search">
    </label>

    <span class="sidebar-label">Watch</span>

    <button class="sidebar-button active">
      <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18">
        <path fill="none" fill-rule="evenodd" stroke="rgba(255,255,255,0.8)" d="M9 17A8 8 0 1 1 9 1a8 8 0 0 1 0 16zM9 6.714A1.143 1.143 0 1 0 9 4.43a1.143 1.143 0 0 0 0 2.285zm-3.429 3.429a1.143 1.143 0 1 0 0-2.286 1.143 1.143 0 0 0 0 2.286zm6.858 0a1.143 1.143 0 1 0 0-2.286 1.143 1.143 0 0 0 0 2.286zM9 13.57a1.143 1.143 0 1 0 0-2.285 1.143 1.143 0 0 0 0 2.285zM16.429 17H9.57h6.858z"/>
      </svg>
      Movies
    </button>

    <button class="sidebar-button">
      <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18">
        <path fill="none" fill-rule="evenodd" stroke="rgba(255,255,255,0.8)" d="M9 17A8 8 0 1 1 9 1a8 8 0 0 1 0 16zM9 6.714A1.143 1.143 0 1 0 9 4.43a1.143 1.143 0 0 0 0 2.285zm-3.429 3.429a1.143 1.143 0 1 0 0-2.286 1.143 1.143 0 0 0 0 2.286zm6.858 0a1.143 1.143 0 1 0 0-2.286 1.143 1.143 0 0 0 0 2.286zM9 13.57a1.143 1.143 0 1 0 0-2.285 1.143 1.143 0 0 0 0 2.285zM16.429 17H9.57h6.858z"/>
      </svg>
      TV Shows
    </button>

    <button class="sidebar-button">
      <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18">
        <path fill="none" fill-rule="evenodd" stroke="rgba(255,255,255,0.8)" d="M9 17A8 8 0 1 1 9 1a8 8 0 0 1 0 16zM9 6.714A1.143 1.143 0 1 0 9 4.43a1.143 1.143 0 0 0 0 2.285zm-3.429 3.429a1.143 1.143 0 1 0 0-2.286 1.143 1.143 0 0 0 0 2.286zm6.858 0a1.143 1.143 0 1 0 0-2.286 1.143 1.143 0 0 0 0 2.286zM9 13.57a1.143 1.143 0 1 0 0-2.285 1.143 1.143 0 0 0 0 2.285zM16.429 17H9.57h6.858z"/>
      </svg>
      Anime
    </button>

    <div class="group bottom">
      <span class="sidebar-label">Continue watching</span>
    <div class="continue-watching-card">
      <div class="card-image"></div>
      <div class="card-info">
        <h5>Bohemian Rapsody</h5>
        <div class="progressbar">
          <div class="progress"></div>
        </div>
      </div>
    </div>
    </div>

    

    <!-- <ul class="list">
      <li class="movie-icon">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16">
          <path
            fill="none"
            fill-rule="evenodd"
            stroke="rgba(255,255,255,0.8)"
            d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0-9a1 1 0 1 0 0-2 1 1 0 0 0 0 2zM5 9a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm6 0a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm-3 3a1 1 0 1 0 0-2 1 1 0 0 0 0 2zm6.5 3h-6 6z"
          ></path>
        </svg>
        <a href>Movies</a>
      </li>
      <li>
        <a href>TV Shows</a>
      </li>
      <li>
        <a href>Anime</a>
      </li>
    </ul> -->
    <!-- <h4 class="list2">Favourites</h4>
    <ul class="list">
      <li>
        <a href>Continue wathing</a>
      </li>
      <li>
        <a href>Favourites</a>
      </li>
      <li>
        <a href>Your list</a>
      </li>
    </ul> -->
  </aside>
</template>

<script>
export default {
  name: "sidebar"
};
</script>

<style scoped>
.sidebar-search-field {
  padding: 0 12px;
  margin-bottom: 20px;
  position: relative;
  display: block;
  width: 100%;
  height: 24px;
}

.sidebar-search-field svg {
  position: absolute;
  left: 18px;
  top: 50%;
  transform: translateY(-50%);
}

.sidebar-search-field .sidebar-search-input {
  position: relative;
  background: rgba(255, 255, 255, 0.1);
  color: #fff;
  border: none;
  border-radius: 4px;
  padding: 2px;
  padding-left: 24px;
  font-size: 13px;
  width: 100%;
  height: 100%;
  box-shadow: rgba(255, 255, 255, 0.2) 0 -0.6pt 0 inset, 
  rgba(255, 255, 255, 0.2) -0.2pt 0 0 inset,
  rgba(255, 255, 255, 0.2) 0 0.2pt 0 inset,
  rgba(255, 255, 255, 0.1) 0.2pt 0 0 inset,
  rgba(0, 0, 0, 0.2) 0 1px 2px inset;
}

.sidebar-search-input::placeholder {
  color: rgba(255, 255, 255, 0.4);
}

.sidebar-search-input:focus {
  outline: none;
  /* box-shadow: 0 0 0 2pt lightskyblue; */
}

.sidebar-label {
  display: block;
  padding: 2px 22px 8px 22px;
  font-size: 12px;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 0.4);
}

.sidebar-button {
  padding: 0 22px;
  position: relative;
  width: 100%;
  height: 32px;

  display: flex;
  align-items: center;

  border: none;
  background: transparent;
  color: inherit;
  text-align: left;
  font-size: 13px;
}
.sidebar-button svg { 
  margin-right: 8px;
}
.sidebar-button.active {
  background: rgba(0, 0, 0, 0.8);
}
.sidebar-button:focus {
  outline: none;
}

.group.bottom {
  position: absolute;
  bottom: 24px;
}

.continue-watching-card {
  margin: 0 12px;
  padding: 4px;
  display: flex;
  background: rgba(255, 255, 255, 0.1);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 6px;
  width: 100%;
}

.continue-watching-card .card-image {
  width: 60px;
  height: 60px;
  background: rgba(0, 0, 0, 0.2);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 6px;
  background: url(https://m.media-amazon.com/images/M/MV5BNDg2NjIxMDUyNF5BMl5BanBnXkFtZTgwMzEzNTE1NTM@._V1_SY1000_CR0,0,629,1000_AL_.jpg) no-repeat center;
  background-size: cover;
}

.continue-watching-card .card-info {
  padding: 8px 6px 0 6px;
}

.continue-watching-card .card-info span {
  font-size: 10px;
  text-transform: uppercase;
}

.continue-watching-card .card-info h5 {
  margin: 0;
  font-size: 13px;
  font-weight: normal;
  width: 90px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.continue-watching-card .card-info p {
  margin: 0;
  margin-top: 6px;
}

ul {
  margin: 0;
  padding: 0;
  list-style: none;
}
a {
  color: inherit;
  text-decoration: none;
}
h4 {
  margin: 0;
  padding-bottom: 6px;
  font-size: 10px;
}
.sidebar {
  position: relative;
  min-width: 220px;
  height: 100%;
  padding-top: 28px;
  /* padding-left: 12px;
  padding-right: 12px; */
  font-size: 13px;
  /* background: #303033; */
  color: rgba(255, 255, 255, 0.9);
}

.list {
  /* padding-left: 6px; */
}

.list li {
  /* padding: 4px; */
}

.list2 {
  padding-top: 40px;
}

.search {
  position: relative;
  background: transparent;
  color: #fff;
  border: 1px solid #3a3a3a;
  border-radius: 4px;
  padding: 2px;
  padding-left: 12px;
  font-size: 13px;
  box-shadow: rgba(255, 255, 255, 0.4) 0px -1px 0px inset;
  width: 100%;
}

.search::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 20px;
  height: 20px;
  background: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Cpath d='M443.5 420.2L336.7 312.4c20.9-26.2 33.5-59.4 33.5-95.5 0-84.5-68.5-153-153.1-153S64 132.5 64 217s68.5 153 153.1 153c36.6 0 70.1-12.8 96.5-34.2l106.1 107.1c3.2 3.4 7.6 5.1 11.9 5.1 4.1 0 8.2-1.5 11.3-4.5 6.6-6.3 6.8-16.7.6-23.3zm-226.4-83.1c-32.1 0-62.3-12.5-85-35.2-22.7-22.7-35.2-52.9-35.2-84.9 0-32.1 12.5-62.3 35.2-84.9 22.7-22.7 52.9-35.2 85-35.2s62.3 12.5 85 35.2c22.7 22.7 35.2 52.9 35.2 84.9 0 32.1-12.5 62.3-35.2 84.9-22.7 22.7-52.9 35.2-85 35.2z' fill='#fff' /%3E%3C/svg%3E")
    no-repeat center;
}

.movie-icon {
  padding: 0 8px;
  position: relative;
  /* background: gray; */
  height: 28px;
  display: flex;
  align-items: center;
}

.movie-icon a {
  padding-left: 8px;
}

/* .movie-icon::before {
  content: '';
  position: absolute;
  width: 24px;
  height: 24px;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 512 512'%3E%3Cpath d='M447.9 80H64.1C46.5 80 32 94.5 32 112.1v287.7c0 17.7 14.5 32.1 32.1 32.1h383.7c17.7 0 32.1-14.5 32.1-32.1V112.1c.1-17.6-14.4-32.1-32-32.1zM120 400c0 4.4-3.6 8-8 8H64c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v48zm0-80c0 4.4-3.6 8-8 8H64c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v48zm0-80c0 4.4-3.6 8-8 8H64c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v48zm0-80c0 4.4-3.6 8-8 8H64c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v48zm232 108H160c-6.6 0-12-5.4-12-12s5.4-12 12-12h192c6.6 0 12 5.4 12 12s-5.4 12-12 12zm104 132c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v48zm0-80c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v48zm0-80c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v48zm0-80c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v48z' fill='%23fff'/%3E%3C/svg%3E");
} */

.progressbar {
  position: relative;
  margin-top: 14px;
  width: 100%;
  height: 4px;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 4px;
  overflow: hidden;
}

.progress {
  position: absolute;
  top: 0;
  left: 0;
  width: 80%;
  height: 100%;
  background: #d41d00;
}
</style>

