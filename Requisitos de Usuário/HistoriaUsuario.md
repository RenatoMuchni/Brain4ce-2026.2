# Histórias de Usuário

## US01

**História:** Como visitante, eu quero visualizar a lista de veículos disponíveis no estoque, para conhecer as opções da loja.

**Critérios de aceitação:**
- Dado que há veículos disponíveis, quando o visitante acessar a lista, então o sistema deve exibir esses veículos com foto, nome/modelo e preço.
- Dado que um veículo está indisponível, quando o visitante acessar a lista, então esse veículo não deve aparecer.
- Dado que o visitante acessou a lista, quando a página carregar, então o carregamento deve levar até 3 segundos.
- Dado que o visitante usa celular ou computador, quando acessar a lista, então não deve haver rolagem horizontal.

**Prioridade:** Alta  
**RF relacionados:** RF01  
**RNF relacionados:** RNF01, RNF03

---

## US02

**História:** Como visitante, eu quero ver os detalhes de um veículo, para decidir se ele atende ao que procuro.

**Critérios de aceitação:**
- Dado que o visitante está na lista, quando selecionar um veículo, então o sistema deve exibir fotos, nome/modelo, ano, preço e descrição.
- Dado que o visitante está nos detalhes, quando quiser voltar, então deve haver uma forma de retornar à lista.
- Dado que o visitante usa celular ou computador, quando abrir os detalhes, então não deve haver rolagem horizontal.

**Prioridade:** Alta  
**RF relacionados:** RF02  
**RNF relacionados:** RNF03

---

## US03

**História:** Como visitante, eu quero pesquisar veículos por nome ou modelo, para encontrar rapidamente o carro que procuro.

**Critérios de aceitação:**
- Dado que o visitante está na lista, quando informar um nome ou modelo no campo de busca, então o sistema deve exibir apenas os veículos que contenham o termo, sem diferenciar maiúsculas e minúsculas.
- Dado que o visitante enviou um termo, quando a pesquisa for feita, então o resultado deve aparecer em até 2 segundos.
- Dado que há uma pesquisa ativa, quando o visitante limpar o campo, então a lista completa deve voltar a ser exibida.

**Prioridade:** Alta  
**RF relacionados:** RF03  
**RNF relacionados:** RNF02

---

## US04

**História:** Como visitante, eu quero ser informado quando a pesquisa não encontrar veículos, para saber que devo tentar outro termo.

**Critérios de aceitação:**
- Dado que nenhum veículo corresponde ao termo, quando o visitante pesquisar, então o sistema deve exibir a mensagem "Nenhum veículo encontrado".
- Dado que a mensagem foi exibida, quando o visitante quiser pesquisar de novo, então o campo de busca deve continuar disponível.

**Prioridade:** Média  
**RF relacionados:** RF04  
**RNF relacionados:** RNF02

---

## US05

**História:** Como visitante, eu quero consultar as informações de contato da loja, para falar com a equipe sobre um veículo.

**Critérios de aceitação:**
- Dado que o visitante abriu o contato, quando a página for exibida, então devem aparecer telefone, endereço, e-mail e horário de atendimento.
- Dado que o visitante está em qualquer página, quando procurar o contato, então deve chegar a ele em até 2 cliques.
- Dado que o visitante usa celular ou computador, quando abrir o contato, então não deve haver rolagem horizontal.

**Prioridade:** Alta  
**RF relacionados:** RF05  
**RNF relacionados:** RNF03, RNF04

---

## US06

**História:** Como visitante, eu quero conhecer a apresentação da loja na página inicial, para entender quem é a Auto Elite e o que ela oferece.

**Critérios de aceitação:**
- Dado que o visitante acessou o site, quando a página inicial for exibida, então devem aparecer o nome da loja e um texto de apresentação.
- Dado que o visitante está na página inicial, quando quiser ver os veículos ou o contato, então deve haver acesso direto a ambos.

**Prioridade:** Média  
**RF relacionados:** RF06  
**RNF relacionados:** RNF05

---