<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>.wave {
        animation-name: wave-animation;  /* Name of @keyframes element below */
        animation-duration: .75s;  /* Wave speed */
        animation-iteration-count: infinite;
        animation-timing-function: linear;
        animation-play-state: paused;
        transform-origin: 70% 70%;  /* Pivot from bottom-left palm */
        display: inline-block;
        font-size: 8rem;
      }
      
      .wave:hover {
        animation-play-state: running; /* Play animation on mouse hover */
      }
      
      @keyframes wave-animation {
        0% { transform: rotate( 0deg ) }
        25% { transform: rotate( -10deg ) }
        75% { transform: rotate( 12deg ) }
        100% { transform: rotate( 0deg ) }
      }</style>
</head>
<body>
    Hi <span class="wave">👋</span> I'm Heba
    
</body>
</html>
