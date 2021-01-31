# тестовое задание 7ЦВЕТОВ

## 1. Для чего служит тип объекта метаданных 1С &quot;Последовательность&quot;?
а) Для визуализации журнала документов отгрузки с определенной сортировкой<br>
б) Для группирования документов в едином хронологическом порядке<br>
в) Для последовательной групповой обработки справочников или документов<br>

#### Ответ: Б

## 2. Каким образом нужно соединить таблицы А и Б, чтобы получить результат В?

<table>
<caption>А:</caption>
<tr><td>Клиент №1</td><td> 1000</td></tr>
<tr><td>Клиент №2</td><td> 12300</td></tr>
<tr><td>Клиент №3</td><td> 15600</td></tr>
</table>
<table>
<caption>Б:</caption>
<tr><td>Клиент №1</td><td> Категория А</td></tr>
<tr><td>Клиент №2</td><td> Категория B</td></tr>
<tr><td>Клиент №3</td><td> Категория A</td></tr>
<tr><td>Клиент №4</td><td> Категория С</td></tr>
</table>
<table>
<caption>В:</caption>
<tr><td>Категория А</td><td> 16600</td></tr>
<tr><td>Категория B</td><td> 12300</td></tr>
<tr><td>Категория C</td><td> 0</td></tr>
</table>

а) А полное соединение Б, далее итоги по &quot;категории&quot;<br>
б) А левое соединение Б, далее группировка по &quot;категории&quot;<br>
в) Б левое соединение А, далее группировка по &quot;категории&quot;<br>
г) А внутреннее соединение Б, далее итоги по &quot;категории&quot;<br>

#### Ответ: В

## 3. Что произойдет при выполнении следующего кода? <br>
(регистр сведений &quot;КонтактныеДанные&quot; независимый и непериодический).<br>

```1C
НовыйНаборЗаписей = РегистрыСведений.КонтактныеДанные.СоздатьНаборЗаписей();
НовыйНаборЗаписей.Записать();
```
а) Очистка регистра &quot;КонтактныеДанные&quot;<br>
б) Будет вызвано исключение<br>
в) Ничего<br>
г) Добавлена запись в пустыми полями<br>

#### Ответ: А

## 4. Какие виртуальные таблицы будут доступны в конструкторе запросов для регистра накопления оборотов &quot;ЗатратыПоЗаказам&quot;?
а) ЗатратыПоЗаказам.СрезПоследних<br>
б) ЗатратыПоЗаказам.Остатки<br>
в) ЗатратыПоЗаказам.ОстаткиИОбороты<br>
г) ЗатратыПоЗаказам.Обороты<br>
д) ЗатратыПоЗаказам.ДвиженияССубконто<br>
е) варианты в, г<br>
ж) варианты г, д<br>
з) варианты б, в, г<br>
и) варианты а, б, в<br>

#### Ответ: Г
