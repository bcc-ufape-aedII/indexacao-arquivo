# Atividade sobre Indexação

Esse repositório tem a finalidade de implementar em uma árvore o uso de índice para orientar a busca, para a redução do tempo de acesso a um registro. 
Um índice é um mapeamento que associa a cada chave, uma referência ao registro que a contém. Assim, dada uma chave de pesquisa, o índice fornece imediatamente a localização do registro correspondente.

### Compilação do executável:
#### Versão normal (txt):
```gcc -o indexacao arquivo/arquivo.c arvore_avl/avl.c main.c -g```
#### Versão JSON:
```gcc -o indexacao cJSON/cJSON.c arquivo/arquivo-json.c arvore_avl/avl.c main-json.c -g```

### Rodar Programa Após Compilação:
```./indexacao```
