HTML:
 <nav class="nav container">
      <img class="nav__img" src="images/logo.svg" alt="logo image">
      <div class="nav__ham"><img src="images/icon-menu.svg" alt=""></div> <!--esta imagen cambiara de estado dandole clik o no de ham a "X"-->
</nav>
 - El div en el nav-ham se utiliza como medio modificador del menu ham y el icono para cerrar o "X"...
*************************************************************************************************
 <div class="nav__overlay">  
      <ul class="nav__menu">
        <li class="nav__item">
          <span class="nav__parent">
            Features
            <img class="nav__arrow" src="images/icon-arrow-down.svg" alt="arrow icon">
          </span>
          <ul class="nav__inner">
            <li class="nav__dropdown">
              <a href="#" class="nav__link">
                <img class="nav__illustration" src="images/icon-todo.svg" alt="todo icon">
                Todo List
              </a>
            </li>
            <li class="nav__dropdown">
              <a href="#" class="nav__link">
                <img class="nav__illustration" src="images/icon-calendar.svg" alt="todo icon">
                Calendar
              </a>
            </li>
            <li class="nav__dropdown">
              <a href="#" class="nav__link">
                <img class="nav__illustration" src="images/icon-reminders.svg" alt="todo icon">
                Reminder 
              </a>
            </li>
            <li class="nav__dropdown">
              <a href="#" class="nav__link">
                <img class="nav__illustration" src="images/icon-planning.svg" alt="todo icon">
                Planning
              </a>
            </li>
          </ul>
        </li>
      </ul>
    </div>

    + la clase overlay en el div nos servira para hacer el display de la capa negra cuando se dispare el menu ham
    + ul. nav__menu es un li de una ul llamada Features el cual a su vez contiene una lista con los items todo calendar etc... 
    +notece que los li tienen submenu que a su vez usan span