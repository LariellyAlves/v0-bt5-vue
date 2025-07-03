<script setup lang="ts">
import Footer from "@/components/FooterBar.vue";
import { useI18n } from "vue-i18n";
const { t } = useI18n();

const downloadPDF = () => {
  const pdfUrl = '/files/matriz-curricular.pdf';
  const link = document.createElement('a');
  link.href = pdfUrl;
  link.download = 'matriz-curricular.pdf';
  document.body.appendChild(link);
  link.click();
  document.body.removeChild(link);
};

</script>

<template>
  <div class="container mt-5">
    <!-- Primeiro título -->
    <h1 class="mb-4 text-start">{{ t("aboutPage.title") }}</h1>

    <!-- Parágrafos -->
    <div class="about-text">
      <p v-html="t('aboutPage.paragraph1')"></p>
      <p v-html="t('aboutPage.paragraph2')"></p>
      <p v-html="t('aboutPage.paragraph3')"></p>
      <p v-html="t('aboutPage.paragraph4')"></p>
    </div>

    <!-- Segundo título e imagem -->
    <div class="imagem-section mt-5">
      <h2 v-html="t('aboutPage.subtitle')" class="subtitulo"></h2>
      <img
        src="https://i.imgur.com/VwMUxeT.jpeg"
        alt="Matriz Curricular"
        class="imagem-matriz"
      />

      <button class="btn btn-primary mt-3 btn-download" @click="downloadPDF"><i class="bi bi-download" style="margin-right: 5px;"></i>PDF</button>
    </div>
  </div>
  <Footer />
</template>

<style scoped>
h1 {
  font-family: "Oswald", serif;
  font-size: 2rem;
  margin-bottom: 1.5rem;
}

.about-text {
  font-size: 1rem;
  line-height: 1.5rem;
  text-align: left;
}

.subtitulo {
  font-family: "Oswald", serif;
  font-size: 1.5rem;
  margin-bottom: 1rem;
  text-align: left;
}

.imagem-matriz {
  width: 100%;
  max-width: 700px;
  border-radius: 10px;
  display: block;
  margin: 0 auto 2rem auto;
}

.btn-download {
  width: 50%;
  height: 50px;
  display: block;
  margin: 1rem auto 1rem auto;
  background-color: #ffbe00;
  border: none;
  color: black;
}
</style>
