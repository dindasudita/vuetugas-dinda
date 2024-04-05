<template>
    <a href="#Contact">
      <button class="button-hover bnb">Contact Me</button>
    </a>
  </template>
  
  
  <style scoped>
  .button-hover {
    width: 160px;
    font-size: 16px;
    font-weight: 600;
    color: #fff;
    cursor: pointer;
    margin: 20px;
    height: 55px;
    text-align: center;
    border: none;
    background-size: 300% 100%;
    border-radius: 50px;
    transition: all 0.4s ease-in-out;
  }
  
  .button-hover:hover {
    background-position: 100% 0;
  }
  
  .button-hover:focus {
    outline: none;
  }
  
  .button-hover.bnb {
    background-image: linear-gradient(
      to right,
      #d66b39,
      #de8959,
      #e8b189,
      #f1d1b7
    );
    box-shadow: 0 4px 15px 0 rgba(252, 104, 110, 0.75);
  }
  </style>
  