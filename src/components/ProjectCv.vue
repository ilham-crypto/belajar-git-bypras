<template>
  <div id="z">
    <div id="x"></div>
    <div id="v" v-for="row in Projectcv" :key="row">{{ row.resume }}</div>
    <div id="q">
      <div id="r">
        <img
          id="t"
          src="https://i.pinimg.com/236x/80/98/9b/80989b43d668b7b544e58b8d69fd719b.jpg"
        />
        <h1 style="margin-left: 20px" v-for="row in Projectcv" :key="row">
          {{ row.nama }} <br />
          {{ row.nama1 }}
        </h1>
      </div>
    </div>
    <div class="ab">
      <div class="bb" v-for="row in Projectcv" :key="row">
        <h2>
          <br />
          {{ row.profile }}
          <hr style="border: 1px dashed black" />
        </h2>
        <div class="cb">
          <p>
            <b>{{ row.profile1 }}</b
            ><br />
            {{ row.profile2 }}
          </p>
          <p>
            <b>{{ row.profile3 }}</b
            ><br />
            {{ row.profile4 }}
          </p>
          <p>
            <b>{{ row.profile5 }}</b
            ><br />
            {{ row.profile6 }} <br />
            {{ row.profile7 }} <br />
            {{ row.profile8 }}<br />
            {{ row.profile9 }}
          </p>
          <p>
            <b>{{ row.profile26 }}</b
            ><br />
            {{ row.profile17 }}
          </p>
          <h2>
            {{ row.profile10 }}
            <hr style="border: 1px dashed black" />
          </h2>
          <p>
            {{ row.profile11 }}<br />
            {{ row.profile12 }}<br />
            {{ row.profile13 }}<br />
            {{ row.profile14 }}
          </p>
          <h2>
            {{ row.profile15 }}
            <hr style="border: 1px dashed black" />
          </h2>
          <p>
            <b>{{ row.profile16 }}<i class="fas fa-phone-square"></i> </b
            ><br />{{ row.profile17 }}
          </p>
          <p>
            <b>{{ row.profile18 }} <i class="fas fa-phone-square-alt"></i></b
            ><br />{{ row.profile19 }}
          </p>
          <p>
            <b>{{ row.profile20 }} <i class="bi bi-envelope-fill"></i></b
            ><br />{{ row.profile21 }}
          </p>
          <h2>
            {{ row.profile22 }}
            <hr style="border: 1px dashed black" />
          </h2>
          <p>
            <b>{{ row.profile23 }}<i class="fab fa-twitter-square"></i></b
            ><br />{{ row.profile17 }}
          </p>
          <p>
            <b>{{ row.profile24 }}<i class="fab fa-facebook-square"></i></b
            ><br />{{ row.profile25 }}
          </p>
        </div>
      </div>
      <div class="db" v-for="row in Projectcv" :key="row">
        <h2 style="margin-left: 13px">
          {{ row.isi }}
          <hr />
        </h2>
        <div class="eb">
          <h2 style="margin-left: 20px">
            <i class="fas fa-briefcase"></i> {{ row.isi1 }}
          </h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi2 }}</b
              ><br />{{ row.isi3 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ row.isi4 }}</b
                ><br />{{ row.isi5 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi2 }}</b
              ><br />{{ row.isi3 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ row.isi4 }}</b
                ><br />{{ row.isi5 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi2 }}</b
              ><br />{{ row.isi3 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ row.isi4 }}</b
                ><br />{{ row.isi5 }}
              </p>
            </div>
          </div>
        </div>
        <div class="fb">
          <h2 style="margin-left: 20px">
            <i class="fas fa-book"></i> {{ row.isi6 }}
          </h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi7 }}</b
              ><br />{{ row.isi8 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ row.isi9 }}</b
                ><br />{{ row.isi10 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi7 }}</b
              ><br />{{ row.isi8 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ row.isi9 }}</b
                ><br />{{ row.isi10 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ row.isi7 }}</b
              ><br />{{ row.isi8 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ row.isi9 }}</b
                ><br />{{ row.isi10 }}
              </p>
            </div>
          </div>
        </div>
        <div class="fb">
          <h2 style="margin-left: 20px">
            <i class="fas fa-lightbulb"></i> SKILLS
          </h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex">
            <div style="margin-left: 20px; margin-right: 20px">
              <p>
                <b>PROFESIONAL SKILLS</b><br />
                Microsoft Windows
                <i class="fas fa-circle"></i>
                <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="far fa-circle"></i><i class="far fa-circle"></i>
                <br />
                Windows
                <font style="margin-left: 72px">
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
                <br />
                Mac OSX
                <font style="margin-left: 72px">
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
                <br />
                Data Handling
                <font style="margin-left: 35px">
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
                <br />
                Record Keeeping
                <font style="margin-left: 8px"
                  >&nbsp;
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
                <br />
                Web Skills
                <font style="margin-left: 8px"
                  >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
              </p>
            </div>
            <div style="margin-left: 20px; margin-right: 20px">
              <p>
                <b>PERSONAL SKILLS</b><br />
                Organisation
                <font style="margin-left: 4px"
                  >&nbsp;&nbsp;&nbsp;
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i>
                </font>
                <br />
                Communication
                <font style="margin-left: 1px">
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
                <br />
                Time Keeping
                <font style="margin-left: 3px">
                  &nbsp;&nbsp;
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
                <br />
                Team Player
                <font style="margin-left: 6px">
                  &nbsp;&nbsp;&nbsp;&nbsp;
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
                <br />
                Commitment
                <font style="margin-left: 6px">
                  &nbsp;&nbsp;
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
                <br />
                Multitasking
                <font style="margin-left: 12px">
                  &nbsp;&nbsp;
                  <i class="fas fa-circle"></i>
                  <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                  ><i class="far fa-circle"></i><i class="far fa-circle"></i
                ></font>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import axios from "axios";
export default {
  data() {
    return {
      Projectcv: [],
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get("http://localhost:3000/Projectcv")
        .then((res) => {
          this.Projectcv = res.data;
        })
        .catch((err) => {
          console.log(err);
        });
    },
  },
};
</script>
<style>
#a {
  display: flex;
}
.a {
  display: flex;
}
#b {
  margin-left: 50px;
}
.body {
  padding: auto;
  margin-left: 190px;
  height: auto;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  background-color: grey;
}
#c {
  display: flex;
  width: 400px;
}
#d {
  background-color: white;
  padding-left: 15px;
  width: 400px;
}
.d {
  padding-left: 15px;
  width: 400px;
  font-size: 45px;
  font-family: "Courier New";
  margin-top: 14px;
  margin-left: 1px;
  font-size: 20px;
}
#e {
  margin-left: 200px;
  background-color: silver;
  padding: auto;
  height: auto;
}
.e {
  margin-left: 45px;
  font-family: sans-serif;
}
#f {
  color: tomato;
}
#i {
  margin-left: 60px;
  font-size: 11px;
  width: 198px;
}
.i {
  font-size: 16px;
}
.j {
  border: 1px solid black;
}
#l {
  border-radius: 500px;
}
.all {
  background-color: white;
  padding-bottom: 1px;
  font-family: "Courier New";
}
.bg {
  background-color: darkslateblue;
  height: 20px;
}
.res {
  background-color: darkslateblue;
  height: 1px;
  margin-left: 50px;
  width: 110px;
  font-family: "Courier New";
  color: white;
  font-size: 30px;
  text-align: center;
  padding-bottom: 28px;
}
.jud {
  background-color: darkslateblue;
  height: 150px;
  padding: 1px;
  font-family: "Courier New";
  color: white;
}
.gb {
  display: flex;
  padding-top: 30px;
}
.bn {
  margin-left: 15px;
}
.gm {
  width: 150px;
  height: 160px;
  border-radius: 500px;
  margin-left: 20px;
}
.p {
  margin-top: 14px;
  margin-left: 1px;
  font-size: 20px;
  width: 198px;
  text-align: right;
}
#lm {
  font-size: 25px;
  text-align: justify;
  margin-left: 50px;
  width: 400px;
  color: black;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.ab {
  display: flex;
  color: black;
}
.bb {
  text-align: right;
  width: 198px;
  padding-left: 10px;
  padding-right: 15px;
  padding-top: 65px;
  padding-bottom: 30px;
}
.cb {
  text-align: right;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.db {
  width: auto;
  padding-left: 10px;
  padding-right: 10px;
  text-align: justify;
  padding-top: 1px;
  padding-bottom: 100px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
#z {
  width: 790px;
  margin-left: 150px;
  padding-bottom: 20px;
  font-family: "Courier New";
  background-color: white;
}
#x {
  background-color: darkslateblue;
  height: 40px;
}
#v {
  background-color: darkslateblue;
  height: 2px;
  margin-left: 50px;
  width: 130px;
  font-family: "Courier New";
  color: white;
  font-size: 20px;
  text-align: center;
  padding-bottom: 20px;
}
#q {
  background-color: darkslateblue;
  height: 150px;
  font-family: "Courier New";
  color: white;
}
#r {
  padding-top: 30px;
  display: flex;
}
#t {
  width: 200px;
  height: 200px;
  display: flex;
  border-radius: 100%;
  margin-left: 20px;
}
.eb {
  width: auto;
  background-color: rgb(212, 209, 209);
}
.fb {
  width: auto;
  background-color: rgb(212, 209, 209);
}
</style>