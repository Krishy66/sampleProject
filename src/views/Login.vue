<template>
  <div id="log">

    <div class="container  w-50">
      <div class="display-3">
        <h1> University </h1>
       </div>
    </div>

    <div class="container bg-light m-top w-50">
    <form  @submit.prevent="enterDetails">

     <div class="form-group">
    <label for="name">Name</label>
    <input type="text" 
    class="form-control" 
    id="name" 
    placeholder="Enter University Name">
    </div>

    <div class="form-group">
    <label for="code">Code</label>
    <input type="text" 
    class="form-control" 
    id="code" 
    placeholder="Enter University Code">
    </div>


    <div class="form-group">
    <label for="registrar">Registrar Name</label>
    <input type="text" 
    class="form-control" 
    id="registrar" 
    placeholder="Enter Registrar Name">
    </div>

<div class="row">

  <div class="col">

 <div class="form-group">
    <label for="std">Std-Code</label>
    <input type="number" 
    class="form-control" 
    id="code" 
    placeholder="Enter Std Code">
    </div>

  </div>

  <div class="col">

 <div class="form-group">
    <label for="number">Telephone Number</label>
    <input type="number" 
    class="form-control" 
    id="number" 
    placeholder="Enter Telephone Number">
    </div>

  </div>

</div>
    
   <div class="form-group">
    <label for="address">Address</label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
  </div>

<div class="row">

  <div class="col">

<div class="form-group">
    <label for="exampleFormControlSelect1">State</label>
    <select class="form-control" id="exampleFormControlSelect1">
      <option>Maharastra</option>
      <option>Andhra Pradesh</option>
      <option>Gujarat</option>
      <option>karnataka</option>
      <option>Assam</option>
    </select>
  </div>
</div>

<div class="col">

<div class="form-group">
    <label for="exampleFormControlSelect2">District</label>
    <select class="form-control" id="exampleFormControlSelect2">
      <option>Anantapur</option>
      <option>Nellore</option>
      <option>East</option>
      <option>West</option>
      <option>South</option>
    </select>
  </div>

</div>
</div>
  
  <div class="form-group">
    <label for="pin">Pin Code</label>
    <input type="number" 
    class="form-control" 
    id="pin" 
    placeholder="Enter Pin Code">
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
    data(){
        return{
            login:{
                email:"",
                password:""
            }
        }
    },
methods:{
  enterDetails:{
    
  }
}
}
</script>

<style >

</style>