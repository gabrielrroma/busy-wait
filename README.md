# 🖥️ Exclusão Mútua com Espera Ocupada (Busy-Wait)

Projeto acadêmico da disciplina **Infraestrutura de Software**.  
Demonstração prática de **exclusão mútua com espera ocupada**, utilizando o **Algoritmo de Peterson** em C.

---

## 📂 Conteúdo do Repositório

- ⚠️ **Sem exclusão mútua**  
  Exemplo em C onde duas threads acessam a mesma variável compartilhada sem proteção, resultando em *race condition*.

- ✅ **Com Peterson**  
  Implementação do **Algoritmo de Peterson**, garantindo exclusão mútua entre duas threads por meio de espera ocupada.

- 🌐 **Site (HTML/CSS + Bootstrap)**  
  Página explicativa com:
  - Introdução teórica  
  - Explicação sobre exclusão mútua e busy-wait  
  - Exemplos dos algoritmos  
  - Prints das execuções  

---

## 🚀 Como Executar os Exemplos em C

### Pré-requisitos
- Compilador C (Clang ou GCC) com suporte a **C11**
- `pthread` (já incluso no Linux/macOS)
- [CLion](https://www.jetbrains.com/clion/) ou [VS Code](https://code.visualstudio.com/) com extensão C/C++

### Compilando via Terminal
```bash
# Criar pasta de build
cmake -S . -B build

# Compilar
cmake --build build

# Executar (exemplos)
./build/sem_lock
./build/peterson
