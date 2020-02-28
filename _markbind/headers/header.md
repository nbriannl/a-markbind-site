<header>
  <navbar type="light">
    <a slot="brand" href="{{baseUrl}}/index.html" title="Home" class="navbar-brand">nbriannl.github.io</a>
    <!-- <dropdown header="Projects" class="nav-link">
      <li><a href="{{baseUrl}}/projects/oboeru.html" class="dropdown-item">Oboeru</a></li>
    </dropdown> -->
    <li><a href="{{baseUrl}}/contents/summary.html" class="nav-link">My Summary</a></li>
    <li><a href="{{baseUrl}}/contents/markbind-overview.html" class="nav-link">Markbind Overview</a></li>
    <li><a href="{{baseUrl}}/minoni.html" class="nav-link">Minna no Nihongo</a></li>
    <!-- <li><a href="{{baseUrl}}/contents/topic2.html" class="nav-link">Topic 2</a></li> -->
    <li><a href="https://nbriannl.github.io/" class="nav-link">Back to Main Site</a></li>
    <a href="https://github.com/nbriannl/" target="_blank" class="nav-link"><md>:fab-github:</md></a>
    <li slot="right">
      <form class="navbar-form">
        <searchbar :data="searchData" placeholder="Search" :on-hit="searchCallback" menu-align-right></searchbar>
      </form>
    </li>
  </navbar>
</header>
