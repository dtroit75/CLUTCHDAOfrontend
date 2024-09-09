
This component will display the value of tokens issued against the collected plastic waste.

svelte
<script>
  let tokenValue = 0;
  let plasticCollected = 0;

  // Simulate fetching data from an API
  function fetchTokenData() {
    // Replace with actual API call
    tokenValue = 100; // Example value
    plasticCollected = 200; // Example value in kg
  }

  fetchTokenData();
</script>

<div>
  <h2>Token Value</h2>
  <p>Tokens Issued: {tokenValue}</p>
  <p>Plastic Waste Collected: {plasticCollected} kg</p>
</div>

<style>
  div {
    margin-top: 2rem;
  }
</style>

