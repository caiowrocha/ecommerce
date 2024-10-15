# Setup do Projeto

## Link no Github

[https://github.com/caiowrocha/ecommerce](https://github.com/caiowrocha/ecommerce)

```bash
git clone <https://github.com/caiowrocha/ecommerce>
cd ecommerce
npm install
```

## Servir o projeto localmente

```bash
npm start
```

Ou

```bash
npx nx serve
```

O projeto será servido por padrão em [http://localhost:4200/](http://localhost:4200/).

## Executar tarefas independentes

[Nx: execução de tarefas](https://www.notion.so/Nx-execu-o-de-tarefas-9abeabed4689441ea381baecf96027d8?pvs=21)

```bash
npx nx <NOME_DA_TAREFA> <NOME_DO_MODULO>
```

Exemplos:

```bash
npx nx test ecommerce
npx nx lint modules-layout
```

## Visualizar Dependency Graph

[Dependency Graph: Arquitetura viva](https://www.notion.so/Dependency-Graph-Arquitetura-viva-f9a7c5c156704e46aa0dcbe8a79b1efc?pvs=21)

```bash
npx nx graph
```

## Executar tarefas somente do que foi afetado

```bash
npx nx affected:<NOME_DA_TAREFA>
```

Exemplos:

```bash
npx nx affected:test
npx nx affected:graph
```