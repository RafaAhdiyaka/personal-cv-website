<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h5>Hello, My Name is</h5>
    <h1 class="black">{{ msg }}</h1>
    <h4>
      Personal CV Website, Created using Vue JS.
    </h4>
    <h6>
       I am a 16 year old vocational highschool software engineering student interested in the field of design and implementation in a website. I am able to work well both in a team environment as well as using own initiative. 
    </h6>

    <hr>

    <div class="sub">
        <p>No Telepon: 081316332729 (Whatsapp)</p>
        <p>Email: rafaahdiyaka@gmail.com</p>
        <p>Github: RafaAhdiyaka</p>
        <p>Depok, Jawa Barat, Indonesia.</p>
    </div>
  </div>
</template>

<style>

.greetings h1 {
    color: #d85426;
}

.greetings h5{
    margin-top: 20px;
    font-weight: normal;
}
.greetings h4{
    margin-top: 15px;
}

.greetings h6 {
    margin-top: 20px;
}

.sub {
    margin-top: 25px;
    line-height: 13px;
}

</style>