<template>
  <div class="text-light d-flex flex-column" style="height: 100vh; width: 100%;">
    <!-- Header -->
    <div class="d-flex justify-content-between align-items-center p-3 border-bottom border-secondary">
      <div class="d-flex align-items-center">
        <div class="bg-info rounded-circle me-2"
          style="width: 40px; height: 40px; display: flex; justify-content: center; align-items: center;">
          <span style="font-size: 20px;">👤</span>
        </div>
        <span class="fs-5">adeli</span>
      </div>
      <div>
        <i class="bi bi-star me-3 text-secondary"></i>
        <i class="bi bi-house me-3 text-primary"></i>
        <i class="bi bi-info-circle text-primary"></i>
      </div>
    </div>

    <!-- Chat area -->
    <div class="flex-grow-1 p-3 overflow-auto" style="display: flex; flex-direction: column-reverse;">
      <div class="d-flex flex-column align-items-end">
        <div class="bg-primary rounded-pill px-3 py-2 mb-2 mw-75">WOI</div>
        <small class="text-muted">19h ago</small>
      </div>
      <div class="d-flex flex-column align-items-end mt-2">
        <div class="bg-primary rounded-pill px-3 py-2 mb-2 mw-75">Konto</div>
        <small class="text-muted">12m ago</small>
      </div>
      <div class="d-flex flex-column align-items-end mt-2">
        <div class="bg-primary rounded-pill px-3 py-2 mb-2 mw-75">😂😂😂😂😂</div>
        <small class="text-muted">12m ago</small>
      </div>
    </div>

    <!-- Input area -->
    <div class="p-3 border-top border-secondary">
      <div class="input-group">
        <button class="btn btn-outline-secondary" type="button">
          <i class="bi bi-plus-lg"></i>
        </button>
        <input type="text" class="form-control bg-dark text-light border-secondary" placeholder="Type a message..">
        <button class="btn btn-outline-secondary" type="button">
          <i class="bi bi-emoji-smile"></i>
        </button>
        <button class="btn btn-primary" type="button">
          <i class="bi bi-send-fill"></i>
        </button>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style>
.mw-75 {
  max-width: 75%;
}
</style>