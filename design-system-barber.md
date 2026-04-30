{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Barber Booking \'97 Design System\
\
Sistema de design b\'e1sico do app de agendamento de barbearia. Tema escuro com acento dourado.\
\
---\
\
## Cores\
\
| Token | Hex | Uso |\
|---|---|---|\
| `background` | `#161616` | Fundo geral do app |\
| `card` | `#232323` | Cart\'f5es / containers principais |\
| `secondary` | `#2A2A2A` | Inputs, bot\'f5es de \'edcone, chips inativos |\
| `primary` | `#D4A437` | Cor de marca (dourado) \'97 bot\'f5es, destaques, item ativo |\
| `primaryForeground` | `#181818` | Texto/\'edcones sobre fundo `primary` |\
| `text` | `#FFFFFF` | Texto principal |\
| `muted` | `#9A9A9A` | Texto secund\'e1rio, \'edcones inativos |\
| `border` | `#2D2D2D` | Bordas, divis\'f3rias, pontos do paginador |\
| `tabBar` | `#1F1F1F` | Fundo da barra de navega\'e7\'e3o flutuante |\
\
---\
\
## Tipografia\
\
Fam\'edlia: **Inter** (Google Fonts)\
\
| Estilo | Tamanho | Peso | Uso |\
|---|---|---|---|\
| Display | 32 / 38 | 700 | T\'edtulo de onboarding |\
| Title | 22 | 700 | Nome do barbeiro |\
| Section | 17 | 700 | T\'edtulos de se\'e7\'e3o ("Best category", "Special offers") |\
| Subtitle | 16 | 600 | "Choose style", t\'edtulo do bot\'e3o principal |\
| Body | 14 | 500 / 600 | Texto geral, labels, inputs |\
| Caption | 13 | 500 | Fun\'e7\'e3o/cargo, "See all" |\
| Small | 12 | 500 / 600 | Labels de estat\'edsticas, chips |\
| Micro | 11 | 600 | Labels de categorias, rating |\
\
---\
\
## Espa\'e7amento\
\
Base de **4 px**. Escala usada:\
\
`4 \'b7 6 \'b7 8 \'b7 10 \'b7 12 \'b7 14 \'b7 16 \'b7 18 \'b7 22 \'b7 24 \'b7 28 \'b7 32`\
\
- Padding interno de cart\'e3o: **18 px**\
- Padding lateral de tela: **16 px**\
- Espa\'e7o entre se\'e7\'f5es: **22 px**\
\
---\
\
## Raio de borda (radius)\
\
| Token | Valor | Uso |\
|---|---|---|\
| `xs` | 12 px | Tag de rating |\
| `sm` | 18\'9619 px | Chips, bot\'f5es pequenos |\
| `md` | 24 px | Cart\'e3o de oferta |\
| `lg` | 28\'9632 px | Cart\'e3o principal |\
| `xl` | 36\'9648 px | Container do "device" / cart\'e3o grande |\
| `pill` | 999 px | Bot\'f5es CTA, barra de tabs, busca, avatar |\
\
---\
\
## Componentes\
\
### Bot\'e3o prim\'e1rio (CTA)\
- Fundo `primary` (`#D4A437`), texto `primaryForeground`\
- Altura **54\'9658 px**, raio **pill**\
- Peso 600, tamanho 15\'9616\
- \'cdcone opcional \'e0 direita (seta)\
\
### Bot\'e3o secund\'e1rio\
- Fundo transparente, borda `border`, texto `text`\
- Mesma altura do CTA\
\
### Bot\'e3o de \'edcone\
- 40\'9644 px c\'edrculo, fundo `secondary`\
- \'cdcone 16\'9618 px\
\
### Chip\
- Altura 36 px, raio 18 px, padding lateral 14 px\
- Inativo: texto `muted`, fundo transparente\
- Ativo: fundo `primary`, texto `primaryForeground`, peso 600\
\
### Cart\'e3o (card)\
- Fundo `card`, raio 28\'9632 px, padding 18 px\
\
### Categoria (\'edcone circular)\
- C\'edrculo de 56 px, fundo `secondary`, borda `border` 1 px\
- Ativo: fundo e borda `primary`, \'edcone em `primaryForeground`\
- Label abaixo, 11 px\
\
### Cart\'e3o de oferta\
- 290 \'d7 180 px, raio 24 px\
- Imagem de fundo + gradiente preto inferior\
- Tag de rating no topo esquerdo (preto transl\'facido)\
- Bot\'e3o "Book now" no canto inferior direito\
\
### Avatar\
- Padr\'e3o: 44 px c\'edrculo\
- Perfil grande: 110 px com anel `primary` 2 px e padding 3 px\
\
### Barra de navega\'e7\'e3o (tab bar)\
- Flutuante, fundo `tabBar` (`#1F1F1F`), raio **pill**\
- Altura 70 px, margem inferior 16 px\
- Item ativo: fundo `primary` em p\'edlula, com **ponto** indicador ao lado do \'edcone\
- Itens inativos: \'edcones `muted` 20 px\
\
### Indicador de pagina\'e7\'e3o (dots)\
- Inativo: 6 \'d7 6 px, `border`\
- Ativo: 18 \'d7 6 px, `text`\
\
---\
\
## Telas\
\
1. **Onboarding** \'97 imagem em tela cheia, gradiente preto inferior, t\'edtulo grande, subt\'edtulo, CTA "Get started".\
2. **Home** \'97 header com avatar + localiza\'e7\'e3o + sino de notifica\'e7\'e3o, busca + filtro, categorias horizontais, ofertas em carrossel, dots, tab bar flutuante.\
3. **Perfil do Barbeiro** \'97 voltar + menu, avatar com anel dourado, nome + fun\'e7\'e3o, 3 estat\'edsticas (Experience / Rating / Customers), Follow + Message, chips de servi\'e7o, grade 2\'d72 de estilos com numera\'e7\'e3o dourada, CTA "Book now".\
\
---\
\
## Iconografia\
\
- Fam\'edlia: **Feather Icons** (linhas 2 px, termina\'e7\'f5es arredondadas)\
- Tamanho padr\'e3o: 18\'9620 px\
- Cor: `text` ou `muted` conforme estado\
}