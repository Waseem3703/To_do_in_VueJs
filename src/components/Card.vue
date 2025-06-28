<script>
export default {
};
</script>

<template>
    <header>
     <div class="header">
      <h2>Save Your Task</h2>
      <button class="header-btn">Add ToDo</button>
     </div>
    </header>
    <main>
  <div class="card">
    <div class="card-header">
      <p class="card-title">Title</p>
      <button class="remove-btn">Remove</button>
    </div>
    <div class="card-body">
      <p>Description will show here</p>
    </div>
  </div>
  </main>
</template>

<style scoped>
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f4f6f8;
}
.card {
  background-color: #ffffff;
  border-radius: 12px;
  padding: 20px;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.06);
  transition: box-shadow 0.3s ease, transform 0.3s ease;

}
.card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.08);
}
.card-header{
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.card-title {
  font-weight: bold;
  font-size: 18px;
  margin: 0;
}

.remove-btn {
  padding: 12px 10px;
  font-size: 14px;
  background-color: crimson;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.remove-btn:hover {
  background-color: darkred;
}

.card-body {
  margin-top: 16px;
  color: #333;
}
main {
  max-width: 800px;
  margin: 40px auto;
  padding: 0 20px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: #353535;
  max-width: 900px;
  margin: 0 auto;
  background-color: transparent;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.231);
  border-radius: 50px;
  margin-top: 10px;
  padding: 0 25px

}

.header h2 {
  font-size: 26px;
  font-weight: 600;
}

.header-btn {
  border: none;
  background-color: #ffffff;
  color: rgba(32, 33, 36, 0.676);
  font-weight: 600;
  font-size: 15px;
  transition: all 0.2s ease;
  cursor: pointer;
  border-radius: 15px;
  padding: 8px;
}
.header-btn:hover{
  color: rgb(32, 33, 36);
  background-color: #d4d3d3;


}
</style>
