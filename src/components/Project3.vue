<template>
  <div id="a">
    <div id="e" v-for="row in Project3" :key="row.id">
      <h1 class="e" v-for="row in Project3" :key="row.id">
        {{ row.nama }}<br />
        <font id="f">{{ row.nama1 }}</font>
      </h1>
      <img src="ilh.jpg" />
      <br /><br />
      <div id="i">
        <h1>
          {{ row.judul5 }}
          <hr color="black" size="1" />
        </h1>
        <div class="i">
          <p>
            <b>{{ row.isi14 }}</b
            ><br />{{ row.isi15 }}
          </p>
          <p>
            <b>{{ row.isi16 }}</b
            ><br />{{ row.isi17 }}
          </p>
          <p>
            <b>{{ row.isi18 }}</b
            ><br /><u>{{ row.isi19 }}</u>
          </p>
          <p>
            <b>{{ row.isi20 }}</b
            ><br /><u>{{ row.isi21 }}</u>
          </p>
        </div>
        <h1>
          {{ row.isi22 }}
          <hr color="black" size="1" />
        </h1>
        <div class="i">
          <p>{{ row.isi23 }}</p>
          <p>{{ row.isi24 }}</p>
          <p>{{ row.isi25 }}</p>
        </div>
        <h1>
          {{ row.isi26 }}
          <hr color="black" size="1" />
        </h1>
        <div class="i">
          <ul>
            <li>{{ row.isi27 }}</li>
            <li>{{ row.isi28 }}</li>
            <li>{{ row.isi29 }}</li>
            <li>{{ row.isi30 }}</li>
          </ul>
        </div>
      </div>
    </div>
    <div id="d" v-for="row in Project3" :key="row.id">
      <h1>{{ row.judul }}</h1>
      <hr />
      <p>
        {{ row.isi }}
      </p>
      <h1>{{ row.judul1 }}</h1>
      <hr />
      <ul>
        <div id="c">
          <div>
            <li>{{ row.list }}</li>
            <li>{{ row.list1 }}</li>
            <li>{{ row.list2 }}</li>
          </div>
          <div id="b">
            <li>{{ row.list3 }}</li>
            <li>{{ row.list4 }}</li>
            <li>{{ row.list5 }}</li>
          </div>
        </div>
      </ul>
      <h1>{{ row.judul2 }}</h1>
      <hr />
      <p>
        <b>{{ row.isi2 }}</b
        >{{ row.isi3 }}<br />
        <b>{{ row.isi4 }}</b
        >{{ row.isi5 }}
      </p>
      <ul>
        <li>
          {{ row.list6 }}
        </li>
        <li>{{ row.list7 }}<br />{{ row.list8 }}</li>
        <li>{{ row.list9 }}<br />{{ row.list10 }}</li>
        <li>{{ row.list11 }}<br />{{ row.list12 }}</li>
        <li>{{ row.list13 }}<br />{{ row.list14 }}</li>
      </ul>
      <h1>{{ row.judul3 }}</h1>
      <hr />
      <p>
        {{ row.isi6 }}<b>{{ row.isi7 }}</b
        >{{ row.isi8 }}<br /><b>{{ row.isi9 }}</b>
      </p>
      <h1>{{ row.judul4 }}</h1>
      <hr />
      <p>
        {{ row.isi10 }}<b>{{ row.isi11 }}}</b><br />{{ row.isi12
        }}<b>{{ row.isi13 }}</b>
      </p>
    </div>
  </div>
</template>
<script>
import axios from "axios";
export default {
  data() {
    return {
      Project3: [],
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get("http://localhost:3000/Project3")
        .then((res) => {
          this.Project3 = res.data;
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
  width: 790px;
}
.a {
  display: flex;
}
#b {
  margin-left: 50px;
}
.body {
  padding: 10px;
  width: 790px;
  height: auto;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  background-color: grey;
}
#c {
  display: flex;
  width: 790px;
}
#d {
  background-color: white;
  padding-left: 15px;
  width: 790px;
}
.d {
  width: 200px;
}
#e {
  background-color: silver;
  padding: 5px;
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
}
.i {
  font-size: 16px;
}
#l {
  border-radius: 500px;
}
.all {
  background-color: white;
  width: 400px;
  padding-bottom: 1px;
  font-family: "Courier New", Courier, monospace;
}
.bg {
  background-color: darkslateblue;
  height: 20px;
}
.res {
  background-color: darkslateblue;
  height: 1px;
  margin-left: 50px;
  width: 400px;
  font-family: "Courier New", Courier, monospace;
  color: white;
  font-size: 30px;
  text-align: center;
  padding-bottom: 28px;
}
.jud {
  background-color: darkslateblue;
  height: 150px;
  padding: 1px;
  font-family: "Courier New", Courier, monospace;
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
  width: 450px;
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
  font-family: "Courier New", Courier, monospace;
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
  font-family: "Courier New", Courier, monospace;
  color: white;
  font-size: 20px;
  text-align: center;
  padding-bottom: 20px;
}
#q {
  background-color: darkslateblue;
  height: 150px;
  font-family: "Courier New", Courier, monospace;
  color: white;
}
#r {
  padding-top: 30px;
  display: flex;
}
#t {
  width: 200px;
  padding: 20px;
  height: 200px;
  display: flex;
  border-radius: 100%;
  margin-left: 20px;
}
.eb {
  width: 500px;
  background-color: rgb(212, 209, 209);
}
.fb {
  width: 500px;
  background-color: rgb(212, 209, 209);
}
</style>