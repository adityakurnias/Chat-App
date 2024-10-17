<template>
  <!-- components/UserDetails.vue -->
  <div class="bg-dark text-light p-3" style="width: 300px;">
    <div class="d-flex justify-content-between align-items-center mb-4">
      <h5 class="mb-0">User Details</h5>
      <button class="btn btn-close btn-close-white" aria-label="Close"></button>
    </div>

    <div class="text-center mb-4">
      <div class="rounded-circle bg-info mx-auto mb-3 d-flex align-items-center justify-content-center"
        style="width: 80px; height: 80px;">
        <!-- Placeholder for the user icon -->
        <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-person"
          viewBox="0 0 16 16">
          <path
            d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6m2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0m4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4m-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10s-3.516.68-4.168 1.332c-.678.678-.83 1.418-.832 1.664z" />
        </svg>
      </div>
      <h6>adeli</h6>
    </div>

    <div class="text-danger text-center mb-4" style="cursor: pointer;">
      Delete Conversation
    </div>

    <div>
      <h6 class="text-muted">Shared Photos</h6>
      <div class="bg-secondary bg-opacity-25 p-3 rounded">
        <p class="mb-0 text-muted">Nothing shared yet</p>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style></style>