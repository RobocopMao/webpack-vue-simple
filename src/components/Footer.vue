<template>
    <div class="footer">{{msg}}</div>
</template>
<script>
    export default {
        name: 'footer',
        data () {
            return {
                msg: 'Copyright © 2014-2017 Evan You'
            }
        }
    }
</script>

<style>
    .footer {
        margin-top: 50px;
        color: #999;
    }
</style>