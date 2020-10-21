<template>
  <div class="content-panel">
    <h4>Список завок</h4>
    <hr>
    <table class="table table-striped table-advance table-hover">
      <thead>
        <tr>
          <th id="id"><i class="fa fa-sort-numeric-asc"></i> id</th>
          <th id="theme"><i class="fa fa-envelope"></i> Тема</th>
          <th id="author"><i class="fa fa-wheelchair"></i> Автор</th>
          <th id="master"><i class="fa fa-users"></i> Кто взял</th>
          <th id="date"><i class="fa fa-bookmark"></i> Дата</th>
          <th id="buttons"><i class=" fa fa-cogs"></i> Действия</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>8804</td>
          <td>Удлинить кабель</td>
          <td>Мария Созинова</td>
          <td>Ляушкин Ярослав</td>
          <td>21/10/2020 12:26 PM</td>
          <td>
            <button class="btn btn-success btn-xs"><i class="fa fa-check"></i></button>
            <button class="btn btn-info btn-xs"><i class="fa fa-user"></i></button>
            <button class="btn btn-primary btn-xs"><i class="fa fa-comments "></i></button>
            <button class="btn btn-warning btn-xs"><i class="fa fa-file-text "></i></button>
            <button class="btn btn-danger btn-xs"><i class="fa fa-trash-o "></i></button>
          </td>
        </tr>
        <tr>
          <td>8781</td>
          <td>Заявка 11994 от 19.10.2020. Лунда, ООО. Протянуть провод ООО. Протянуть проводООО. Протянуть провод</td>
          <td>Сервис</td>
          <td>Ляушкин Ярослав</td>
          <td>19/10/2020 04:11 PM</td>
          <td>
            <button class="btn btn-success btn-xs"><i class="fa fa-check"></i></button>
            <button class="btn btn-info btn-xs"><i class="fa fa-user"></i></button>
            <button class="btn btn-primary btn-xs"><i class="fa fa-comments "></i></button>
            <button class="btn btn-warning btn-xs"><i class="fa fa-file-text "></i></button>
            <button class="btn btn-danger btn-xs"><i class="fa fa-trash-o "></i></button>
          </td>
        </tr>
        <tr>
          <td>8727</td>
          <td>перенос принтера</td>
          <td>Дарья Гамова</td>
          <td>Ляушкин Ярослав</td>
          <td>12/10/2020 11:28 AM</td>
          <td>
            <button class="btn btn-success btn-xs"><i class="fa fa-check"></i></button>
            <button class="btn btn-info btn-xs"><i class="fa fa-user"></i></button>
            <button class="btn btn-primary btn-xs"><i class="fa fa-comments "></i></button>
            <button class="btn btn-warning btn-xs"><i class="fa fa-file-text "></i></button>
            <button class="btn btn-danger btn-xs"><i class="fa fa-trash-o "></i></button>
          </td>
        </tr>
        <tr>
          <td>8620</td>
          <td>Заявка 11904 от 29.09.2020. ЛКП. Заменить элемент питания в пульте</td>
          <td>Сервис</td>
          <td>Ляушкин Ярослав</td>
          <td>29/09/2020 04:03 PM</td>
          <td>
            <button class="btn btn-success btn-xs"><i class="fa fa-check"></i></button>
            <button class="btn btn-info btn-xs"><i class="fa fa-user"></i></button>
            <button class="btn btn-primary btn-xs"><i class="fa fa-comments "></i></button>
            <button class="btn btn-warning btn-xs"><i class="fa fa-file-text "></i></button>
            <button class="btn btn-danger btn-xs"><i class="fa fa-trash-o "></i></button>
          </td>
        </tr>
        <tr>
          <td>8784</td>
          <td>Срочная заявка. Установка ЭЦП-Годионенко М.В.</td>
          <td>Константинова Ксения Александровна</td>
          <td>Ляушкин Ярослав</td>
          <td>20/10/2020 10:22 AM</td>
          <td>
            <button class="btn btn-success btn-xs"><i class="fa fa-check"></i></button>
            <button class="btn btn-info btn-xs"><i class="fa fa-user"></i></button>
            <button class="btn btn-primary btn-xs"><i class="fa fa-comments "></i></button>
            <button class="btn btn-warning btn-xs"><i class="fa fa-file-text "></i></button>
            <button class="btn btn-danger btn-xs"><i class="fa fa-trash-o "></i></button>
          </td>
        </tr>
        <tr>
          <td>8790</td>
          <td>RE: Удаление с диска</td>
          <td>Наталья Козлова</td>
          <td>Ляушкин Ярослав</td>
          <td>20/10/2020 03:54 PM</td>
          <td>
            <button class="btn btn-success btn-xs"><i class="fa fa-check"></i></button>
            <button class="btn btn-info btn-xs"><i class="fa fa-user"></i></button>
            <button class="btn btn-primary btn-xs"><i class="fa fa-comments "></i></button>
            <button class="btn btn-warning btn-xs"><i class="fa fa-file-text "></i></button>
            <button class="btn btn-danger btn-xs"><i class="fa fa-trash-o "></i></button>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<style scoped>
.content-panel {
  border-radius: 10px;
}
tr {
text-align: left;
color: black;
font-size: 14px
}
.btn {
  margin-left: 3px;
}
#id {
  width: 5%;
}
#theme {
  max-width: 35%;
}
#author {
  width: 15%;
}
#master {
  width: 15%;
}
#date {
  width: 15%;
}
#buttons {
  width: 15%;
}
table {
  table-layout: fixed;
  width: 100%;
  border-collapse: collapse;
}
td {
  width: auto;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}
</style>
