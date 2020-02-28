<header>
  <navbar type="dark">
    <a slot="brand" href="{{baseUrl}}/minoni.html" title="Home" class="navbar-brand">Minna no Nihongo Fansite</a>
    <li><a href="{{baseUrl}}/minoni/overview.html" class="nav-link">Overview</a></li>
    <!-- <li><a href="{{baseUrl}}/contents/topic2.html" class="nav-link">Topic 2</a></li> -->
    <dropdown header="Characters" class="nav-link">
      <li><a href="{{baseUrl}}/minoni/miller.html" class="dropdown-item">Mike Miller</a></li>
    </dropdown>
    <li slot="right">
      <form class="navbar-form">
        <searchbar :data="searchData" placeholder="Search" :on-hit="searchCallback" menu-align-right></searchbar>
      </form>
    </li>
  </navbar>
</header>
