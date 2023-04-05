#### Qual a proposta?

Minha equipe foi selecionada para resolver o principal problema da empresa Wtec Suprimentos, uma importadora de diversos suprimentos de informática, como cabos, cartuchos de impressoras, mouses, teclados, câmeras e outros produtos relacionados. O negócio da Wtec Suprimentos é importar esses produtos e revendê-los para pequenas lojas, redes de armarinhos e grandes redes de supermercado.

## Os problemas a serem resolvidos são:

1 - Traçar uma estratégia comum para cada grupo de cliente, mesmo que atualmente não existam informações claras sobre o segmento do cliente ou tamanho. Isso ajudaria o time de marketing e análise de crédito a tomar decisões mais eficientes com base em informações precisas.

2 - Encontrar uma solução para lidar com a geração de novos grupos de clientes e o que fazer quando chegar um novo cliente solicitando um novo crédito. A empresa precisa ter uma estratégia clara para gerenciar essa situação de forma eficiente e tomar decisões informadas com base nas informações disponíveis.

3 - Desenvolver um "robô automatizado" capaz de realizar recomendações de crédito para que os analistas possam se basear nessas recomendações para conceder o limite máximo de crédito. Isso ajudará a empresa a tomar decisões mais rápidas e precisas em relação à concessão de crédito.

4 - Para alcançar esses objetivos, a empresa precisará realizar uma análise aprofundada de seus dados e desenvolver soluções personalizadas para cada um dos problemas identificados. Será necessário trabalhar em estreita colaboração com a equipe da empresa e entender suas necessidades e processos para desenvolver soluções que atendam às suas expectativas e objetivos de negócios.

#### Soluções 

Criamos um pitch de 3 minutos apresentado, que resolve o problema: [Pitch](https://github.com/xxbielxd/bootcamp_ia/blob/main/apresenta%C3%A7%C3%A3o/Pitch_Bootcamp.pptx)

Criamos um Jupyter Notebook para gerar os modelos : [Jupyter Notebook](https://github.com/xxbielxd/bootcamp_ia/blob/main/Trabalho_Final_MBA_Intelige%CC%82ncia_Artificial_e_Machine_Learning.ipynb) 

Além disso criamos um website e um painel dos clientes, segue as imagens:

- [Web Site](https://github.com/xxbielxd/bootcamp_ia/blob/main/img/website.png?raw=true)
- [Tela de Login](https://github.com/xxbielxd/bootcamp_ia/blob/main/img/login.png?raw=true)
- [Cadastro de novos clientes](https://github.com/xxbielxd/bootcamp_ia/blob/main/img/novos_clientes.png?raw=true)
- [Dashboard do cliente](https://github.com/xxbielxd/bootcamp_ia/blob/main/img/dashboard.png?raw=true)
- [Resumo de crédito](https://github.com/xxbielxd/bootcamp_ia/blob/main/img/credito.png?raw=true)
- [Solicitar crédito](https://github.com/xxbielxd/bootcamp_ia/blob/main/img/solicitar_credito.png?raw=true)
- [Lojinha online](https://github.com/xxbielxd/bootcamp_ia/blob/main/img/loja.png?raw=true)

Todas as tela estão funcionando em nossa infra, usando docker.

#### Como executar a infra do projeto?

- Primeiramente instale o Docker https://www.docker.com/products/docker-desktop/
- Acesse a pasta infra
- Execute o código ```docker-compose up -d ```
- Para acompanhar o passo-a-passo da maquina subindo rode ```docker logs -t -f api```

### Plataforma Web - Como utilizar

- Rodar o site em: http://127.0.0.1:8081
- Acessar a página de login em http://127.0.0.1:8081/login.html
- Logar com os dados:
    - CNPJ: ***KEBE17609492220843***
    - Senha: ***123***
    - OBS: Qualquer cliente na base pode ser acessado com a senha "123".
- Após logado, abrir o menu lateral e clicar em "financeiro".
- Na tela das últimas solicitações, clicar em "Solicitar".
- Preencher o valor desejado, adicionar uma mensagem (opicional) e finalmente clicar em "Enviar Solicitação" para enviar a solicitação e obter o retorno da API.
