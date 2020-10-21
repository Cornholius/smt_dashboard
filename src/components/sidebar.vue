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
            <li><a href="blank.html">Создать новую запись</a></li>
          </ul>
        </li>
        <li class="sub-menu">
          <a href="javascript:;">
            <i class="fa fa-tasks"></i>
            <span>Заявки</span>
            </a>
          <ul class="sub">
            <li><a href="form_component.html">Все заявки</a></li>
            <li><a href="advanced_form_components.html">Открытые заявки</a></li>
            <li><a href="form_validation.html">Мои заявки</a></li>
          </ul>
        </li>
        <li>
          <router-link to="Home">
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
