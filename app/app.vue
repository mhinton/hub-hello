<template>
  <NuxtRouteAnnouncer />
  <NuxtLoadingIndicator />
  <nav>
    <ul>
      <li>
        <NuxtLink to="/">
          home
        </NuxtLink>
      </li>
      <li>
        <NuxtLink to="/demo">
          demo
        </NuxtLink>
      </li>
    </ul>
  </nav>
  <NuxtPage />
</template>
