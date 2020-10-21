<template>
  <aside>
    <div id="sidebar" class="nav-collapse">
      <ul class="sidebar-menu" id="nav-accordion">
        <li class="mt">
          <router-link class="active" to="/">
            <i class="fa fa-dashboard"></i>
            <span>Dashboard</span>
            </router-link>
        </li>
        <li class="sub-menu">
          <a href="javascript:;">
            <i class="fa fa-book"></i>
            <span>Локальная Вики</span>
            </a>
          <ul class="sub">
            <li><router-link to="/wiki">Все записи</router-link></li>
            <li><router-link to="blank.html">Создать новую запись</router-link></li>
          </ul>
        </li>
        <li class="sub-menu">
          <a href="javascript:;">
            <i class="fa fa-tasks"></i>
            <span>Заявки</span>
            </a>
          <ul class="sub">
            <li><router-link to="/requests">Все заявки</router-link></li>
            <li><router-link to="form_validation.html">Мои заявки</router-link></li>
            <li><router-link to="advanced_form_components.html">Открытые заявки</router-link></li>
            <li><router-link to="advanced_form_components.html">Закрытые заявки</router-link></li>
          </ul>
        </li>
        <li>
          <router-link to="/mail">
            <i class="fa fa-envelope"></i>
            <span>Почта</span>
            <span class="label label-theme pull-right mail-info">2</span>
          </router-link>
        </li>
      </ul>
    </div>
  </aside>
</template>

<script>
export default {
  name: 'Sidebar'
}
</script>
