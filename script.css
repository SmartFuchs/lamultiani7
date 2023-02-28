// Set the date of the birthday
const birthday = new Date("2023-03-01");

// Get the countdown element
const countdown = document.getElementById("countdown");

// Update the countdown every second
setInterval(() => {
  // Get the current date and time
  const now = new Date();

  // Calculate the time difference between now and the birthday
  const diff = birthday.getTime() - now.getTime();

  // Calculate the days, hours, minutes, and seconds left
  const daysLeft = Math.floor(diff / (1000 * 60 * 60 * 24));
  const hoursLeft = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  const minutesLeft = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
  const secondsLeft = Math.floor((diff % (1000 * 60)) / 1000);

  // Update the countdown element with the time left
  countdown.innerHTML = `${daysLeft} days, ${hoursLeft} hours, ${minutesLeft} minutes, and ${secondsLeft} seconds left until the birthday!`;
}, 1000);
