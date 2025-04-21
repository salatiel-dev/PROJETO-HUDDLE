# 💬 Projeto Huddle Landing Page

Este é um clone da **landing page do Huddle**, desenvolvido com foco em treinar **HTML5**, **CSS3**
🔗 Acesse o repositório: [PROJETO-HUDDLE](https://github.com/salatiel-dev/PROJETO-HUDDLE)

## 🖼️ Preview

<style>
  .image-gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    padding: 20px;
  }

  .image-item {
    text-align: center;
    max-width: 300px;
  }

  .image-item img {
    width: 100%;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s ease;
  }

  .image-item img:hover {
    transform: scale(1.05);
  }

  .image-caption {
    margin-top: 8px;
    font-size: 14px;
    color: #555;
  }

  @media (max-width: 600px) {
    .image-gallery {
      flex-direction: column;
      align-items: center;
    }

    .image-item {
      width: 90%;
    }
  }
</style>

<div class="image-gallery">
  <div class="image-item">
    <img src="https://github.com/user-attachments/assets/cd924599-9b20-4ee9-9af4-2356704d3543" alt="Imagem 1" />
    <div class="image-caption">Legenda da imagem 1</div>
  </div>
  <div class="image-item">
    <img src="https://github.com/user-attachments/assets/b18e3fd6-0c56-4232-8a35-237c24037630" alt="Imagem 2" />
    <div class="image-caption">Legenda da imagem 2</div>
  </div>
</div>


## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3

## 🧱 Estrutura do layout

O layout foi dividido em três áreas.

- `header`: área superior com o logotipo.
- `main`: seção central com imagem, texto de destaque e botão.
- `footer`: rodapé com os ícones das redes sociais.

## 🚀 Como executar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/salatiel-dev/PROJETO-HUDDLE.git
