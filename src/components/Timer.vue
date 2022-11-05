<template>
  <div class="timer">
    <div class="timer-container">
       <ul>
         <li>Pomodoro</li>
         <li>Short Break</li>
         <li>Long Break</li>
       </ul>
      <p class="time">30:00</p>
      <button>STOP</button>
    </div>
  </div>

  <div class="count-time">
    <p class="count">#x</p>
    <p>Time to focus</p>
  </div>
</template>

<script>

</script>

<style>
.timer {  
  width: 500px;
  margin: 80px auto 25px auto;
  background: rgba(236, 158, 155, 0.3);
  padding: 30px 0;
  border-radius: 3px;
}

.timer-container {
  width: 80%;
  height: 70%;
  margin: auto;
  display: flex; 
  flex-direction: column; 
  justify-content: space-between;
}

ul {
  list-style: none;
  display: flex;
  justify-content: space-around; 
  font-weight: bold;
  font-size: 16px;
  padding: 0;
}

.time {
  font-size: 120px;
  font-weight: bold;
  margin: 0 auto;
}

button {
  width: 200px;
  height: 55px;
  padding: 0 12px;
  font-size: 20px;
  font-weight: bold;
  border: none;
  border-radius: 3px;
  color: #ca5652;
  margin: 20px auto 0 auto;
  cursor: pointer;
}

.count-time {
  display: flex;
  flex-direction: column; 
  width: 300px;
  height: 50px;
  margin: 0 auto;
}

.count-time p {
  margin: 0;
  text-align: center;
}

.count {
  color: #f0a09d;
}
</style>