# dicas-desenvolvimento


## Carousel leve e diverso
https://swiffyslider.com/examples/


## Atualiza todos as libs do Package.json

Para versões mais atuais do NPM

```
npm outdated                     # verifica dependências que possuem atualização
npm update                       # atualiza dependências
npm install                      # instala dependências
```

```
yarn upgrade-interactive --latest   # atualiza dependências selecionadas
yarn upgrade --latest               # atualiza dependências
```

Ou utilizando o npm-check-updates

```
npm install -g npm-check-updates # instala o npm-check-updates de forma global
npm-check-updates                # verifica dependências que possuem atualização
ncu -u                           # atualiza dependências
npm install                      # instala dependências
```

```
npx npm-check-updates -u         # utiliza a última versão do npm-check-updates atualiza dependências
npm install                      # instala dependências
```