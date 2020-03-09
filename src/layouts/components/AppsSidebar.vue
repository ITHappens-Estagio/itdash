<template>
  <div>
    <span class="navigation-header truncate">Apps</span>
    <div class="vs-sidebar--item">
      <a href="/demo/vuesax-vuejs-admin-dashboard-template/demo-1/apps/email" class target="_self">
        <span class="feather-icon select-none relative">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24px"
            height="24px"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-mail"
          >
            <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z" />
            <polyline points="22,6 12,13 2,6" />
          </svg>
        </span>
        <span class="truncate">Email</span>
        <!---->
      </a>
    </div>

    <div class="vs-sidebar--item">
      <a href="/demo/vuesax-vuejs-admin-dashboard-template/demo-1/apps/chat" class target="_self">
        <span class="feather-icon select-none relative">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24px"
            height="24px"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-message-square"
          >
            <path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z" />
          </svg>
        </span>
        <span class="truncate">Chat</span>
        <!---->
      </a>
    </div>

    <div class="vs-sidebar--item">
      <a href="/demo/vuesax-vuejs-admin-dashboard-template/demo-1/apps/todo" class target="_self">
        <span class="feather-icon select-none relative">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24px"
            height="24px"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-check-square"
          >
            <polyline points="9 11 12 14 22 4" />
            <path d="M21 12v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11" />
          </svg>
        </span>
        <span class="truncate">Todo</span>
        <!---->
      </a>
    </div>

    <div class="vs-sidebar--item">
      <a
        href="/demo/vuesax-vuejs-admin-dashboard-template/demo-1/apps/calendar/vue-simple-calendar"
        class
        target="_self"
      >
        <span class="feather-icon select-none relative">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24px"
            height="24px"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-calendar"
          >
            <rect x="3" y="4" width="18" height="18" rx="2" ry="2" />
            <line x1="16" y1="2" x2="16" y2="6" />
            <line x1="8" y1="2" x2="8" y2="6" />
            <line x1="3" y1="10" x2="21" y2="10" />
          </svg>
        </span>
        <span class="truncate">Calendar</span>
        <!---->
      </a>
    </div>
  </div>
</template>

<script>
export default {
    name: 'AppSidebar'
}
</script>