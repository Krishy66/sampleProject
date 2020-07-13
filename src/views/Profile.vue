<template>
  <div id="log">

    <div class="container  w-50 text-center">
      <div class="display-3">
        <h1> Program Details </h1>
       </div>
    </div>

    <div class="container bg-light m-top w-50">
    <form  @submit.prevent="enterDetails">

     <div class="form-group">
    <label for="mProgramName">Name</label>
    <input type="text" 
    class="form-control" 
    id="mProgramName" 
    v-model="programDetails.mProgramName"
    placeholder="Enter program Name">
    </div>

     <div class="form-group">
    <label for="mProgramCompleteName">Complete Name</label>
    <input type="text" 
    class="form-control" 
    id="mProgramCompleteName" 
     v-model="programDetails.mProgramCompleteName"
    placeholder="Enter Complete Program Name">
    </div>

    <div class="form-group">
    <label for="mProgramCode">Code</label>
    <input type="text" 
    class="form-control" 
    id="mProgramCode" 
     v-model="programDetails.mProgramCode"
    placeholder="Enter Program Code">
    </div>

<div class="form-group">
    <label for="exampleFormControlSelect1">University</label>
    <b-form-select class="form-control" id="exampleFormControlSelect1" :options=options  v-model="programDetails.mUniversityName">
      <template v-slot:first>
                <b-form-select-option
                  :value="null"
                  disabled
                >Please select the University</b-form-select-option>
              </template>
    </b-form-select>
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
            programDetails:{
                mProgramName:"",
                mProgramCompleteName:"",
                mProgramCode:"",
                mUniversityName:""
            },
            options:[
              "ycmou",
              "IGNOU",
              "IITD"
            ]
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