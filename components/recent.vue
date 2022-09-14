<template>
  <div class="recent">
    <div class="container f">
      <div class="mb-5">
        <h1 class="heading fw-bold">Recent Stories</h1>
        <button
          type="button"
          class="view-all btn btn-outline-secondary float-end"
        >
          View all
        </button>
      </div>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img
              src="@/assets/images/card/recentcard1.jpg"
              class="rounded"
              alt=""
              height="250px"
              weight="250px"
            />
            <div class="card-body">
              <span class="smallHeading">3D TUTORIAL</span>
              <h3 class="mb-5 title">
                Product Designer Guide: Salaries, Skills, Responsibilities and
                More
              </h3>
              <span> by Jasmine Andria</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img
              src="@/assets/images/card/recentcard2.jpg"
              alt=""
              class="rounded"
              height="250px"
            />
            <div class="card-body">
              <span class="smallHeading">SALARY GUIDE</span>
              <h3 class="mb-5 title">
                A Step-by-Step Guide to Exporting glTF Files From Blender
              </h3>
              <span> by Saikomi</span>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img
              src="@/assets/images/card/recentcard3.jpg"
              alt=""
              height="250px"
              class="rounded"
            />
            <div class="card-body">
              <span class="smallHeading">3D TUTORIAL</span>
              <h3 class="mb-5 title">
                How to Customize 3D Illustrations in Blender: Change Colors and
                Angles
              </h3>
              <span>by IconScout</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.recent {
  background: linear-gradient(180deg, #eceef5 0%, rgba(245, 246, 250, 0) 100%);
  margin-top: 231px;
}
.f {
  padding-top: 250px;
}

.heading {
  font-size: 36px;
}
.view-all {
  background: white;
  margin-top: -30px;
}
.card {
  border: none;
  overflow: hidden;
  height: auto;
}
.card img {
  display: block;
  object-fit: cover;
  object-position: center;
  transition: all 0.4s ease-out;
  border-radius: 12px;
  height: 250px;
  weight: 100px;
}
.card:hover img {
  transform: scale(1.2);
}
.smallHeading {
  color: #0073c2;
  margin-top: 30px;
  margin-bottom: 40px;
  font-size: 12px;
}

.title {
  font-size: 22px;
  margin-top: 20px;
}
.bgtext {
  padding: 100px;
}
.bgtext h1 {
  font-size: 48px;
}
.bgtext button {
  background: white;
  border: none;
}

</style>
