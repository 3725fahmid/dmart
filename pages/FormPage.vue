<template>
    <div>
        <div class="container px-5">

        <select v-model="selected">
        <option disabled value="">Please select one</option>
        <option>A</option>
        <option>B</option>
        <option>C</option>
        </select>
        <span>Selected: {{ selected }}</span>
           <!-- <form class="ui large form" @submit.prevent="signInButtonPressed">
                <div class="field">
                    <div class="ui left icon input">
                    <i class="user icon"></i>
                    <input type="text" placeholder="Username or Email"/>
                    </div>
                </div>
                <div class="field">
                    <div class="ui left icon input">
                    <i class="lock icon"></i>
                    <input type="password" placeholder="Password"/>
                    </div>
                </div>
                <button class="ui fluid pink button big">SIGN IN</button>
            </form> -->
        </div>
    </div>
</template>
<script>
export default {
    name:'loginPage',
    data() {
        return {
            selected: ''
            // form: {
            //     email: '',
            //     password:''
            // }
        }
    },
    // methods: {
    //     signInButtonPressed() {
    //     console.log("sign in button is pressed");
    //     }
    // }
}
</script>
<style>
    #title{
  font-size: clamp(24px,10vw,46px);
}
form {
  width:400px;
  margin:20px auto;
}
</style>