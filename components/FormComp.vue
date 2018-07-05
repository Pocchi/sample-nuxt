<template lang="pug">
  .form
    h1 form
    form(name="contact" method="POST" netlify)
      input(type="hidden" name="form-name" value="contact")
      p
        label
          | Your Name:
          input(type="text" name="name")
      p
        label
          | email:
          input(type="email" name="email")
      p
        button(type="submit") send
</template>

<style>
input {
  border: 1px solid #ddd;
}
button {
  border: 1px solid #ddd;
  background: #ccc;
}
</style>
