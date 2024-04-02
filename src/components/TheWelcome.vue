<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <TENTANG SAYAicon />
    </template>
    <template #heading>TENTANG SAYA</template>

    
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    Saya adalah seorang mahasiswi di Universitas Islam Riau.Saya lahir pada tanggal 16 november 2003 di dusun IV kasikan. Saya dari fakultas teknik prodi teknik informatika.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <PENDIDIKANIcon />
    </template>
    <template #heading>PENDIDIKAN</template>

    
   - 2010 - 2016
    SDN 020 KASIKAN

   <br> - 2016 - 2019
    SMP YP2TG KASIKAN

    <br>- 2019 - 2022 
    SMAN 01 TAPUNG HULU

    


    <br />

   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <HobiIcon />
    </template>
    <template #heading>Hobi</template>

    Hoby saya adalah membaca.Saya juga suka mendengar musik dengan genre pop dan dj.
    saya juga suka memasak karna saya suka ngemil.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <KeahlianIcon />
    </template>
    <template #heading> Keahlian</template>

    -Kerjasama Tim
    <br>-Manajemen waktu
    <br>-Kreatif
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <KontakIcon />
    </template>
    <template #heading>Kontak</template>

    Telp  : 082392931774
    <br>ig    : @elfrda_16
    <br>email : elfridabrmarbun@student.uir.ac.id
  </WelcomeItem>
</template>
