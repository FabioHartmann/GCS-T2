# Instalando dependências

Monorepo com projetos JS utilizado como demo do 

Primeiramente para utilizar o Monorepo é necessário instalar o Lerna através do comando.

```
sudo npm install --global lerna
```

Na raíz do projeto, executar o comando:

```
lerna bootstrap --hoist
```

Assim todas as dependências de todos os projetos estão instaladas.