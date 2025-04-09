import React from 'react';

const mobiles = [
  { name: "Samsung Galaxy S21", price: "$799", description: "Latest model, high performance." },
  { name: "iPhone 13", price: "$999", description: "Premium features with iOS." },
  { name: "Xiaomi Redmi Note 10", price: "$199", description: "Affordable with great features." }
];

function App() {
  return (
    <div className="App">
      <h1>Mobile Price and Specs</h1>
      <ul>
        {mobiles.map((mobile, index) => (
          <li key={index}>
            <h2>{mobile.name}</h2>
            <p>Price: {mobile.price}</p>
            <p>{mobile.description}</p>
          </li>
        ))}
      </ul>
    </div>
  );
}

export default App;# mobileprice
