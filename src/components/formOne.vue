<template>
    <div>

        <form-Helper>
            <div slot="form-header">
               
                <h1> This is form ONE -REG  </h1>
                <p>This is some info about the form</p>
            </div>
            <div slot="form-fields">
                <input type="text" placeholder="name" required />
                <input type="password" placeholder="password" required />
                
            </div>
            <div slot="form-controls">
                <button v-on:click="handleSubmit">Submit</button>
            </div>

            <div slot="form-etc">
               <input type="text" placeholder="etc" required />
              
            </div>
        </form-Helper>
    </div>
</template>

<script>
import formHelper from './components/formHelper.vue'
export default {
    components: {
        'form-Helper':formHelper
    },
    data () {
        return {
        }
    },
    methods: {
    }
}
</script>


<style scoped>

</style>