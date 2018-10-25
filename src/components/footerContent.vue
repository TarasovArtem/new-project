<template>
    <div class="footerList">
        <p>&copy; HTML-CSS-JS.com</p>
        <address>Contact <a href="mailto:me@ HTML-CSS-JS.com">email</a></address>
    </div>
</template>

<script>
    
    export default {
        name: 'footerContent',
        props: {
            msg: String,
  },
};

</script>

<style scoped lang="scss">

.footerList {
    color: #fff;
    background-color: #342d4c;
}


</style>
