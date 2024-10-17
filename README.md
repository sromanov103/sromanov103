# 💫 About Me:
🔭 My name is Sergey, I am a beginner programmer.<br>🌱I have an incomplete higher education in programming.<br>🤝 I'm studying Al Sweigart's book Automating Routine Tasks with Python.<br>💬 I'm learning Python, C++, C#<br>⚡ I am studying courses on neural networks.<br>


## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/polovoyagressor) 
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/paren_iz_alupki_) 
[![Telegram](https://img.shields.io/badge/Telegram-%230088cc.svg?logo=Telegram&logoColor=white)](https://t.me/PiterChong)

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=sromanov103&theme=react&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=sromanov103&theme=react&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=sromanov103&theme=react&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

### 😂 Random Dev Meme
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Случайный мем</title>
</head>
<body>
    <h1>😂 Random Dev Meme</h1>
    <img id="meme" src="" style="height: 400px;" />
    <script>
        fetch('https://api.imgflip.com/get_memes')
            .then(response => response.json())
            .then(data => {
                const memes = data.data.memes; // Получаем массив мемов
                const randomMeme = memes[Math.floor(Math.random() * memes.length)]; // Выбираем случайный мем
                const memeImage = randomMeme.url; // URL изображения мема

                document.getElementById('meme').src = memeImage; // Установка изображения в элемент <img>
            })
            .catch(error => console.error('Ошибка:', error));
    </script>
</body>
</html>

---
[![](https://visitcount.itsvg.in/api?id=sromanov103&icon=8&color=8)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
