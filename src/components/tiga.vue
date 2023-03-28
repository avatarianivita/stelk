<template>
<div>ini adalah component 3</div>
<div>{{providedAuthor}}</div>
</template>

<script>
export default {
  inject: ['providedAuthor']
};
</script>