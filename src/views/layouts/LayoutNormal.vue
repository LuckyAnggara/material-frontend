<script>
import NavBar from './NavBar.vue'
import MainContent from './MainContent.vue'
import Footer from './Footer.vue'
import Title from './Title.vue'
export default {
  setup() {},
  components: { NavBar, MainContent, Footer, Title },
}
</script>

<template>
  <div class="md:flex flex-col justify-between">
    <NavBar />
    <Title />
    <!-- <aside
      class="fixed top-0 left-0 z-40 w-64 h-screen pt-14 transition-transform -translate-x-full bg-white border-r border-gray-200 md:translate-x-0"
      aria-label="Sidenav"
      id="drawer-navigation"
    >
      <div class="overflow-y-auto py-5 px-3 h-full =">
        <ul class="menu bg-base-200 rounded-box w-56">
          <li>
            <h2 class="menu-title">Title</h2>
            <ul>
              <li><a>Item 1</a></li>
              <li><a>Item 2</a></li>
              <li><a>Item 3</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </aside> -->
    <MainContent />
    <Footer class="self-end"></Footer>
  </div>
</template>
