### Hi there 👋

<div>
<a href="https://github.com/seu-usuário-aqui">
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JhonathanLemos&layout=compact&langs_count=7&theme=dracula"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=JhonathanLemos&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
</div>
  
  
  ![Snake animation](https://github.com/JhonathanLemos/JhonathanLemos/blob/output/github-contribution-grid-snake.svg)
  
  <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Loading</title>
</head>
<body>
    <ul>
        <li>L</li>
        <li>O</li>
        <li>A</li>
        <li>D</li>
        <li>I</li>
        <li>N</li>
        <li>G</li>
    </ul>
    
</body>
</html>
  
  body
{
    margin: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    font-family: sans-serif;
}

ul
{
    margin: 0;
    padding: 0;
    display: flex;
}

ul li
{
    list-style: none;
    font-size: 80px;
    letter-spacing: 20px;
    animation: loading 3s linear infinite
}

@keyframes loading
{
    0%
{ 
    color: red;
    transform: translateX(-50px);
    letter-spacing: 20px;
    opacity: 0;
}
    10% 
{
    opacity: 1;
}
    50% 
{ 
    letter-spacing: -20px;
    opacity: 1;
}
    100% 
{
    color: blue;
    transform: translateX(50px);
    letter-spacing: 20px;
    opacity: 0;
}
}

ul li:nth-child(1)
{
    animation-delay: 0s;
}
ul li:nth-child(2)
{
    animation-delay: 0.2s;
}
ul li:nth-child(3)
{
    animation-delay: 0.4s;
}
ul li:nth-child(4)
{
    animation-delay: 0.6s;
}
ul li:nth-child(5)
{
    animation-delay: 0.8s;
}
ul li:nth-child(6)
{
    animation-delay: 1s;
}
ul li:nth-child(7)
{
    animation-delay: 1.2s;
}
