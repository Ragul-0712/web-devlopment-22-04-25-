<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Travel Booking UI</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="container">
    <div class="card search">
      <h2>Select your destination</h2>
      <input type="text" placeholder="From" />
      <input type="text" placeholder="To" />

      <div class="date-section">
        <div class="today">
          <p>Today</p>
          <h3>28</h3>
          <span>Dec, 2016</span>
        </div>
        <div class="calendar">
          <p>December 2016</p>
          <!-- You can replace this with a real calendar plugin -->
        </div>
      </div>

      <div class="seats">
        <label>Seats</label>
        <div class="seat-options">
          <button>1</button>
          <button>2</button>
          <button>3</button>
          <button class="active">4</button>
          <button>5</button>
          <button>6</button>
        </div>
      </div>

      <button class="proceed">Proceed</button>
    </div>

    <div class="card details">
      <h2>Travel Detail</h2>
      <div class="route">
        <div>BLR<br><small>Bangalore</small></div>
        <div class="icon">🚌</div>
        <div>PNY<br><small>Pondicherry</small></div>
      </div>
      <p class="date">29 Dec 2016</p>
      <div class="seats-info">Seats: <strong>3</strong></div>

      <div class="bus-option">
        <div class="info">
          <p><strong>YRL</strong></p>
          <p>10:30PM - 06:30AM</p>
          <p>Sleeper | AC</p>
          <p>12 Available Seats</p>
        </div>
        <div class="price">INR 1,400</div>
      </div>

      <button class="book">Book Now</button>
    </div>
  </div>
</body>
</html>


body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(to bottom right, #c2185b, #e91e63);
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }
  
  .container {
    display: flex;
    gap: 20px;
    padding: 20px;
  }
  
  .card {
    background: white;
    border-radius: 20px;
    padding: 20px;
    width: 300px;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
  }
  
  h2 {
    color: #c2185b;
    font-size: 18px;
    margin-bottom: 20px;
  }
  
  input[type="text"] {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
    border-radius: 8px;
    border: 1px solid #ccc;
  }
  
  .date-section {
    display: flex;
    justify-content: space-between;
    margin: 15px 0;
  }
  
  .today {
    text-align: center;
    color: #c2185b;
  }
  
  .seats {
    margin-bottom: 20px;
  }
  
  .seat-options button {
    margin: 5px;
    padding: 8px 12px;
    border: none;
    border-radius: 6px;
    background-color: #eee;
    cursor: pointer;
  }
  
  .seat-options .active {
    background-color: #c2185b;
    color: white;
  }
  
  .proceed, .book {
    width: 100%;
    background-color: #c2185b;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 25px;
    font-size: 16px;
    cursor: pointer;
  }
  
  .details .route {
    display: flex;
    justify-content: space-between;
    margin: 10px 0;
  }
  
  .details .icon {
    font-size: 24px;
    color: #c2185b;
  }
  
  .date {
    text-align: center;
    color: #c2185b;
  }
  
  .seats-info {
    margin: 10px 0;
    font-weight: bold;
  }
  
  .bus-option {
    background: #f9f9f9;
    padding: 10px;
    margin: 15px 0;
    border-radius: 10px;
    display: flex;
    justify-content: space-between;
  }
  
  .price {
    color: #c2185b;
    font-weight: bold;
  }
  






































