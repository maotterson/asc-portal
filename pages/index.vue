<template>
  <div>
    <Tutorial/>
    <form name="contact" method="POST" data-netlify="true">
      <label for="text-name">Name</label>
      <input type="text" name="name" id="text-name">
      <button type="submit">Submit</button>
    </form>
  </div>
</template>

<script>
export default {}
</script>
