<template>
  <div class="NewNavbar">
    <div class="ntheader"></div>
    <div class="ntmenu">
      <div class="container">
        <div class="Navtop-menu-in">
          <ul class="Navtop-menu-inner">
            <li class="Navtop-menu-item">
              <a href=""><i class="fas fa-home"></i></a>
            </li>
            <li class="Navtop-menu-item"><a href="">Spor</a></li>
            <li class="Navtop-menu-item"><a href="">Live</a></li>
            <li class="Navtop-menu-item"><a href="">Poker</a></li>
          </ul>
          <ul class="Navtop-menu-right">
            <li class="Navtop-menu-right-item">
              <a href=""><i class="fas fa-home"></i></a>
            </li>
            <li class="Navtop-menu-right-item"><a href="">icon</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.NewNavbar {
  background-color: #f2f3f8;
  height: 136px;
}
.ntheader {
  height: 84px;
}
.NewNavbar .ntmenu {
  height: 52px;
  background-color: #424757;
  display: flex;
  align-items: center;
  justify-content: center;
}
.NewNavbar .ntmenu .Navtop-menu-in {
  display: flex;
  justify-content: space-between;
}
.NewNavbar .ntmenu .Navtop-menu-in .Navtop-menu-inner {
  display: flex;
  justify-content: space-between;
  flex-grow: 2;
}

.NewNavbar .ntmenu .Navtop-menu-in .Navtop-menu-right {
  display: flex;
  justify-content: flex-end;
  flex-grow: 1;
  align-items: center;
}
.NewNavbar
  .ntmenu
  .Navtop-menu-in
  .Navtop-menu-inner
  .Navtop-menu-item:first-child {
  width: 52px;
}

.NewNavbar .ntmenu .Navtop-menu-in .Navtop-menu-inner .Navtop-menu-item {
  position: relative;
  height: 52px;
  flex-grow: 2;
  text-align: center;
  line-height: normal;
}
.NewNavbar
  .ntmenu
  .Navtop-menu-in
  .Navtop-menu-right
  .Navtop-menu-right-item:first-child {
  border-left: 1px solid #595e6f;
}
.NewNavbar .ntmenu .Navtop-menu-in .Navtop-menu-right .Navtop-menu-right-item {
  position: relative;
  height: 100%;
  width: 53 px;
  border-right: 1 px solid #595e6f;
  transition: 500ms;
}
.NewNavbar
  .ntmenu
  .Navtop-menu-in
  .Navtop-menu-right
  .Navtop-menu-right-item
  a {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.Navtop-menu-item a {
  position: relative;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 16px;
  font-weight: normal;
  text-decoration: none;
  transition: 500ms;
}
.Navtop-menu-item a i {
  font-size: 28px;
}
.Navtop-menu-item a:hover {
  background-color: #787e94;
}
</style>
