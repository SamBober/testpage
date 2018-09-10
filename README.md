# testpage


<!DOCTYPE html>

<html lang="ru">
<head>
  <meta charset="utf-8">
  <title>Интерактивная карта Аместриса</title>
  <script src="http://code.jquery.com/jquery-latest.js"></script>
  <script src="jquery.tooltip.min.js"></script>
  <link href="style.css" rel="stylesheet">
</head>

<body>

<div id="text">
  <h1>Аместрис</h1>
  <p>Страна из вселенной «Стального алхимика». Имеет форму окружности. Разделена на 5 районов:</p>
  <table id="areas">
    <thead>
      <tr>
        <th></th>
        <th>Название</th>
        <th><input type="radio" id="peopleswitch" name="tabledata"><label for="peopleswitch">Люди</label></th>
        <th><input type="radio" id="moneyswitch" name="tabledata"><label for="moneyswitch">Деньги</label></th>
      </tr>
    </thead>
    <tbody>
      <tr id='path3186'> 
        <td><input type="checkbox"></td>
        <td>Центр</td>
        <td>23,5</td>
        <td>19464,3</td>
      </tr> 
      <tr id='path3191'> 
        <td><input type="checkbox"></td>
        <td>Восток</td> 
        <td>18,2</td>
        <td>7859,5</td>
      </tr> 
      <tr id='path3180'> 
        <td><input type="checkbox"></td>
        <td>Юг</td> 
        <td>15,9</td>
        <td>6503,9</td>
      </tr> 
      <tr id='path3177'> 
        <td><input type="checkbox"></td>
        <td>Запад</td> 
        <td>11,7</td>
        <td>5673,1</td>
      </tr> 
      <tr id='path2405'> 
        <td><input type="checkbox"></td>
        <td>Север</td> 
        <td>5,6</td>
        <td>11349,6</td>
      </tr> 
    </tbody>
  </table>
  <p><input type="radio" id="resetswitch" name="tabledata" checked><label for="resetswitch">Не показывать никаких значений</label></p>
  <p><input type="checkbox" id="titleswitch"><label for="titleswitch">Скрыть названия городов и зон.</label></p>
</div>

<figure id="imapc">
  <object data="Amestris_map.svg" type="image/svg+xml" id="imap">
    <p>К сожалению, вы используете устаревшую версию браузера, который не поддерживает интерактивную карту.</p>
  </object>
  <figcaption>SVG-карта страны Аместрис</figcaption>
</figure>

<script src="script.js"></script>

</body>
</html>
