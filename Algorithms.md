---


---

<h1 id="readme">README</h1>
<h1 id="лабораторная-работа-по-алгоритмам-и-структурам-данных">Лабораторная работа по Алгоритмам и структурам данных</h1>
<h2 id="версия-0.87">Версия 0.87</h2>
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
<hr>
<h3 id="selection-sort">Selection Sort</h3>
<p>Сортировка выбором сортирует массив, каждый раз находя минимальный элемент в неотсортированной часте массива и помещая его в начало.</p>
<h5 id="оценка-по-времени">Оценка по времени:</h5>
<p>O(n2), т.к. реализация включает в себя два вложенных цикла for</p>
<h5 id="оценка-по-памяти">Оценка по памяти:</h5>
<p>O(1)</p>

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
</table><p><img src="https://3.downloader.disk.yandex.ru/preview/c1ec4e8e8451bb03e55bd7ccda9751e0eaea02293c820cb49188819dd0640d6e/inf/biSzw9oC_lrYBX0fD6-6CxHDp80NpyOB9ewYrVal7XOeHkspntiQMXLbIdTj-WAftT5hzwDO46UkmHBi250esQ==?uid=89395030&amp;filename=2018-02-04_23-09-49.png&amp;disposition=inline&amp;hash=&amp;limit=0&amp;content_type=image/png&amp;tknv=v2&amp;size=1249x509" alt="enter image description here"></p>
<p>Входными данными для программы является массив из целых чисел в диапазоне от 0 до 3 000 000 000.</p>
<p><a href="mailto:den.ionov@gmail.com">den.ionov@gmail.com</a></p>

