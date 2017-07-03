<html lang="en">
<body>
<style>
@import url(https://fonts.googleapis.com/css?family=Roboto:400,500,700,300,100);

body {
  background-color: #3e94ec;
  font-family: "Roboto", helvetica, arial, sans-serif;
  font-size: 16px;
  font-weight: 400;
  text-rendering: optimizeLegibility;
}

div.table-title {
   display: block;
  margin: auto;
  max-width: 600px;
  padding:5px;
  width: 100%;
}

.table-title h3 {
   color: #fafafa;
   font-size: 30px;
   font-weight: 400;
   font-style:normal;
   font-family: "Roboto", helvetica, arial, sans-serif;
   text-shadow: -1px -1px 1px rgba(0, 0, 0, 0.1);
   text-transform:uppercase;
}
.table-fill {
  background: white;
  border-radius:3px;
  border-collapse: collapse;
  height: 320px;
  margin: auto;
  max-width: 600px;
  padding:5px;
  width: 100%;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
  animation: float 5s infinite;
}

th {
  color:#D5DDE5;;
  background:#1b1e24;
  border-bottom:4px solid #9ea7af;
  border-right: 1px solid #343a45;
  font-size:23px;
  font-weight: 100;
  padding:24px;
  text-align:left;
  text-shadow: 0 1px 1px rgba(0, 0, 0, 0.1);
  vertical-align:middle;
}

th:first-child {
  border-top-left-radius:3px;
}

th:last-child {
  border-top-right-radius:3px;
  border-right:none;
}

tr {
  border-top: 1px solid #C1C3D1;
  border-bottom-: 1px solid #C1C3D1;
  color:#666B85;
  font-size:16px;
  font-weight:normal;
  text-shadow: 0 1px 1px rgba(256, 256, 256, 0.1);
}

tr:hover td {
  background:#4E5066;
  color:#FFFFFF;
  border-top: 1px solid #22262e;
  border-bottom: 1px solid #22262e;
}

tr:first-child {
  border-top:none;
}

tr:last-child {
  border-bottom:none;
}

tr:nth-child(odd) td {
  background:#EBEBEB;
}

tr:nth-child(odd):hover td {
  background:#4E5066;
}

tr:last-child td:first-child {
  border-bottom-left-radius:3px;
}

tr:last-child td:last-child {
  border-bottom-right-radius:3px;
}

td {
  background:#FFFFFF;
  padding:20px;
  text-align:left;
  vertical-align:middle;
  font-weight:300;
  font-size:18px;
  text-shadow: -1px -1px 1px rgba(0, 0, 0, 0.1);
  border-right: 1px solid #C1C3D1;
}

td:last-child {
  border-right: 0px;
}

th.text-left {
  text-align: left;
}

th.text-center {
  text-align: center;
}

th.text-right {
  text-align: right;
}

td.text-left {
  text-align: left;
}

td.text-center {
  text-align: center;
}

td.text-right {
  text-align: right;
}
</style>
<table class="table-fill">
<thead>
<tr>
<th class="text-left"></th>
<th class="text-left">Name</th>
<th class="text-left">Designation</th>
<th class="text-left">Email-Id</th>  
</tr>
</thead>
<tbody class="table-hover">
<tr>
<td class="text-left"><img src="https://media.licdn.com/mpr/mpr/shrinknp_400_400/AAEAAQAAAAAAAAXoAAAAJGZiMDlmYjAzLTdiZTUtNDdlOS1hZWE0LTVhZGZhN2NhM2ZhOA.jpg" alt=""></td>
<td class="text-left">SR SRIDHAR</td>
<td class="text-left">Registrar</td>
<td class="text-left">Registrar@iiitb.ac.in</td>  
</tr>
<tr>
<td class="text-left"><img src="https://www.iiitb.ac.in/main-control/user_images/1472529878.jpg" alt=""></td>
<td class="text-left">Prof. Madhav Rao</td>  
<td class="text-left">iM.Tech Coordinator</td>
<td class="text-left">coordinator-imtech@iiitb.ac.in</td>
</tr>
<tr>
<td class="text-left"><img src="https://www.iiitb.ac.in/main-control/user_images/1486624837.JPG" alt=""></td>
<td class="text-left">Prof. Chandrashekar Ramanathan</td>
<td class="text-left">Dean(Academics)</td>
  <td class="text-left">dean-academics@iiitb.ac.in</td>
</tr>
<tr>
<td class="text-left"><img src="https://www.iiitb.ac.in/main-control/user_images/1486624800.JPG" alt=""></td>
<td class="text-left">Prof. Jyotsna Bapat</td>
<td class="text-left">Dean(Faculty)</td>
<td class="text-left">dean-faculty@iiitb.ac.in</td>
</tr>
<tr>
<td class="text-left"><img src="https://www.iiitb.ac.in/main-control/user_images/1486624712.JPG" alt=""></td>
<td class="text-left">Prof. Srinath Srinivasa</td>
<td class="text-left">Dean(R&D)</td>
<td class="text-left">dean-rd@iiitb.ac.in</td>
</tr>
</tbody>
</table>
</body>
