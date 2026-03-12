````markdown
# Criação de Páginas Estáticas no GitHub

## 1. O que são Páginas Estáticas

**Páginas estáticas** são páginas web compostas por arquivos que não dependem de processamento no servidor para gerar conteúdo dinamicamente. Elas são formadas principalmente por arquivos como:

- HTML
- CSS
- JavaScript
- imagens e outros arquivos estáticos

Diferente de aplicações dinâmicas, nas páginas estáticas o conteúdo é **entregue diretamente ao navegador do usuário**, sem necessidade de processamento adicional em um servidor.

Essas páginas são ideais para:

- portfólios
- documentações
- sites institucionais simples
- páginas pessoais
- páginas de projetos

---

## 2. O que é o GitHub Pages

O **GitHub Pages** é um serviço oferecido pelo GitHub que permite **publicar páginas estáticas diretamente a partir de um repositório**.

Com ele, desenvolvedores podem hospedar um site gratuitamente usando os arquivos armazenados no repositório.

Ao ativar o GitHub Pages, o conteúdo do projeto passa a ser acessível através de uma URL pública, geralmente no formato:

```
https://usuario.github.io/nome-do-repositorio
```

Esse recurso é muito utilizado para publicar:

- documentações de projetos
- portfólios de desenvolvedores
- páginas de apresentação de projetos
- blogs estáticos

---

## 3. Estrutura Básica de uma Página Estática

Para criar uma página estática simples, normalmente é necessário pelo menos um arquivo **HTML** que servirá como página principal do site.

O arquivo principal costuma se chamar:

```
index.html
```

Exemplo de uma estrutura simples de página:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Meu Site</title>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Esta é minha página hospedada no GitHub Pages.</p>
</body>
</html>
```

Esse arquivo define o conteúdo que será exibido no navegador.

---

## 4. Criando uma Página Estática no GitHub

O processo para publicar uma página estática no GitHub normalmente envolve algumas etapas.

### 1. Criar um repositório no GitHub

Primeiro, é necessário criar um novo repositório no GitHub.

O repositório armazenará os arquivos do site.

---

### 2. Adicionar os arquivos do site

Depois de criar o repositório, devem ser adicionados os arquivos da página, como:

- `index.html`
- arquivos CSS
- arquivos JavaScript
- imagens

Esses arquivos podem ser enviados utilizando Git.

Exemplo:

```bash
git add .
git commit -m "Adiciona página inicial"
git push origin main
```

---

### 3. Ativar o GitHub Pages

Após enviar os arquivos, é possível ativar o GitHub Pages nas configurações do repositório.

O processo geralmente envolve:

1. Acessar **Settings** do repositório
2. Ir até a seção **Pages**
3. Selecionar a branch que contém os arquivos do site (geralmente `main`)
4. Salvar as configurações

Depois disso, o site será publicado automaticamente.

---

## 5. Atualizando o Site

Sempre que alterações forem feitas nos arquivos do projeto e enviadas para o repositório, o GitHub Pages **atualizará automaticamente o site publicado**.

Exemplo de atualização:

```bash
git add .
git commit -m "Atualiza conteúdo da página"
git push origin main
```

Após alguns instantes, as mudanças estarão visíveis no site.

---

## 6. Vantagens do GitHub Pages

O uso do GitHub Pages oferece diversas vantagens:

- hospedagem gratuita
- integração direta com repositórios Git
- facilidade de atualização do site
- ideal para projetos simples
- controle de versão do conteúdo

Essas características tornam o serviço muito útil para desenvolvedores que desejam **publicar páginas web rapidamente**.

---

## 7. Conclusão

A criação de páginas estáticas no GitHub é uma forma simples e eficiente de publicar sites na internet. Utilizando o **GitHub Pages**, é possível hospedar projetos diretamente a partir de um repositório, mantendo todo o conteúdo versionado e facilmente atualizável.

Esse recurso é amplamente utilizado para portfólios, documentações e páginas de apresentação de projetos.
````
