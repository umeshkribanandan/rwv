<template>
  <div>
    <h1>Uh-oh!</h1>
    <h3>
      It looks like you're experiencing some network issue, please click the
      back button and try again
    </h3>
    <router-link :to="{ name: 'event-list' }">Back to Home Page</router-link>
  </div>
</template>
