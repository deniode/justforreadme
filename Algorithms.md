---


---

<h1 id="readme">README</h1>
<h1 id="лабораторная-работа-по-алгоритмам-и-структурам-данных">Лабораторная работа по Алгоритмам и структурам данных</h1>
<h2 id="версия-1.01">Версия 1.01</h2>
<h3 id="студент-ионов-денис">Студент: Ионов Денис</h3>
<h3 id="преподаватель-санеев-илья">Преподаватель: Санеев Илья</h3>
<p>В работе реализованы следыющие алгоритмы сортировки:</p>
<ul>
<li>Алгоритм сортировки выбором.</li>
<li>Алгоритм сортировки вставками</li>
<li>Сортировка Шелла</li>
<li>Алгоритм быстрой сортировки.</li>
<li>Алгоритм сортировки слиянием.</li>
<li>Поразрядная сортировка (RadixSort)</li>
</ul>
<p>Входными данными для программы является массив из целых чисел в диапазоне от 0 до 3 000 000 000.</p>
<p>В экспериментальной части для каждого типа сгенерированного массива (RANDOMIZED, SORTED, REVERSED) и для каждого размера массива (100, 500, 1000, 5000, 10000, 50000. 100000) совершалось 5 попыток запуска программы для нахождения среднего времени.</p>
<hr>
<h3 id="selection-sort">Selection Sort</h3>
<p>Сортировка выбором сортирует массив, каждый раз находя минимальный элемент в неотсортированной часте массива и помещая его в начало.</p>
<h5 id="оценка-по-времени">Оценка по времени:</h5>
<p>O(n2), т.к. реализация включает в себя два вложенных цикла for</p>
<h5 id="оценка-по-памяти">Оценка по памяти:</h5>
<p>O(1)</p>
<p>Таблица среднего времени запуска программы по различным вводным данным, микросекунды</p>

<table>
<thead>
<tr>
<th>Тип   исходного массива/Количество элементов</th>
<th>100</th>
<th>500</th>
<th>1000</th>
<th>5000</th>
<th>10000</th>
<th>50000</th>
<th>100000</th>
</tr>
</thead>
<tbody>
<tr>
<td>RANDOMIZED</td>
<td>37,6</td>
<td>495,6</td>
<td>2005,8</td>
<td>51923,4</td>
<td>349349,5</td>
<td>5033993</td>
<td>19858112</td>
</tr>
<tr>
<td>SORTED</td>
<td>30,8</td>
<td>1206,6</td>
<td>2776,2</td>
<td>79571,8</td>
<td>320367,4</td>
<td>4874275</td>
<td>17884170</td>
</tr>
<tr>
<td>REVERSED</td>
<td>33,6</td>
<td>785,8</td>
<td>2577,6</td>
<td>126522,6</td>
<td>376719,8</td>
<td>5288054</td>
<td>19102147</td>
</tr>
</tbody>
</table><p><img src="https://3.downloader.disk.yandex.ru/preview/c1ec4e8e8451bb03e55bd7ccda9751e0eaea02293c820cb49188819dd0640d6e/inf/biSzw9oC_lrYBX0fD6-6CxHDp80NpyOB9ewYrVal7XOeHkspntiQMXLbIdTj-WAftT5hzwDO46UkmHBi250esQ==?uid=89395030&amp;filename=2018-02-04_23-09-49.png&amp;disposition=inline&amp;hash=&amp;limit=0&amp;content_type=image/png&amp;tknv=v2&amp;size=1249x509" alt="Selection Sort"></p>
<hr>
<h3 id="insertion-sort">Insertion Sort</h3>
<p>Сортировка вставками происходит путем сравнения элемента с предыдущем и последующим сравнением с каждым элементом из левой части массива.</p>
<h5 id="оценка-по-времени-1">Оценка по времени:</h5>
<p>O(n2). Худшее время будет для обратно отсортированного массива</p>
<h5 id="оценка-по-памяти-1">Оценка по памяти:</h5>
<p>O(1)<br>
Таблица среднего времени запуска программы по различным вводным данным, микросекунды</p>

<table>
<thead>
<tr>
<th>Тип   исходного массива/Количество элементов</th>
<th>100</th>
<th>500</th>
<th>1000</th>
<th>5000</th>
<th>10000</th>
<th>50000</th>
<th>100000</th>
</tr>
</thead>
<tbody>
<tr>
<td>RANDOMIZED</td>
<td>24,2</td>
<td>508</td>
<td>2008</td>
<td>60938,8</td>
<td>288805</td>
<td>4285940</td>
<td>18088853</td>
</tr>
<tr>
<td>SORTED</td>
<td>2,6</td>
<td>7,6</td>
<td>12,8</td>
<td>58</td>
<td>115,4</td>
<td>490,2</td>
<td>742</td>
</tr>
<tr>
<td>REVERSED</td>
<td>29,2</td>
<td>669,6</td>
<td>2042,4</td>
<td>98114,2</td>
<td>339532,2</td>
<td>4618492</td>
<td>21114319</td>
</tr>
</tbody>
</table><p><img src="https://2.downloader.disk.yandex.ru/preview/907aa8183125a982ffd887ec09d3f8fe140c0069c0b51becd674b9b39774f5fe/inf/biSzw9oC_lrYBX0fD6-6C1gh_soweO3na5uz7i4oAQdPNl8S8oFZ70K-0ACxD6ZVbHy2-HY-ex7O01MD0yTizw==?uid=89395030&amp;filename=2018-02-04_23-11-03.png&amp;disposition=inline&amp;hash=&amp;limit=0&amp;content_type=image/png&amp;tknv=v2&amp;size=1249x509" alt="Insertion Sort"></p>
<hr>
<h3 id="shell-sort">Shell Sort</h3>
<p>Сортировка Шелла является переосмыслением сортировки вставками, т.к. позволяет перемещение между удаленными элементами массива на расстоянии h.</p>
<h5 id="оценка-по-времени-2">Оценка по времени:</h5>
<h5 id="оценка-по-памяти-2">Оценка по памяти:</h5>
<p>Таблица среднего времени запуска программы по различным вводным данным, микросекунды</p>

<table>
<thead>
<tr>
<th>Тип   исходного массива/Количество элементов</th>
<th>100</th>
<th>500</th>
<th>1000</th>
<th>5000</th>
<th>10000</th>
<th>50000</th>
<th>100000</th>
</tr>
</thead>
<tbody>
<tr>
<td>RANDOMIZED</td>
<td>28</td>
<td>196,8</td>
<td>352,2</td>
<td>1964</td>
<td>10248</td>
<td>40208,2</td>
<td>50421,2</td>
</tr>
<tr>
<td>SORTED</td>
<td>5,4</td>
<td>32,2</td>
<td>64,8</td>
<td>456,6</td>
<td>2180,6</td>
<td>6876,2</td>
<td>9305,8</td>
</tr>
<tr>
<td>REVERSED</td>
<td>11,2</td>
<td>55,4</td>
<td>114,6</td>
<td>627</td>
<td>1645,8</td>
<td>8798,4</td>
<td>19264,2</td>
</tr>
</tbody>
</table><p><img src="https://4.downloader.disk.yandex.ru/preview/3a792a7433d2f384f9449b4b9e52463887cf94f8b50922a8d1fa7848cc952bb8/inf/biSzw9oC_lrYBX0fD6-6C58zf7M6reMGBhwzLAv57ofyaI2A1vwal8C7i85aZpKm6ypzn8oKdp6q7odgfjhlEw==?uid=89395030&amp;filename=2018-02-04_23-11-56.png&amp;disposition=inline&amp;hash=&amp;limit=0&amp;content_type=image/png&amp;tknv=v2&amp;size=1249x509" alt="Shell Sort"></p>
<hr>
<h3 id="quick-sort">Quick Sort</h3>
<p>Быстрая сортировка</p>
<p><a href="mailto:den.ionov@gmail.com">den.ionov@gmail.com</a></p>

