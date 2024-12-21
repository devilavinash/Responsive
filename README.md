**Code of Home CSS **

.help{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 50px;
  background-color: #5B9FB8;
  padding: 0px 180px;
}
.help p{
    color: #fff;
    font-weight: 600;
    font-size: 13px;
}
.help a{
  text-decoration: none;
  color: #fff;
  width: 200px;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
}
.help a img{
  width: 20px;
  height: 20px;
}
.game-container{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  height: auto;
  padding: 20px 100px;
}
.game-container-top{
  width: 80%;
  height: 150px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0px 100px;
}
.open-play, .jantri, .cross{
  width: 200px;
  height: 80px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  font-weight: 700;
  background-color:#EAF6F8;
  cursor: pointer;
}
.open-play.active{
  background-color: #5F9DC1;
}
.jantri.active{
  background-color: #5F9DC1;
}
.cross.active{
  background-color: #5F9DC1;
}
.game-container-bottom{
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 80%;
  height: auto;
}
.open-play-container{
    display: none;
}
.jantri-play-container{
    display: none;
}
.cross-play-container{
    display: none;
}
.open-play-container.active{
  display: initial;
  width: 100%;
  height: auto;
}
.jantri-play-container.active{
  display: initial;
  width: 100%;
  height: auto;
}
.cross-play-container.active{
  display: initial;
  width: 100%;
  height: auto;
}
.open-play-container form{
  width: 100%;
  display: flex; 
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 10px;
}
.custom-select{
  padding: 10px 20px;
  -webkit-appearance: none;
  -moz-appearance: none;  
  appearance: none;  
  outline: none;
  border: none;
  width: 90%;
  height: 100%;
  font-size: 18px;
  font-weight: 500;
  color: #029d02;
  background-color: #EAF6F8;
}
.game-select-container{
  position: relative;
  width: 100%;
  height: 60px;
  display: flex;
  justify-content: left;
  align-items: center;
  border: 1.5px solid #54AAA4;
  background-color: #EAF6F8;
  padding: 0px 20px;
}
.game-select-container i{
  font-size: 18px;
}

.with-palti{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 50px;
}
.with-palti-number{
  display: flex;
  justify-content: left;
  align-items: center;
  width: 53%;
  height: 100%;
  border: 1.5px solid #54AAA4;
  padding: 0 5px;
}
.with-palti-checkbox{
  width: 14%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  border: 1.5px solid #54AAA4;
  gap: 5px;
}
.equalto{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 8%;
  height: 100%;
  font-size: 20px;
  font-weight: 700;
}
.equalto i{
  color: #000;
}
.with-palti-ammount{
  display: flex;
  justify-content: left;
  align-items: center;
  width: 25%;
  height: 100%;
  border: 1.5px solid #54AAA4;
  padding: 0 5px;
}
.with-palti-number input{
  outline: none;
  border: none;
  font-size: 17px;
  width: 100%;
  height: 100%;
}
.with-palti-ammount input{
  outline: none;
  border: none;
  font-size: 15px;
  width: 100%;
  height: 100%;
}
.with-palti-checkbox p{
  font-size: 13px;
  font-weight: 600;
}

.with-palti-circular-checkbox {
  position: relative;
  display: inline-block;
  width: 18px;
  height: 18px;
}

.with-palti-circular-checkbox input {
  position: absolute;
  opacity: 0;
  cursor: pointer;
}
.with-palti-circular-checkbox span {
  position: absolute;
  color: #fff;
  font-size: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 1px solid #000; /* Border color */
  border-radius: 50%;
  background-color: #fff;
  transition: background-color 0.3s ease, border-color 0.3s ease;
}

.with-palti-circular-checkbox input:checked + span {
  background-color: #029d02;
  color: #fff;
}
/*harup*/
.harup{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 50px;
}
.harup-number{
  display: flex;
  justify-content: left;
  align-items: center;
  width: 53%;
  height: 100%;
  border: 1.5px solid #54AAA4;
  padding: 0 5px;
}
.harup-checkbox{
  width: 14%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  border: 1.5px solid #54AAA4;
  gap: 0px;
}
.harup-a-checkbox{
  width: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.harup-b-checkbox{
  width: 50%;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}

.harup-ammount{
  display: flex;
  justify-content: left;
  align-items: center;
  width: 25%;
  height: 100%;
  border: 1.5px solid #54AAA4;
  padding: 0 5px;
}
.harup-number input{
  outline: none;
  border: none;
  font-size: 17px;
  width: 100%;
  height: 100%;
}
.harup-ammount input{
  outline: none;
  border: none;
  font-size: 15px;
  width: 100%;
  height: 100%;
}
.harup-checkbox p{
  font-size: 13px;
  font-weight: 600;
}

.harupa-circular-checkbox, .harupb-circular-checkbox {
  position: relative;
  display: inline-block;
  width: 18px;
  height: 18px;
}

.harupa-circular-checkbox input, .harupb-circular-checkbox input  {
  position: absolute;
  opacity: 0;
  cursor: pointer;
}
.harupa-circular-checkbox span, .harupb-circular-checkbox span {
  position: absolute;
  color: #fff;
  font-size: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 1px solid #000; /* Border color */
  border-radius: 50%;
  background-color: #fff;
  transition: background-color 0.3s ease, border-color 0.3s ease;
}

.harupa-circular-checkbox input:checked + span, .harupb-circular-checkbox input:checked + span {
  background-color: #029d02;
  color: #fff;
}
.total-amount{
  width: 100%;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  font-weight: 600;
  gap: 10px;
  color: #000;
}
.total-amount span{
  color: #029d02;
}

.open-play-btn{
  width: 30%;
  height: 50px;
  font-size: 20px;
  font-weight: 500;
  background-color: #7CABD9;
  color: #fff;
  border: none;
  transition: 0.5s;
  cursor: pointer;
}
.open-play-btn:hover{
  background-color: #4d96df;
}
.bet-input{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column-reverse;
  border: 1.5px solid #4d96df;
  width: 100%;
  min-height: 60px;
  background-color: #fff;
}
.bet-input div{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 60px;
  border-bottom: 1.5px solid #4d96df;
  padding: 0px 20px;
}
.bet-input div input{
  outline: none;
  border: none;
  font-size: 18px;
  background-color: #fff;
}
.bet-input-remove{
  font-size: 15px;
  color: #000000d5;
}
.bet-input-remove p{
  width: 25px;
  height: 25px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 15px;
  font-weight: 700;
  border-radius: 50%;
  border: 1px solid rgba(0, 0, 0, 0.76);
  cursor: pointer;
  transition: 0.7s;
}
.bet-input-remove p:hover{
  
  background-color: red;
  color: #fff;
}
/*jantri play conatiner*/

.jantri-play-container form{
  width: 100%;
  display: flex; 
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 10px;
}
.j-custom-select{
  padding: 10px 20px;
  -webkit-appearance: none;
  -moz-appearance: none;  
  appearance: none;  
  outline: none;
  border: none;
  width: 90%;
  height: 100%;
  font-size: 18px;
  font-weight: 500;
  color: #029d02;
  background-color: #EAF6F8;
}
.j-game-select-container{
  position: relative;
  width: 100%;
  height: 60px;
  display: flex;
  justify-content: left;
  align-items: center;
  border: 1.5px solid #54AAA4;
  background-color: #EAF6F8;
  padding: 0px 20px;
}
.j-game-select-container i{
  font-size: 18px;
}
.j-total-amount{
  width: 100%;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  font-weight: 600;
  gap: 10px;
  color: #000;
}
.j-total-amount span{
  color: #029d02;
}

.jantri-play-btn{
  width: 30%;
  height: 50px;
  font-size: 20px;
  font-weight: 500;
  background-color: #7CABD9;
  color: #fff;
  border: none;
  transition: 0.5s;
  cursor: pointer;
}
.jantri-play-btn:hover{
  background-color: #4d96df;
}
.grid-item {
  background-color: #2b7a78;
  color: white;
  text-align: center;
  padding: 10px;
  border-radius: 5px;
  font-size: 16px;
  cursor: pointer;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 85px;
  height: 85px;
}

.grid-item:hover {
  background-color: #3dccc7;
}

.amount-input {
  margin-top: 5px;
  width: 80%;
  padding: 5px;
  border: 1px solid #ccc;
  border-radius: 5px;
  text-align: center;
}
.jantri-main-input-containe{
  width: 100%;
  height: auto;
}
.jantri-main-input-containe .grid{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  gap: 5px;
}
.with-jota{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 50px;
}
.with-jota-number{
  display: flex;
  justify-content: left;
  align-items: center;
  width: 53%;
  height: 100%;
  border: 1.5px solid #54AAA4;
  padding: 0 5px;
}
.with-jota-checkbox{
  width: 14%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  border: 1.5px solid #54AAA4;
  gap: 5px;
}
.equalto{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 8%;
  height: 100%;
  font-size: 20px;
  font-weight: 700;
}
.equalto i{
  color: #000;
}
.with-jota-ammount{
  display: flex;
  justify-content: left;
  align-items: center;
  width: 25%;
  height: 100%;
  border: 1.5px solid #54AAA4;
  padding: 0 5px;
}
.with-jota-number input{
  outline: none;
  border: none;
  font-size: 17px;
  width: 100%;
  height: 100%;
}
.with-jota-ammount input{
  outline: none;
  border: none;
  font-size: 15px;
  width: 100%;
  height: 100%;
}
.with-jota-checkbox p{
  font-size: 13px;
  font-weight: 600;
}

.with-jota-circular-checkbox {
  position: relative;
  display: inline-block;
  width: 18px;
  height: 18px;
}

.with-jota-circular-checkbox input {
  position: absolute;
  opacity: 0;
  cursor: pointer;
}
.with-jota-circular-checkbox span {
  position: absolute;
  color: #fff;
  font-size: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 1px solid #000; /* Border color */
  border-radius: 50%;
  background-color: #fff;
  transition: background-color 0.3s ease, border-color 0.3s ease;
}

.with-jota-circular-checkbox input:checked + span {
  background-color: #029d02;
  color: #fff;
}
.jota-bet-input{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column-reverse;
  border: 1.5px solid #4d96df;
  width: 100%;
  min-height: 60px;
  background-color: #fff;
}
.with-joda-container {
  margin: 20px;
}
.with-joda-item {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}
.with-joda-item input {
  margin: 0 5px;
  padding: 5px;
}
.with-joda-delete-btn {
  color: red;
  cursor: pointer;
  margin-left: 10px;
}

.cross-play-container form{
  width: 100%;
  display: flex; 
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 10px;
}
.joda-total-amount{
  width: 100%;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  font-weight: 600;
  gap: 10px;
  color: #000;
}
.joda-total-amount span{
  color: #029d02;
}

@media (min-width:0px) and (max-width:576px) {
  .help {
      max-width: 100%; 
      flex-direction: row;
      padding: 10px; 
      box-sizing: border-box;
  }

  .help p {
      font-size: 25px;
      float: left;
  }
  

  #whatsapp {
    flex-direction: column;
    font-size: 25px;
    text-align: center;
    margin-top: 50px;
    
}

#whatsapp img {
    display: none;
    margin-right: 0;
    margin-bottom: 10px; 
   
    height: 25px;
    width: 25px;
  
 }
 .game-container-top {
  flex-direction: column;
  align-items: stretch;
  gap: 10px;
  margin-bottom: 10px;
  margin-right: 200px;
  float: left;
}
.game-container-bottom{
  margin-right: 80px;
}
.with-palti, .harup {
      flex-direction: column;
      align-items: flex-start;
    }

    .with-palti div, .harup div {
      width: 100%; 
      margin-bottom: 10px;
    }

    .equalto {
    margin-bottom: 10px;
    /* text-align: center; */
    
    }
    .harup-a-checkbox p{
     margin-top: 20px;
    }
    .harup-b-checkbox p{
      margin-top: 20px;
    }
    .harupa-circular-checkbox span i{
    display: none;
    text-decoration: none;
    }

}
@media (min-width:576px) and (max-width:768px){

  .help {
    min-width: 80%; 
    flex-direction: row;
    padding: 10px; 
    box-sizing: border-box; 
}

.help p {
    font-size: 20px;
    float: left;
}


#whatsapp {
  flex-direction: row;
  font-size: 20px;
  text-align: center;
  margin-bottom: 15px;
}

#whatsapp img {
  /* display: none; */
  margin-right: 0;
  margin-bottom: 1px; 
  height: 25px;
  width: 25px;

}
  .game-container-top {
    flex-direction: column; 
    align-items: stretch;
    gap: 10px; 
    margin-bottom: 10px;
    margin-right: 100px;
   text-align: center;
  }
  .game-container-bottom{
    margin-right: 80px;
  }
}
@media (min-width:768px) and (max-width:992px) {
  .help {
    min-width: 80%; 
    flex-direction: row;
    padding: 10px; 
    box-sizing: border-box; 
}

.help p {
    font-size: 20px;
    float: left;
}


#whatsapp {
  flex-direction: row;
  font-size: 20px;
  text-align: center;
  margin-bottom: 15px;
}

#whatsapp img {
  /* display: none; */
  margin-right: 0;
  margin-bottom: 1px; 
  height: 25px;
  width: 25px;
}
  .game-container-top {
    flex-direction: row; 
    align-items: stretch;
    gap: 10px; 
    margin-top: 20px;
    margin-right: 70px;
    text-align: center;
  }
  .game-container-bottom{
    margin-right: 80px;
  }

}
@media (min-width:992px) and (max-width:1200px){
  .help {
    min-width: 80%; 
    flex-direction: row;
    padding: 10px; 
    box-sizing: border-box; 
}

.help p {
    font-size: 20px;
    float: left;
}


#whatsapp {
  flex-direction: row;
  font-size: 20px;
  text-align: center;
  margin-bottom: 15px;
}

#whatsapp img {
  /* display: none; */
  margin-right: 0;
  margin-bottom: 1px; 
  height: 25px;
  width: 25px;

}
  .game-container-top {
    flex-direction: row;
    align-items: stretch;
    gap: 10px;
    margin-top: 20px;
    margin-right: 70px;
  }
  .game-container-bottom{
    margin-right: 80px;
  }
}
@media  (min-width:1200px){
  .help {
    min-width: 80%; 
    flex-direction: row;
    padding: 10px; 
    box-sizing: border-box; 
}

.help p {
    font-size: 20px;
    float: left;
}


#whatsapp {
  flex-direction: row;
  font-size: 20px;
  text-align: center;
  margin-bottom: 15px;
}

#whatsapp img {
  /* display: none; */
  margin-right: 0;
  margin-bottom: 1px; 
  height: 25px;
  width: 25px;

}
  .game-container-top {
    flex-direction: row;
    align-items: stretch;
    gap: 10px;
    margin-top: 20px;
    margin-right: 70px;
  }
  .game-container-bottom{
    margin-right: 80px;
  }
}




****Styles css code 

@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Set a base font size and family */
html {
  font-size: 16px;
  font-family: "Poppins", serif;
  scroll-behavior: smooth;
}

/* Apply a consistent style to the body */
body {
  color: #333;
  background-color: #f9f9f9; 
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  line-height: 1;
}


/* footer {
  text-align: center;
  width: 100%;
  padding: 1rem 0;
  background-color: #333;
  color: #fff;
} */


.top{
  width: 100%;
  height: 80px;
  background-color: #EAF6F8;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 50px;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
  
}
.top-right{
     width: 130px;
     height: 70px;
     background-image: url('../images/logo.png');
     background-position: center;
     background-size: cover;
     background-repeat: no-repeat;
     border-radius: 20% 0% 20% 0%;
     border: 2px solid #007bff;
}
.top-left{
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
.top-left .top-user-id{
  width: 80px;
  height: 40px;
  border:  1px solid #007bff;
  border-radius: 5px;
  border-top: 4px solid #007bff;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding: 0;
}

.top-left .top-user-id p:nth-child(1){
  font-size: 12px;
  font-weight: 600;
  color: #007bff;
}
.top-left .top-user-id p:nth-child(2){
  font-size: 15px;
  font-weight: 700;
  color:#000;
}
.top-user-money{
  width: 90px;
  height: 38px;
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 4px;
}
.top-user-money div{
  color: #fff;
  width: 25px;
  height: 25px;
  font-weight: 600;
  background-color: #029D02;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.top-user-money h5{
    color: #029D02;
}
.top-add-money{
  position: relative;
  width: 40px;
  height: 40px;
  text-decoration: none;
  font-size: 18px;
  
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #609CC1;
  border-radius: 4px;
}
.top-add-money i{
  width: 22px;
  height: 22px;
  background-color: #fff;
  border-radius: 50%;
  color: #609CC1;
  display: flex;
  justify-content: center;
  align-items: center;
}
.top-add-money .top-circle{
  position: absolute;
  top: -5px;
  right:-5px;
  width: 15px;
  height: 15px;
  border-radius: 50%;
  background-color: #029D02;
  border: 2px solid #EAF6F8;
}
/* For Chrome, Safari, Edge, and Opera */
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  -webkit-appearance: none;
  margin: 0;
}


/* Add responsiveness */

/* @media (min-width: 576px ) and (max-width: 746){
  body {
      width: 100%;
  }
} */
@media (max-width: 768px) {
  .container {
      width: 100%;
  }
}



@media (min-width:0px) and (max-width:576px) {
  .top{
  max-width: 100%;
  padding: 10px;
  box-sizing: border-box;
  }
}
@media (min-width:576px) and (max-width:768px) {
  .top{
  max-width: 100%;
 padding: 10px;
  box-sizing: border-box;
  }
}
