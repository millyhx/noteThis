<template>
<img src="../assets/noteThisLogo.png" />
<h1> Sign Up</h1>
<div class="register">
    <input type="text" placeholder="Enter Name" />
    <input type="text" placeholder="Enter Email" />
    <input type="password" placeholder="Enter Password" />
    <button>Sign Up</button>
</div>

</template>

<script>
export default {
    name: 'signUp'
}
</script>


<style>
.register input {
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid black;
    border-radius: 20px;
}

.register button {
    width: 320px;
    height: 40px;
    background-color: skyblue;
    color: black;
    cursor: pointer;
    border: 0px;
    border-radius: 20px;
}
</style>