<svg viewBox="0 0 100 30" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<style>
  .wave {
    animation: wave 4s linear infinite;
    fill: #6C63FF;
    opacity: 0.8;
  }
  #wave2 {
    animation-duration: 6s;
    animation-direction: reverse;
    opacity: 0.5;
    fill: #4ECDC4;
  }
  #wave3 {
    animation-duration: 3s;
    opacity: 0.3;
    fill: #FFE66D;
  }
  @keyframes wave {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
</style>
<defs>
  <path id="wave-path" d="M 0,15 C 30,15 30,25 60,25 90,25 90,15 120,15 150,15 150,25 180,25 210,25 210,15 240,15 v 20 h -240 z" />
</defs>
<use id="wave1" class="wave" xlink:href="#wave-path" x="0" y="0"/>
<use id="wave2" class="wave" xlink:href="#wave-path" x="0" y="-3"/>
<use id="wave3" class="wave" xlink:href="#wave-path" x="0" y="-6"/>
</svg>
