# w3-matching-button
I've applied CSS on button that will look awesome with w3 form formats.
I've added a sapereate css file also for those who need only css code.




//Button One
       
        .btn1 {
        width: 100px;
        height: 40px;
        border: 3px solid #04aa6d;
        border-radius: 45px;
        transition: all 0.3s;
        cursor: pointer;
        background: white;
        font-size: 1.2em;
        font-weight: 550;
        font-family: "Montserrat", sans-serif;
      }
      
      .btn1:hover {
        background: #04aa6d;
        color: white;
        font-size: 1.5em;
      }
    
    
    
   //Second Button
        
        .btn3 {
        position: relative;
        margin-left: 45%;
        font-size: 17px;
        text-transform: uppercase;
        text-decoration: none;
        padding: 1em 2.5em;
        display: inline-block;
        border-radius: 6em;
        transition: all 0.2s;
        border: none;
        font-family: inherit;
        font-weight: 500;
        color: black;
        background-color: white;
      }
      
      .btn3:hover {
        transform: translateY(-3px);
        box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
      }
      
      .btn3:active {
        transform: translateY(-1px);
        box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
      }
      
      .btn3::after {
        content: "";
        display: inline-block;
        height: 100%;
        width: 100%;
        border-radius: 100px;
        position: absolute;
        top: 0;
        left: 0;
        z-index: -1;
        transition: all 0.4s;
      }
      
      .btn3::after {
        background-color: #04aa6d;
      }
