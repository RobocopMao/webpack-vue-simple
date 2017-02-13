<template>
    <ul>
        <li v-for="nav of navs">
            {{nav.text}}
        </li>
    </ul>
</template>

<script>
    export default {
        name: 'nav',
        data () {
            return {
                navs: [
                    {text: 'HOME'},
                    {text: 'API'},
                    {text: 'ABOUT'}
                ]
            }
        }
    }
</script>