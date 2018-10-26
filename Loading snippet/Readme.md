

## Screenshot
![Screenshot](https://i.imgur.com/2HGbjJ4.png)

> ### Try changing color of LOADING text by uncommenting 64,68 and 78 th LINE  and comment all colors in css file after those three changes i.e. for  #text span{}     #text span:nth-child(2){}    .... and so on, under styleV2.css file.


##### I'm also attaching a sample css, replace only these css files.



@keyframes blink {

  0% {
  
    opacity: 0.2;
    color:grey;
  }
  
  20% {
  
    opacity: 1;
    color:grey;
  }
  
  100% {
  
    opacity: 0.2;
    color:grey;
  }
  
}


#text span

{

animation: blink 4s infinite;
  
}

#text span:nth-child(2)

{

  animation-delay: 0.2s;

}

#text span:nth-child(3) 

{

  animation-delay: 0.4s;

}

#text span:nth-child(4) 

{

animation-delay: 0.6s;

}

#text span:nth-child(5) 

{

animation-delay: 0.8s;

}

#text span:nth-child(6) 


{

animation-delay: 1s;

}

#text span:nth-child(7) 

{

animation-delay: 1.2s;

}

#text span:nth-child(8)

{

animation-delay: 1.4s;

}

#text span:nth-child(9) 


{

  animation-delay: 1.6s;
  
}

#text span:nth-child(10) 

{

  animation-delay: 1.8s;
  
}









