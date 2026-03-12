# TreinoPOO

# 🎯 Desafio POO — Java | Iniciante

---

## 📚 Biblioteca de Livros

Crie um sistema simples para gerenciar uma biblioteca pessoal.

---

## 📋 O que você deve implementar

### Classes obrigatórias:

**`Livro`**
- Atributos: `titulo`, `autor`, `anoPublicacao`, `disponivel`
- Métodos: `emprestar()`, `devolver()`, `exibirInfo()`

**`Biblioteca`**
- Atributo: lista de livros (`ArrayList<Livro>`)
- Métodos:
  - `adicionarLivro(Livro livro)`
  - `listarLivros()` — exibe todos os livros
  - `buscarPorAutor(String autor)` — retorna livros do autor
  - `emprestarLivro(String titulo)` — marca como indisponível
  - `devolverLivro(String titulo)` — marca como disponível

---

## ✅ Requisitos

- Use **encapsulamento** (atributos `private` + getters/setters)
- Use **construtor** na classe `Livro`
- O método `emprestar()` deve **verificar** se o livro já está emprestado e exibir uma mensagem adequada
- Crie uma classe `Main` para testar tudo

---

## 🧪 Exemplo de uso esperado no Main

```java
Biblioteca biblioteca = new Biblioteca();

biblioteca.adicionarLivro(new Livro("Dom Casmurro", "Machado de Assis", 1899));
biblioteca.adicionarLivro(new Livro("O Cortiço", "Aluísio Azevedo", 1890));
biblioteca.adicionarLivro(new Livro("Memórias Póstumas", "Machado de Assis", 1881));

biblioteca.listarLivros();
biblioteca.emprestarLivro("Dom Casmurro");
biblioteca.emprestarLivro("Dom Casmurro"); // deve avisar que já está emprestado
biblioteca.buscarPorAutor("Machado de Assis");
```

---

## 💡 Conceitos praticados

- Classes e objetos
- Encapsulamento
- Construtores
- ArrayList
- Métodos com lógica condicional

---

Quando terminar, me manda o código para eu revisar! 🚀
