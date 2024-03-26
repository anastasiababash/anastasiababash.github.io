---
title: Talks
layout: page
---

<h2>Conference and Workshop Presentations, Public Lectures</h2>

<style>
  /* Стили для скрытия текста */
  .hidden-text {
    display: none;
  }
</style>
</head>
<body>

<!-- Кнопка для открытия текста -->
<button onclick="toggleText()">Показать текст</button>

<!-- Текст, который раскроется -->
<p id="hiddenText" class="hidden-text">Это раскрывающийся текст!</p>

<script>
  function toggleText() {
    var hiddenText = document.getElementById("hiddenText");
    if (hiddenText.style.display === "none") {
      hiddenText.style.display = "block";
    } else {
      hiddenText.style.display = "none";
    }
  }
</script>


<details>
  <summary>Легенда</summary>
  <p>Раскрывающийся текст</p>
</details>
