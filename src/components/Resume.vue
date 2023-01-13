<template>
    <div>
        <h2>EDUCATION</h2>
        <table class="table table-dark">
  <thead>
    <tr>
      <th scope="col">Year</th>
      <th scope="col">Organization</th>
      <th scope="col">Qualification</th>
    </tr>
  </thead>
  <tbody class="tbody" v-for="Ed in Resume" :key="Ed">
    <tr>
      <th scope="row">{{Ed.year }}</th>
      <td>{{Ed.name }}</td>
      <td>{{Ed.Qualifications}}</td>
    </tr>
  </tbody>
</table>
    <h2>WORK EXPERIENCE</h2>
    <table class="table table-dark">
  <thead>
    <tr>
      <th scope="col">Year</th>
      <th scope="col">Name</th>
      <th scope="col">Duration</th>
      <th scope="col">Duties</th>
    </tr>
  </thead>
  <tbody class="tbody" v-for="work in Workexperience" :key="work">
    <tr>
      <th scope="row">{{work.year }}</th>
      <td>{{work.name }}</td>
      <td>{{work.duration}}</td>
      <td>{{work.duties}}</td>
    </tr>
  </tbody>
</table>
    </div>
</template>
<script>
export default {
    name: 'Resume',
data() {
    return{
        Resume:[
            {year: 2014,
             name: "J.S Skenjana S.S.S",
             duration: "2012-2014",
             Qualifications: "Matric",
            },
            {year: 2015,
             name: "University of the Western Cape",
             duration: "2015-2020",
             Qualifications: "Bachelor of Commerce"
            },
            {year: 2022,
             name: "Life Choices Academy",
             duration: "Current",
             Qualifications: "Web developer"
            }
                ],
 Workexperience: [
                {year: 2018,
                 name: "Levi's",
                 duration: "6 months",
                 duties: "Sales person"
                },
                {year: 2019,
                 name: "IkamvaYouth",
                 duration: "6 months",
                 duties: "Tutor"
                },
                {year: 2021,
                 name: "ACDC Dynamics",
                 duration: "10 months",
                 duties: "Picker / Packer"
                }
    
            ]
        }
}
}



</script>
<style>
thead{
  border-bottom: 5px white solid;
}  
</style>