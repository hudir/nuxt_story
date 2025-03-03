<script setup>
const story = await useStoryblok('home', { version: 'draft' });
await console.log(story)
</script>
 
<template>
  <StoryblokComponent v-if="story" :blok="story.content" />
</template>