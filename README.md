# 🌾 Calculadora de Perdas na Colheita

Aplicativo gratuito para o produtor calcular quanto grão fica no campo durante a colheita.
Funciona **offline** e pode ser **instalado no celular** (Android e iPhone), sem loja de aplicativos.

## 👉 Quero usar no meu celular (passo a passo simples)

Você **não precisa baixar nada deste site do GitHub**. É só abrir o endereço do app e instalar:

**Endereço do app:** https://eduardog360.github.io/calculadora-perdas/

### Se o seu celular é Android
1. Abra o endereço acima no **Chrome**, com internet.
2. Toque nos **três pontinhos (⋮)** no canto de cima.
3. Toque em **Instalar app** (ou **Adicionar à tela inicial**) e depois em **Instalar**.

### Se o seu celular é iPhone
1. Abra o endereço acima no **Safari** (o ícone azul de bússola). Não funciona pelo Chrome do iPhone.
2. Toque no botão **Compartilhar** (quadrado com uma seta para cima, na barra de baixo).
3. Role a lista e toque em **Adicionar à Tela de Início**, depois em **Adicionar**.

Pronto! O ícone 🌾 aparece na tela do celular. **Abra o app uma vez com internet**; depois disso ele funciona **sem sinal**, na lavoura.

> O próprio app também mostra esse passo a passo na primeira vez que você abre.

---

## Como usar

1. **Variedade:** cadastre a variedade plantada, a cultura e a produtividade esperada (sc/ha).
2. **Grãos do chão:** marque uma área atrás da colheitadeira (ex.: quadro de 1 m × 1 m), recolha os grãos caídos e informe a área (m²) e o peso (g). Dá para adicionar várias amostras; o app usa a média.
3. **Áreas:** informe a área total e a área que falta colher (ha).
4. Toque em **CALCULAR**.

O app mostra a perda em kg/ha e sc/ha, a porcentagem sobre a produtividade, a perda em kg na área que falta e o quanto isso representa da produção da área total. O botão **Compartilhar imagem** gera uma imagem para enviar ou arquivar.

## Fórmulas

- Perda (kg/ha) = g/m² × 10
- Perda (%) = perda por hectare ÷ produtividade esperada × 100
- Perda na área que falta (kg) = perda por hectare × área que falta (ha)
- Perda da área que falta em relação à produção total (%) = perda na área que falta ÷ (área total × produtividade esperada) × 100

## Instalar no celular

Abra o endereço do app no navegador e use **Instalar** (Android/Chrome) ou **Compartilhar → Adicionar à Tela de Início** (iPhone/Safari). Depois da primeira abertura, funciona sem internet.

## Publicar sua própria cópia (GitHub Pages)

1. Faça um fork ou baixe este repositório.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. O app ficará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Ao alterar qualquer arquivo, aumente a `VERSAO` em `sw.js` para os celulares receberem a atualização.

## Privacidade

Nenhum dado sai do aparelho. Variedades e medidas ficam salvas só no navegador do usuário.

## Licença

[MIT](LICENSE): uso, cópia e modificação livres e gratuitos.
