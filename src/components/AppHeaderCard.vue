<script>

export default {
  name: "AppHeaderCard",
};
</script>

<template>
  
    <div class="d-flex my-5">
      <div class="pc-icon d-flex justify-content-center align-items-center rounded-circle">
        <i class="fa-solid fa-desktop"></i>
      </div>
      <div class="marketing-list text-start ms-3 lh-3 gy-3">
        <h5>Online Marketing</h5>
        <p>it is a long enstablished fact that a reader will be distracted</p>
        <ul class="p-0 gy-3">
          <li class="gy-3">
            <i class="fa-solid fa-check"></i>
            <span>CEO</span>
          </li>
          <li class="gy-3">
            <i class="fa-solid fa-check"></i>
            <span>SEM</span>
          </li>
          <li class="gy-3">
            <i class="fa-solid fa-check"></i>
            <span>Website strategy</span>
          </li>
          <li class="gy-3">
            <i class="fa-solid fa-check"></i>
            <span>Social Management</span>
          </li>
        </ul>
      </div>
    </div>
  
</template>

<style scoped lang="scss">
.pc-icon{
    border: 5px solid white;
    box-shadow: 0 3px 10px rgba(20, 168, 253, 0.4);
    background-color: #377DFF;
    height: 47px;
    width: 47px;
    .fa-desktop{
      font-size: 14px;
      color: aliceblue;

    }   
} .fa-check{
      color: #377DFF;
    }
span{
  margin: 0 10px;
  color: black;
  font-weight: 400;
  line-height: 2;
}    
    
</style>
