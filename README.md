# Nano Editor - Guia de Comandos e Utilização

## 📋 Sobre
Este documento contém anotações pessoais sobre o uso do editor de texto **Nano** no terminal Linux.
Estas informações podem ser úteis para consulta rápida durante o desenvolvimento.

---

## ⌨️ Comandos Básicos

### Comandos de Controle Principal
| Comando      | Ação                                                   |
|--------------|--------------------------------------------------------|
| `CTRL + o`   | Salvar como — use quando o arquivo nunca foi salvo     |
| `CTRL + x`   | Fechar o editor Nano                                   |
| `CTRL + c`   | Cancelar ação atual                                    |
| `CTRL + s`   | Salvar arquivo — use em arquivos já existentes         |
| `CTRL + g`   | Abrir menu de ajuda                                    |

### Convenção de Teclas
- `^` = Tecla **CTRL**  
- `M` = Tecla **ALT (Meta)**

---

## 📂 Trabalhando com Múltiplos Arquivos

### Abrindo vários arquivos
```bash
nano arquivo1.txt arquivo2.txt arquivo3.txt
```

### Navegação entre arquivos abertos
| Comando     | Ação                             |
|-------------|----------------------------------|
| `ALT + >`   | Avançar para o próximo arquivo   |
| `ALT + <`   | Voltar para o arquivo anterior   |

### Inserir conteúdo de outros arquivos
| Comando              | Ação                                                           |
|----------------------|----------------------------------------------------------------|
| `CTRL + SHIFT + r`   | Inserir conteúdo de outro arquivo no cursor atual              |
| `ALT + f`            | Abrir arquivo em nova instância (após `CTRL + SHIFT + r`)      |

---

## ✂️ Manipulação de Texto

### Seleção e Manipulação
| Comando     | Ação                                              |
|-------------|---------------------------------------------------|
| `ALT + a`   | Marcar início da seleção (**Mark set**)           |
| `ALT + 6`   | Copiar texto selecionado                          |
| `CTRL + k`  | Recortar texto selecionado ou apagar linha        |
| `CTRL + u`  | Colar texto copiado/recortado                     |

#### Dica de Uso
- Use `ALT + a` para iniciar a seleção.  
- Use as setas do teclado para expandir a seleção.  
- Use `ALT + 6` para copiar ou `CTRL + k` para recortar.  
- Use `CTRL + u` para colar o conteúdo.  

---

## 🔍 Busca no Texto
| Comando      | Ação                            |
|--------------|---------------------------------|
| `CTRL + w`   | Localizar texto no documento    |
| `ALT + w`    | Ir para a próxima ocorrência    |

---

## 💡 Dicas Importantes

### Salvamento em Outros Diretórios
- É possível salvar arquivos em outros diretórios especificando o **path** completo.  
- Use `CTRL + o` (**Salvar como**) para navegar entre diretórios.

### Boas Práticas
- Salve o trabalho frequentemente com `CTRL + s`.  
- Use `CTRL + x` para fechar o editor corretamente.  
- Consulte a ajuda (`CTRL + g`) quando necessário.  

---

## 📚 Recursos Adicionais
- Documentação oficial: `man nano`  
- Ajuda interna: `CTRL + g` dentro do Nano  
- Para sair **sem salvar**: `CTRL + x` e depois `N`
