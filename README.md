# Aula GIT

![Logo do Git](./assets/img/logo_git.png)

Para baixar o Git entre no [link](https://git-scm.com/downloads)

## Após instalação
Sempre *configurar* as credênciais do **Git**.

```bash
git config --global user.name "Seu nome"
git config --global user.email seu@email
```

## Inicializar uma pasta com o git
```bash
git init
```

## Adicinoar arquivos para gerar uma versão do git

```bash
git add nome_do_arquivo
```

## Para gerar uma versão

```bash
git commit -m "Uma mensagem do que foi feito"
```

## Verificar arquivos que foram alterados

```bash
git status
```

## Verificar o log das modificações

```bash
git log
```

# Comandos basicos do Linux

## Entrar em uma pasta
```bash
cd nome_da_pasta
```

## Listar o conteúdo de uma pasta
```bash
ls nome_da_pasta
```

## Criar uma pasta
```bash
mkdir nome_da_pasta
```

## Excluir uma pasta
```bash
rm -r nome_da_pasta
```

## Renomear um arquivo
```bash
mv nome_atual_do_arquivo nome_novo_do_arquivo
```

## Mover uma arquivo de lugar
```bash
mv nome_do_arquivo caminho_da_pasta/
```

## Copiar um arquivo
```bash
cp nome_do_arquivo caminho_da_pasta_de_destino/
```