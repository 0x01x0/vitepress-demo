<template>
  <h1>{{ $site.title }}</h1>
  <p>{{ $site.description }}</p>
  <Content />
</template>

<script>
export default {
  name: 'Layout'
}
</script>