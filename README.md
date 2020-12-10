
<div> 


<h1>CRY AND CODING</h1>

<div>
<a href="https://github.com/natterstefan/natterstefan">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=cloudbyteelias&show_icons=true&line_height=27&count_private=true&title_color=ffffff&text_color=c9cacc&icon_color=2bbc8a&bg_color=1d1f21" alt="Catalin's GitHub Stats" />
</a>
</div>
<div>

<br>
<a href="https://github.com/natterstefan/natterstefan">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cloudbyteelias&hide=java,html&title_color=ffffff&text_color=c9cacc&icon_color=2bbc8a&bg_color=1d1f21" />
</a>

</div>


<style> 


@font-face {font-family: pixel_font;src: url('fonts/prstartk.ttf') format('opentype');}



h1{
    text-align: center;
    font-size: 80px;
    font-family: 'pixel_font';
}

:root{
    --neon-purple: 341, 100%, 58%;
    --neon-blue: 184, 96%, 46%;
}


h1::before{
    z-index: -1;
    position: absolute;
    top: 0.2rem;
    left: -0.2rem;
    width: 100%;
    height: 100%;
    color: hsl(var(--neon-purple));
    opacity: 0.7;
    -webkit-animation: glitch 0.3s linear infinite alternate-reverse;
    animation: glitch 0.3s linear infinite alternate-reverse;

}

h1::after{
    z-index: -1;
    position: absolute;
    top: 0.1rem;
    left: 0.2rem;
    width: 100%;
    height: 100%;
    color: hsl (var(--neon-blue));
    opacity: 0.7;
    -webkit-animation: glitch 0.4s 0.2s linear infinite alternate-reverse;
    animation: glitch 0.3s 0.1s linear infinite alternate-reverse;
    -webkit-clip-path: polygon(3% 100%,14% 28%,67% 15%,103% 67%);
    clip-path: polygon(3% 100%, 14% 28%, 67% 15%,103% 67%);
}

@keyframes glitch{
    0%{
      -webkit-transform: translate(0);
      transform: translate(0);

    }20%{
        -webkit-transform: translate(-0.1rem, -0.1rem);
        transform: translate(-0.1rem, -0.1rem);

    }40%{
        -webkit-transform: translate(-0.1rem, -0.1rem);
        transform: translate(-0.1rem , -0.1rem);

    }60%{
        -webkit-transform: translate(0.1rem, 0.1rem);
        transform: translate(0.1rem,0.1rem);

    }80%{
        -webkit-transform: translate(0.1rem, -0.1rem);
        transform: translate(0.1rem, -0.1rem);

    }to{
        -webkit-transform: translate(0);
        transform: translate(0);
    }
}

@-webkit-keyframes glitch{
    0%{
        -webkit-transform: translate(0);
        transform: translate(0);
    }20%{
        -webkit-transform: translate(-0.1rem, -0.1rem);
        transform: translate(-0.1rem, -0.1rem);

    }40%{
        -webkit-transform: translate(-0.1rem, -0.1rem);
        transform: translate(-0.1rem, -0.1rem);

    }60%{
        -webkit-transform: translate(0.1rem, 0.1rem);
        transform: translate(0.1rem, 0.1rem);

    }80%{
        -webkit-transform: translate(0.1rem, -0.1rem);
        transform: translate(0.1rem, -0.1rem);

    }to{
        -webkit-transform: translate(0);
        transform: translate(0);

    }
}

 h1::before{
    content: "CRY AND CODING";
}









</style>

</div>