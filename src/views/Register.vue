<template>
  
 <div id="log">
    <div class="container  w-50">
      <div class="display-3">
        <h1> Masters </h1>
       </div>
    </div>

    <div class="container bg-light m-top w-50">
    <form  @submit.prevent="enterDetails">
  <div class="form-group">
    <label for="exampleFormControlSelect1">University</label>
    <select class="form-control" id="exampleFormControlSelect1">
      <option>Ycmou</option>
      <option>Ignou</option>
      <option>Pragathi</option>
      <option>IIt</option>
      <option>NIT</option>
    </select>
  </div>

  <div class="form-group">
    <label for="exampleFormControlSelect2">Program</label>
    <select class="form-control" id="exampleFormControlSelect2">
      <option>BBA</option>
      <option>BSC</option>
      <option>BCOM</option>
      <option>BARTS</option>
      <option>BED</option>
    </select>
  </div>


  <div class="form-group">
    <label for="exampleFormControlSelect3">Branch</label>
    <select class="form-control" id="exampleFormControlSelect3">
      <option>CHEMISTRY</option>
      <option>PHYSICS</option>
      <option>MATHS</option>
      <option>ARTS</option>
      <option>COMMERCE</option>
    </select>
  </div>


  <div class="form-group">
    <label for="exampleFormControlSelect4">BATCH</label>
    <select class="form-control" id="exampleFormControlSelect4">
      <option>JAN-DEC-2020</option>
      <option>JAN-DEC-2019</option>
      <option>JAN-DEC-2018</option>
      <option>JAN-DEC-2017</option>
      <option>JAN-DEC-2016</option>
    </select>
  </div>


  <div class="form-group">
    <label for="exampleFormControlSelect5">PART</label>
    <select class="form-control" id="exampleFormControlSelect5">
      <option>Fy</option>
      <option>Dy</option>
      <option>Ey</option>
      <option>My</option>
      <option>Ky</option>
    </select>
  </div>
<div class="form-group">
    <label for="exampleFormControlSelect5">TERM</label>
    <select class="form-control" id="exampleFormControlSelect5">
      <option>sem-1</option>
      <option>sem-2</option>
      <option>sem-3</option>
      <option>sem-4</option>
      <option>sem-5</option>
    </select>
  </div>

   <button type="submit" 
  value="Submit"
  class="btn btn-primary btn-block mt-2">Submit</button>

    </form>
    </div>
  </div>
</template>

<script>
export default {
 name:'App',

  data () {
   return {
     registration:{
        
     }
   }
      },
      methods : {
            enterDetails(){
             
            
      }
}
}
</script>

<style >

</style>


