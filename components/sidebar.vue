<!-- components/MessagesInterface.vue -->
<template>
  <div class="d-flex flex-column bg-dark text-light" style="width: 300px; height: 100vh;">
    <div class="d-flex justify-content-between align-items-center p-3 border-bottom border-secondary">
      <h5 class="mb-0">MESSAGES</h5>
      <i class="bi bi-gear"></i>
    </div>

    <div class="p-3">
      <div class="input-group mb-3">
        <span class="input-group-text bg-dark border-secondary">
          <i class="bi bi-search text-secondary"></i>
        </span>
        <input type="text" class="form-control bg-dark text-light border-secondary" placeholder="Search">
      </div>
    </div>

    <div class="px-3 py-2 border-top border-bottom border-secondary">
      <small class="text-white">Your Space</small>
    </div>

    <div class="p-3 border-bottom border-secondary">
      <div class="d-flex align-items-center">
        <i class="bi bi-bookmark me-3"></i>
        <div>
          <div>Saved Messages</div>
          <small class="text-white">Save messages secretly</small>
        </div>
      </div>
    </div>

    <div class="px-3 py-2 border-bottom border-secondary">
      <small class="text-white">All Messages</small>
    </div>

    <div class="p-3">
      <div class="d-flex align-items-center">
        <div class="rounded-circle p-2 me-3">
          <i class="bi bi-chat-fill text-white"></i>
        </div>
        <div>
          <div>adeli</div>
          <small class="text-white">You: WOI</small>
        </div>
        <small class="text-white ms-auto">7h ago</small>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
// No additional setup needed for this component
</script>

<style scoped>
/* You can add any component-specific styles here */
</style>