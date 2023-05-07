
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Blog Page</title>
      <link rel="stylesheet" href="style.css">
  </head>  
  <body>
<header>
  <div class="bigbox">
    <div class="logo"><a href="#"><img src="pngwing.com.png" alt="logo"></a></div>
    <div class="navbar"><a href="#">Home</a>
    <a href="#">About Us </a>
    <a href="#">Contact</a></div>
  </div>
</header>
<main>
<article>
  <div class="blog">
<div class="intro"> <h1>The Future of Robotics and Robots</h1>
<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Magni veritatis, fuga sunt id, deserunt corporis eligendi iusto molestiae velit quia, laboriosam debitis? Nulla praesentium fuga nesciunt provident dignissimos delectus aliquam, sit ex magni quam facere ullam esse iure minima unde et modi sint eius impedit optio nemo? Amet mollitia, nam voluptatem ea laborum velit, consectetur unde blanditiis ex reprehenderit numquam totam, consequuntur deserunt! Et reprehenderit dolor nulla neque temporibus adipisci error nesciunt magnam distinctio? Aperiam nisi pariatur, corrupti natus, aliquid molestiae minus harum sed tempora, beatae quidem. Iste, et mollitia, sit ducimus neque facere nulla aliquid, repudiandae earum voluptate saepe?</p></div>

<div class="img">
<img class="robo" src="robo.jpg" alt="robo">
</div>

</div>

</article>
</main>

</body>
</html>


style.css
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;}

/*starts here*/
header{
background-color: rgb(42, 120, 165);}
img{width: 80px;
height: 80px;
}
.navbar,a{font-size: 16px;
    color: white;
text-decoration: none;
text-transform: uppercase;
padding-left: 10px;

}

.logo,.navbar{display: inline-block;
vertical-align: middle;
}
.navbar{margin-left: 1000px;}
.navbar,a:hover{color: aqua;}
article{padding: 0px 50px;}

.blog{padding-left: 80px;}

.intro,.img{display: inline-block;}
.intro{width: 400px;
height: 400px;
margin-right: 150px;
}

.img,.robo{width: 400px;
height: 300px;
margin-top: 50px;
}
h1{font-size: 22px;
font-weight: 800;
margin-bottom: 20px;
}
p{line-height: 1.3;}




