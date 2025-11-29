<script setup>
import CategoryPage from "@/components/CategoryPage.vue";

const shorts = [
  {
    id: 9,
    title: "Short Jeans Casual",
    image:
      "https://a-static.mlcdn.com.br/450x450/short-jeans-fashion-casual-confortavel-fortaleza-jeans/mlmodasvariedades/29199-0001-3/07f073ab5079538837be601a55fe8583.jpeg",
    price: "90,00",
  },
  {
    id: 10,
    title: "Short de Sarja Branca",
    image:
      "https://a-static.mlcdn.com.br/450x450/short-jeans-feminino-branco-desfiado-cintura-alta-casual-zafina/zafina/mxd2878br44/9c038e9b4b7b2e6c914f60b5d38757fe.jpeg",
    price: "110,00",
  },
  {
    id: 18,
    title: "Short Jeans com Pérolas",
    image: "https://down-br.img.susercontent.com/file/03b8a3fce9b0c861055b08688a59ee9e",
    price: "150,00",
  },
  {
    id: 11,
    title: "Short de Linho Bege",
    image:
      "https://a-static.mlcdn.com.br/1500x1500/shorts-feminino-lunender-linho-bege-impala-39139/estrelacalcadoseconfeccoes/978751-m/bcfc86dfcbb475a9be8335c24df21ea2.jpeg",
    price: "120,00",
  },
  {
    id: 17,
    title: "Short Listrado com Amarração",
    image:
      "https://images-americanas.b2w.io/produtos/6014124047/imagens/short-cintura-alta-feminino-listrado-amarracao/6014124063_1_large.jpg",
    price: "100,00",
  },
  {
    id: 12,
    title: "Short Esportivo Preto",
    image: "https://imgcentauro-a.akamaihd.net/1366x1366/M0Q5BU50.jpg",
    price: "70,00",
  },
];
</script>

<template>
  <CategoryPage
    eyebrow="Coleção cápsula"
    title="Shorts para todas as ocasiões"
    highlight="Silhuetas leves, tecidos respiráveis e detalhes pensados para o verão brasileiro."
    description="Modelagens de cintura alta, alfaiataria contemporânea e lavagem premium para acompanhar do passeio à noite especial."
    gallerySubtitle="Seleção limitada com entrega expressa para todo o Brasil."
    heroImage="/src/assets/imgs/shorts-hero.png"
    :products="shorts"
  />
</template>
