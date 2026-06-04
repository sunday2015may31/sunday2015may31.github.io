# Simple workflow for deploying static content to GitHub Pages
name: Deploy static content to Pages

on:
  # Runs on pushes targeting the default branch
  push:
    branches: ["main"]

  # Allows you to run this workflow manually from the Actions tab
  workflow_dispatch:

# Sets permissions of the GITHUB_TOKEN to allow deployment to GitHub Pages
permissions:
  contents: read
  pages: write
  id-token: write

# Allow only one concurrent deployment, skipping runs queued between the run in-progress and latest queued.
# However, do NOT cancel in-progress runs as we want to allow these production deployments to complete.
concurrency:
  group: "pages"
  cancel-in-progress: false

jobs:
  # Single deploy job since we're just deploying
  deploy:
    environment:
      name: github-pages
      url: ${{ steps.deployment.outputs.page_url }}
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4
      - name: Setup Pages
        uses: actions/configure-pages@v5
      - name: Upload artifact
        uses: actions/upload-pages-artifact@v3
        with:
          # Upload entire repository
          path: '.'
      - name: Deploy to GitHub Pages
        id: deployment
        uses: actions/deploy-pages@v5

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>HTML Document Template</title>
  <style>
    p {
      font-family: Arial, sans-serif;
    }
  </style>
</head>
<body>
  <p>timcorp library</p>
  <script>
    console.log(document.querySelector('p').textContent);
  </script>
</body>
</html>
<audio controls>
  <source src="https://static.wikia.nocookie.net/omori/images/f/fe/Event_ghost_party.ogg" type="audio/ogg">
</audio>
<img style="display: block;-webkit-user-select: none;margin: auto;background-color: hsl(0, 0%, 90%);transition: background-color 300ms;" src="https://avatars.mds.yandex.net/i?id=dd646cee156e932c4a26ccc5f0c85271_l-9099391-images-thumbs&amp;n=13">
pranked
lol
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Кнопка на Google</title>
    <style>
        /* Стилизуем ссылку, чтобы она выглядела как красивая кнопка */
        .google-btn {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            background-color: #4CAF50; /* Зеленый цвет */
            text-decoration: none; /* Убираем подчеркивание */
            border-radius: 5px; /* Закругляем углы */
            font-family: Arial, sans-serif;
            transition: background 0.3s;
        }
        /* Эффект при наведении мышки */
        .google-btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <h2>Нажмите на кнопку ниже, чтобы перейти на сайт для тебя</h2>
    
    <a href="https://yandex.ru/search/?text=%D0%BA%D0%B0%D0%BA+%D0%B7%D0%B0%D1%81%D1%82%D0%B0%D0%B2%D0%B8%D1%82%D1%8C+%D0%BB%D1%8E%D0%B4%D0%B5%D0%B9+%D0%BB%D1%8E%D0%B1%D0%B8%D1%82%D1%8C+%D1%82%D0%B5%D0%B1%D1%8F+%D0%B5%D1%81%D0%BB%D0%B8+%D1%82%D1%8B+%D0%B6%D0%BB%D0%B8%D0%B9+%D0%BD%D0%B5%D1%83%D0%B4%D0%B0%D1%87%D0%BD%D0%B8%D0%BA+%D0%B2+%D1%82%D1%80%D1%83%D1%81%D0%B8%D1%88%D0%BA%D0%B0%D1%85&clid=2411726&source=chrome.ob&lr=10281"target="_blank" class="google-btn">Перейти</a>

</body>
</html>

 <a href="https://omori-game.com/en/whitespace"target="_blank" class="google-btn">не переходить</a>
<div style="font-family: Arial, sans-serif; max-width: 300px;">
    <audio src="https://static.wikia.nocookie.net/omori/images/8/80/Boss_pluto.ogg" 
           class="thumbimage" 
           style="width: 100%; max-width: 180px;" 
           controls>
    </audio>
    
    <div style="margin-top: 5px; font-size: 12px;">
        <a href="https://omori.fandom.com/ru/wiki/%D0%A4%D0%B0%D0%B9%D0%BB:Boss_pluto.ogg" target="_blank">
        </a>
    </div>
</div>
