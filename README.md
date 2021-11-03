.content {
    position: relative;
    z-index: 3;
  }
  #no{
    position: absolute;
    display: inline-block;
    left: 35%; 
    top: 40vh;
    -webkit-transition: all 0.1s ease-out;
  }
  #yes{
    position: absolute;
    display: inline-block;
    left: 70%; 
    top: 40vh;
    -webkit-transition: all 0.3s ease-out;
  }
#bg{
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  opacity: .8;
  /* height: 100vh; */
  z-index: 0;
  background-repeat: no-repeat;
  background-image: url(../img/puung3.jpg);
  background-size: cover;
  background-position: 50%;
  -webkit-filter: blur(4px);
}
.swal2-title, .swal2-content{
  color: azure !important;
}
.swal2-popup {
  border-radius: 15px !important;
}

header h2 {
  font-family: 'Pacifico';
  font-size: 80px;
  text-align: center;
	margin-bottom: 30px;
}
header h4 {
  font-family: 'Pacifico';
  text-align: center;
}

@media only screen and (max-width: 500px) {
  header h2 {
    font-family: 'Pacifico';
    font-size: 45px;
    text-align: center;
    margin-bottom: 30px;
  }
  header h4 {
    font-family: 'Pacifico';
    text-align: center;
    padding: 15px;
  }
  #no{
    position: absolute;
    display: inline-block;
    left: 7%; 
    top: 40vh;
    font-size: 14px;
    padding: 3px;
    -webkit-transition: all 0.1s ease-out;
  }
  #yes{
    position: absolute;
    display: inline-block;
    left: 58%; 
    top: 40vh;
    font-size: 14px;
    padding: 3px;
    -webkit-transition: all 0.3s ease-out;
  }
}
