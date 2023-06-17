
<template>
  <div>
    <section id="header">

    <!-- Hamburger -->
    <div id="hamburger">
        <svg width="30" height="30" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M5 17h14M5 12h14M5 7h14" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
    </div>

    <!-- Search -->
    <div>
      <svg id="SearchIcon" xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" viewBox="0 0 24 24"><path stroke="#fff" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m15 15 6 6m-11-4a7 7 0 1 1 0-14 7 7 0 0 1 0 14Z"/></svg>

      <input id="search" type="text" placeholder="  Search here" />
    </div>

    <!-- Option Icon -->
    <div>
      <svg id="option_icon" xmlns="http://www.w3.org/2000/svg" width="33" height="33" fill="none" viewBox="0 0 24 24"><g stroke="#fff" stroke-linecap="round" stroke-linejoin="round" stroke-width=".864"><path d="m9.395 19.371.584 1.315a2.213 2.213 0 0 0 4.045 0l.584-1.315a2.426 2.426 0 0 1 2.47-1.423l1.43.152a2.212 2.212 0 0 0 2.023-3.502l-.847-1.164a2.43 2.43 0 0 1-.46-1.434c0-.513.162-1.014.464-1.429l.847-1.163a2.21 2.21 0 0 0-.785-3.274 2.212 2.212 0 0 0-1.237-.228l-1.43.152a2.434 2.434 0 0 1-1.47-.312 2.426 2.426 0 0 1-1-1.117l-.59-1.315a2.212 2.212 0 0 0-4.044 0L9.395 4.63c-.207.468-.557.86-1 1.117-.445.256-.96.365-1.47.312l-1.434-.152a2.212 2.212 0 0 0-2.023 3.502l.847 1.163a2.43 2.43 0 0 1 0 2.858l-.847 1.163a2.21 2.21 0 0 0 .786 3.273c.381.195.811.274 1.237.23l1.43-.153a2.434 2.434 0 0 1 2.474 1.43Z"/><path d="M12 15a3 3 0 1 0 0-6 3 3 0 0 0 0 6Z"/></g></svg>
    </div>

    <!-- Notification Icon -->
      <div>
        <svg id="notification" fill="#13B497" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" width="14px" height="14px" viewBox="0 0 502.001 632.001"><path d="M456.195 384.32h-32.372V233.958c0-85.827-64.763-156.798-147.983-166.646V19.84C275.84 8.883 266.957 0 256 0s-19.84 8.883-19.84 19.84v47.472c-83.221 9.847-147.983 80.819-147.983 166.646v150.364H55.804c-10.957 0-19.84 8.883-19.84 19.84s8.883 19.84 19.84 19.84h142.97v30.773c0 31.554 25.672 57.227 57.227 57.227s57.227-25.672 57.227-57.227v-30.773h142.97c10.957 0 19.84-8.883 19.84-19.84s-8.886-19.842-19.843-19.842zm-200.197 88c-9.675 0-17.547-7.871-17.547-17.547V424h35.092v30.773h.001c.001 9.674-7.871 17.547-17.546 17.547zm128.144-87.999h-106.63v-.001H127.856V233.958c0-70.658 57.484-128.144 128.143-128.144S384.142 163.3 384.142 233.958v150.363z"/></svg>
      </div>

      <!-- Chat Icon -->
      <div>
        <svg id="chat_icon" width="14px" height="14px" viewBox="0 0 25 25" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M9 11h6m-7.876 7.701L5.6 19.921c-.833.665-1.249.998-1.599.998a1 1 0 0 1-.783-.376C3 20.27 3 19.737 3 18.671V7.201c0-1.12 0-1.681.218-2.11.192-.376.497-.681.874-.873C4.52 4 5.08 4 6.2 4h11.6c1.12 0 1.68 0 2.107.218.377.192.683.497.875.874.218.427.218.987.218 2.105v7.607c0 1.117 0 1.676-.218 2.104a2 2 0 0 1-.874.874c-.427.218-.987.218-2.105.218h-8.68c-.417 0-.624 0-.823.04a2.004 2.004 0 0 0-.508.179c-.18.091-.34.22-.657.474l-.011.008Z" stroke="#13B497" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </div>

      <!-- Gift Icon -->
        <div>
          <svg id="gift_icon" xmlns="http://www.w3.org/2000/svg" width="14px" height="px" fill="none" viewBox="0 0 24 24"><g stroke="#8D98A4" stroke-linejoin="round" stroke-width=".888"><path d="M3 9.5c0-.465 0-.697.038-.89A2 2 0 0 1 4.61 7.038C4.803 7 5.035 7 5.5 7h13c.465 0 .697 0 .89.038a2 2 0 0 1 1.572 1.572c.038.193.038.425.038.89s0 .697-.038.89a2 2 0 0 1-1.572 1.572c-.193.038-.425.038-.89.038h-13c-.465 0-.697 0-.89-.038a2 2 0 0 1-1.572-1.572C3 10.197 3 9.965 3 9.5Z"/><path stroke-linecap="round" d="M4 12v4c0 1.886 0 2.828.586 3.414C5.172 20 6.114 20 8 20h8c1.886 0 2.828 0 3.414-.586C20 18.828 20 17.886 20 16v-4M12 7v13M11.375 6.22l-1.98-2.475a2.002 2.002 0 0 0-2.977-.163C5.158 4.842 6.047 7 7.828 7H11a.48.48 0 0 0 .375-.78ZM12.625 6.22l1.98-2.475a2.002 2.002 0 0 1 2.977-.163c1.26 1.26.371 3.418-1.41 3.418H13a.48.48 0 0 1-.375-.78Z"/></g></svg>
        </div>

        <!-- User Section -->
        <div>
          <!-- User Icon -->
          <svg id="user_icon" width="14px" height="14px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M18 18.702C18 15.671 14.5 15 12 15s-6 .67-6 3.702M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Zm-6-3a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z" stroke="#fff" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg>

          <h5 id="user_name">Emmanuel Berrio</h5>

          <!-- Arrow icon -->
          <svg  id="user_arrow" width="20px" height="20px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" transform="scale(1 -1)"><path d="m18.68 13.978-3.21-3.21-1.96-1.97a2.13 2.13 0 0 0-3.01 0l-5.18 5.18c-.68.68-.19 1.84.76 1.84h11.84c.96 0 1.44-1.16.76-1.84Z" fill="#D3D6E4"/></svg>
        </div>
    </section>

    <section id="dashboard">
      <p>Dasboard/</p>
    </section>
  </div>
</template>

<script>
    export default {
      name: "Header",
    };
</script>
