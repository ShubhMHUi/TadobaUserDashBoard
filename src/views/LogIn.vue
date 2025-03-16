<script setup></script>

<template>
  <div class="login-section">
    <div class="login-section_left">
      <figure class="login-section_left-img">
        <img src="/assets/img/img1.jpg" loading="lazy" />
      </figure>
    </div>
    <div class="login-section_right">
      <figure class="login-section_right-img">
        <img src="/assets/img/logo-ttr.png" loading="lazy" alt="img" />
      </figure>
      <div class="login-section_right-input">
        <label class="labels">Email</label>
        <input type="email" placeholder="Enter your Email address" />
        <label class="labels">Password</label>

        <input type="password" placeholder="Enter your Password" />
        <a class="link" href="#">forgot password</a>

        <button class="btn">Log In</button>
        <button class="btn btn-outline">New Registration</button>
      </div>
    </div>
  </div>
</template>

<style lang="scss"></style>
