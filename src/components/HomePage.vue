<template>
      <article class="homePage">
          <div class="logoPage">      
            <img class="logoHome" alt="logo" src="../assets/logo2.png">
          </div>
          <div class="Block-content">
            <h1 class="Text-logo">"СОЗЕРЦАЯ СВЕРХДОХОДЫ"</h1>
            <div class="col-md-12">
              <div header-text="Modals" header-icon="fa fa-align-justify">
                <button type="button" class="btn btn-secondary loginButton " @click="showSmallModal()">
                  LOGIN
                </button>  
              </div>
            </div>
          </div>
      </article>

    
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.loginButton {
  color: #fff;
  background-color: #342d4c;
}

.homePage {
  background-color: #bfcadc;
}
</style>