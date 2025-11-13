# Pokémon Card Web —

Uma aplicação web estilizada como uma Pokédex que permite criar e exportar seu Pokémon Trainer Card.  
Você pode adicionar foto de treinador, escolher o nome do time, buscar Pokémon pela PokéAPI e gerar uma imagem final baixável.

---

# Funcionalidades

✔ Upload de foto do treinador  
✔ Campo para nome do treinador e nome do time  
✔ Busca Pokémon pelo nome (API: https://pokeapi.co)  
✔ Montagem automática do time em layout 2 colunas  
✔ Limite de 6 Pokémon por time  
✔ Resetar o time  
✔ Baixar a imagem final utilizando **html2canvas**  
✔ Interface temática estilo Pokédex  
✔ Placeholder automático quando nenhuma imagem é enviada  

---

# Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **PokéAPI**
- **html2canvas** para exportar o card final
- Layout inspirado em **Pokédex**

---

# Estrutura de Pastas Sugerida

/
├── index.html
├── styles.css
├── imagens/
│ ├── trainer-placeholder.png
│ ├── ... (suas outras imagens)
└── README.md


# Como Rodar o Projeto

	1. Baixe ou clone o repositório:

git clone https://github.com/usuario/repositorio.git
 	
	2. Coloque os arquivos necessários:
Imagens em imagens/

	
 	3. Abra o projeto
Basta abrir o arquivo:
index.html
em qualquer navegador.

Nenhum servidor é necessário.

 Como Subir na Nuvem (Hosting)
Este projeto pode ser hospedado:

	#GitHub Pages

Suba o repositório

Vá em Settings → Pages

Selecione a branch main

Configure a root /


	#Problemas Comuns
 *O layout some após a animação
	Solução: remover opacity: 0 e transform: scale(0.7) da classe .pokedex-frame

 *Foto não centraliza
	Solução aplicada: object-fit: cover; object-position: center;

 
	#Exemplo de Uso

Envie uma foto

Escolha nome do treinador

Digite nomes de Pokémon (ex: pikachu, charizard)

Seu time aparecerá automaticamente

Clique em Baixar Imagem.