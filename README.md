# Building my career - Construindo minha carreira

Iniciei este repositório com o intuito de facilitar minha organização de estudos.

Estou no final do meu curso da faculdade onde atualmente vejo que comi muita bola e não aprendi quase nada(obvio que um enorme erro meu, por não estudar com o intuito de adquirir conhecimento).
Mas não chorando pelo leite derramado, decidi estudar de verdade, para não somente ler sobre tal assunto como também exercita-lo e adquirir este conhecimento.

Tudo isso deu inicio após assistir o vídeo do Fabio Akita sobre a Rinha de Backend - [Link do Vídeo](https://www.youtube.com/watch?v=EifK2a_5K_U&t=2230s) "OBRIGADO FABIO AKITA".

Caso isso chegue a alguem que deseja um caminho para estudar e se tornar um programador de excelência, eu pesquisei de forma bruta/total, quais conhecimentos eram necessários e destrinchei para os principais, os quais utilizarei aqui!

Hoje dia 18/10/2024, eu Willian Simas me identifico como um mero escritor de código.
E o por que disso é simples, eu me sinto estagnado em conhecimento ou até desorientado em relação a isso.
Com atuais 27 de idade, iniciei na área de programação tem relativos 1 ano, como mencionado acima, por não estudar de fato o conteúdo da faculdade, me sinto totalmente perdido(juro que tentei desde o início do curso estudar para ADQUIRIR o conhecimento e não fingir isso).

Acredito que iniciar programação com PHP foi um start bom, do meu ponto de vista, pois iniciei desenvolvendo aplicações para sistemas legado e refatorando algumas aplicações.

Como meus primeiros códigos escritos se iniciaram com PHP 5, aprendi sua sintaxe e de forma básica aprendi a lógica de programação para aplicações simples, famosos CRUDS.

Após o desenvolvimento de alguns desses CRUDS, recebi a permissão de migrar algumas das aplicações do PHP 5 para o PHP 7.

Fiquei animado, pois em paralelo aos projetos que eu desenvolvia, eu já andava estudando fundamentos da linguagem e saber que eu poderia utilizar de boas práticas em novas aplicações, como modelos MVC com Model Controler e Views.

Mas enfim, o foco em si do desabafo creio que muitos se veem travados em algo, ou por falta de conhecimento ou direção para onde e o que estudar.

Dito isto, bora começar!

#


# Plano de Estudo de Fundamentos para Desenvolvimento de Software

## Mês 1: Sistemas Operacionais e Processos

### 1. Leitura e Estudo Teórico:
- Ler capítulos sobre processos e threads nos livros *Operating Systems: Design and Implementation* (Tanenbaum) ou *Operating System Concepts* (Silberschatz).
- Assistir a vídeos tutoriais sobre o funcionamento de processos e threads no YouTube ou em plataformas como Udemy ou Coursera.

### 2. Atividades Práticas:
- Criar um programa simples em C ou Python que usa múltiplos processos (ex.: usando `fork()` em C ou `multiprocessing` em Python).
- Criar um programa multithreaded que utiliza threads para executar tarefas em paralelo (ex.: baixar arquivos, processar dados).
- Utilizar comandos no Linux como `ps`, `htop`, e `top` para monitorar processos em tempo real.
- Simular problemas de sincronização, como o problema do Produtor/Consumidor, usando semáforos ou locks em sua linguagem preferida.

### 3. Projetos Sugeridos:
- Desenvolver um mini gerenciador de tarefas que executa vários processos simultâneos (por exemplo, realizar cópias de arquivos em paralelo).
- Criar um simulador de escalonamento de processos que demonstra como diferentes algoritmos (Round-Robin, FCFS) impactam a execução de processos.

---

## Mês 2: Alocação de Memória e Escalonamento

### 1. Leitura e Estudo Teórico:
- Ler capítulos sobre alocação de memória e escalonamento no *Operating Systems: Design and Implementation* ou *Operating System Concepts*.
- Estudar artigos e tutoriais sobre como os algoritmos de gerenciamento de memória (malloc/free, coleta de lixo) funcionam em linguagens como C/C++ ou Java.

### 2. Atividades Práticas:
- Criar programas que alocam e desalocam memória dinamicamente, medindo o uso de memória (usando ferramentas como `valgrind` para detectar vazamentos).
- Simular o funcionamento de algoritmos de escalonamento (Round-Robin, Shortest Job First) em código, escrevendo um programa que simula o comportamento desses algoritmos.
- Utilizar ferramentas como **gdb** para depurar código e investigar como a memória está sendo utilizada.
- Experimentar com ambientes de virtualização (VMware ou VirtualBox) para ver como a alocação de memória é gerenciada em máquinas virtuais.

### 3. Projetos Sugeridos:
- Criar uma mini-simulação de um gerenciador de memória que implemente diferentes algoritmos de alocação (First-Fit, Best-Fit).
- Desenvolver um escalonador simples de processos que implemente o algoritmo Round-Robin e analisar como diferentes prioridades impactam o desempenho.

---

## Mês 3: Estruturas de Dados e Algoritmos

### 1. Leitura e Estudo Teórico:
- Estudar o livro *Introduction to Algorithms* (Cormen) ou *Algoritmos: Teoria e Prática* (Nivio Ziviani).
- Usar sites como *GeeksforGeeks* ou *HackerRank* para rever e testar conhecimentos sobre estruturas de dados e algoritmos.

### 2. Atividades Práticas:
- Implementar estruturas de dados clássicas (listas ligadas, pilhas, filas) manualmente, sem o uso de bibliotecas prontas.
- Implementar algoritmos de ordenação (QuickSort, MergeSort) e medir o desempenho deles para diferentes conjuntos de dados.
- Resolver problemas de algoritmos em plataformas como *LeetCode*, *Codeforces* ou *HackerRank*.
- Implementar um algoritmo de busca em largura (BFS) e profundidade (DFS) para grafos e aplicar em problemas como busca em labirintos.

### 3. Projetos Sugeridos:
- Criar um gerador de labirintos que resolve o caminho mais curto usando algoritmos de grafos (BFS, DFS, A*).
- Desenvolver uma biblioteca de estruturas de dados em PHP, implementando pilhas, filas, árvores e grafos.

---

## Mês 4: Redes de Computadores e Segurança

### 1. Leitura e Estudo Teórico:
- Ler sobre redes no livro *Computer Networks* (Tanenbaum) ou *Redes de Computadores* (Kurose).
- Estudar o modelo OSI e como o TCP/IP funciona, revisando conceitos como HTTP, DNS e DHCP.

### 2. Atividades Práticas:
- Usar ferramentas como **Wireshark** para capturar e analisar pacotes de rede.
- Criar um servidor e cliente TCP simples em PHP ou Python que se comunica por meio de sockets.
- Configurar uma VPN ou firewall para entender como ocorre o controle de acesso à rede.
- Fazer experimentos com certificados SSL/TLS, criando um servidor web seguro usando HTTPS.

### 3. Projetos Sugeridos:
- Criar um mini simulador de rede que implementa camadas do modelo OSI (ex.: uma aplicação que simula a camada de transporte).
- Desenvolver uma aplicação cliente-servidor que troca dados de forma segura usando criptografia (por exemplo, usando SSL).

---

## Mês 5: Banco de Dados e ORMs

### 1. Leitura e Estudo Teórico:
- Estudar o uso de banco de dados relacionais (MySQL, PostgreSQL) e NoSQL (MongoDB) usando livros como *Database System Concepts*.
- Estudar a documentação de ORMs como **Eloquent** (Laravel) ou **Doctrine** (PHP).

### 2. Atividades Práticas:
- Criar um banco de dados simples para um sistema de inventário, praticando consultas SQL (SELECT, JOIN, GROUP BY, etc.).
- Trabalhar com transações e aprender como implementá-las para garantir atomicidade e consistência.
- Usar índices e otimizar consultas complexas.
- Trabalhar com um ORM como **Eloquent** em Laravel, desenvolvendo uma aplicação CRUD simples.

### 3. Projetos Sugeridos:
- Desenvolver um sistema de gerenciamento de tarefas com Laravel, aplicando boas práticas de ORM e SQL.
- Criar um banco de dados relacional que usa transações para gerenciar uma loja online (produtos, pedidos, clientes).

---

## Mês 6: Virtualização, Containers e Paradigmas de Programação

### 1. Leitura e Estudo Teórico:
- Estudar sobre containers e Docker em livros como *Docker Deep Dive* ou por meio da documentação oficial do Docker.
- Revisar conceitos de orientação a objetos e programação funcional (livros como *Design Patterns* e *Functional Programming in JavaScript*).

### 2. Atividades Práticas:
- Criar e gerenciar containers Docker, explorando o uso de volumes, redes e Docker Compose.
- Implementar um pequeno sistema distribuído usando **Docker Swarm** ou **Kubernetes**.
- Criar programas usando o paradigma de orientação a objetos (com herança, polimorfismo) e programação funcional (funções puras, imutabilidade) em linguagens como PHP ou Python.
- Simular o uso de um hipervisor (ex.: VirtualBox ou KVM) para rodar múltiplas máquinas virtuais e entender como recursos são compartilhados.

### 3. Projetos Sugeridos:
- Desenvolver um sistema de microserviços simples usando Docker, com múltiplos containers interagindo entre si.
- Construir uma API que utiliza boas práticas de programação funcional e orientação a objetos.

---

## Dicas para Aplicar o Conhecimento

- **Desafios de Programação**: Resolver problemas diários em plataformas como *HackerRank*, *LeetCode*, ou *Codewars*.
- **Projetos Open Source**: Contribuir para projetos open source no GitHub relacionados aos temas estudados.
- **Documentação e Tutoriais Oficiais**: Consultar a documentação oficial das ferramentas e linguagens utilizadas, como Docker, Laravel, MySQL, etc.
