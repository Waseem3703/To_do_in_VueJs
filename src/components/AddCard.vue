<template>
    <div class="main">
  <div class="AddCard">
    <button class="close-btn">
      <i class="pi pi-times"></i>
    </button>

    <form class="form">
      <input type="text" placeholder="Enter Title Here" />
      <input type="text" placeholder="Enter Description Here" />
      <div class="actions">
        <button type="button" class="cancel">Cancel</button>
        <button type="submit" class="submit">Add</button>
      </div>
    </form>
  </div></div>
</template>

<script>
export default {
  name: "AddCard"
};
</script>

<style scoped>
@import "primeicons/primeicons.css";
.main{
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: -1;
    display: none;
}
.AddCard {
  padding: 20px;
  background-color: #e4e4e4;
  border-radius: 8px;
  width: 320px;
  position: relative;
}

.close-btn {
  position: absolute;
  top: 1px;
  right: 8px;
  border: none;
  background: transparent;
  font-size: 18px;
  cursor: pointer;
}

.form {
  display: flex;
  flex-direction: column;
  gap: 12px;
}

.form input {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 6px;
}

.actions {
  display: flex;
  justify-content: space-between;
  gap: 10px;
}

.cancel,
.submit {
  flex: 1;
  padding: 8px;
  border: none;
  border-radius: 6px;
  font-weight: 600;
  cursor: pointer;
}

.cancel {
  background-color: #aaa;
  color: white;
}

.submit {
  background-color: #007bff;
  color: white;
}
</style>
