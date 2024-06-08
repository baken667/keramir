<script setup lang="ts"></script>
<template>
  <div class="w-full grow h-full flex flex-col items-center justify-center">
    <div class="mb-8">
      <CompanyLogo imgLink="/logo.jpg" />
    </div>
    <h2 class="text-2xl font-bold">Привет от Керамир!</h2>
    <div class="mt-4 flex flex-col gap-2 items-stretch w-full max-w-xs">
      <CompanyButton href="tel:+77000212034">
        +7 (700) 021 20-34
      </CompanyButton>
      <CompanyButton
        href="https://kuula.co/share/collection/7cTzh?logo=0&info=1&fs=1&vr=0&sd=1&thumbs=1"
      >
        Панорамы с нашей плиткой
      </CompanyButton>
    </div>
    <div class="mt-4 divide-y">
      <InfoItem label="Адрес:">
        Auezov City, проспект Райымбека, 210/12 к2
      </InfoItem>
    </div>
    <div class="mt-4 flex flex-row gap-4">
      <SocialLinkIcon link="https://www.instagram.com/keramir_ala">
        <IconInstagram class="w-16 h-auto" />
      </SocialLinkIcon>
      <SocialLinkIcon link="https://wa.me/77000212035">
        <IconWhatsapp class="w-16 h-auto" />
      </SocialLinkIcon>
    </div>
  </div>
</template>
