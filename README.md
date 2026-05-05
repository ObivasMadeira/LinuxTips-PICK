
Programa Intensivo em Containers e Kubernetes
Desenvolvimento e Otimização Segura de Aplicações Kubernetes
Objetivo Geral
Objetivo: Criar uma aplicação de gestão de senhas utilizando Docker, Kubernetes, Helm, Kyverno, Cosign, Prometheus, apko e Melange para garantir a segurança, automação, e monitoramento contínuo da aplicação.

Descrição do Projeto: Os alunos devem criar uma aplicação de gestão de senhas baseada no projeto giropops-senhas. O objetivo é implementar e configurar a aplicação com as tecnologias listadas, garantindo altos padrões de segurança, automação, e monitoramento.

Data de entrega do projeto: 07/09/2024
Repo da App para o Fork: https://github.com/badtuxx/giropops-senhas
Repo do Desafio: https://github.com/badtuxx/LINUXtips-PICK-24_01/
Requisitos do Projeto

    Containerização com Docker
        Containerizar a aplicação de gestão de senhas.
        Criar um Dockerfile eficiente e seguro.
        Publicar a imagem Docker em um repositório privado.
    Orquestração com Kubernetes
        Implementar a aplicação no Kubernetes.
        Criar os manifests necessários (Deployment, Service, ConfigMap, Secret, etc.).
        Utilizar Ingress para expor a aplicação externamente.
    Automação de Deploy com Helm
        Criar um Chart Helm para a aplicação.
        Configurar valores dinâmicos para diferentes ambientes (dev, staging, prod).
        Gerar pacotes Helm e armazenar em um repositório Helm privado.
    Políticas de Segurança com Kyverno
        Criar políticas Kyverno para garantir práticas de segurança, como:
            Verificação de imagens assinadas.
            Proibição de execução como root.
            Verificação de variáveis de ambiente sensíveis.
        Implementar políticas de conformidade (compliance).
    Assinatura de Imagens com Cosign
        Assinar as imagens Docker utilizando Cosign.
        Configurar a verificação automática das assinaturas no Kubernetes utilizando as políticas Kyverno.
    Monitoramento com Prometheus
        Implementar métricas customizadas na aplicação.
        Configurar Prometheus para coletar e visualizar essas métricas.
        Criar alertas baseados em métricas específicas da aplicação.
    Distribuição de Pacotes com APKO e Melange

        Utilizar Melange para criar pacotes da aplicação.
        Configurar um pipeline CI/CD para construir e distribuir esses pacotes.
        Garantir que os pacotes estejam disponíveis para diferentes ambientes (dev, staging, prod).
    Otimização de Recursos e teste de capacidade
         Eficiência no Kubernetes: Ajuste a aplicação e a configuração do Kubernetes para maximizar a eficiência no uso dos recursos.
        Escolha da Ferramenta: Escolha entre k6 e Locust para realizar testes de performance.
        Implementação dos Testes: Desenvolva scripts para testar a performance da aplicação, garantindo um mínimo de 1000 requisições por minuto sem erros.
    Documentação Detalhada
        Processo e Decisões: Documente cada passo do processo, explicando as escolhas feitas e as práticas adotadas.
        Guia de Uso e Escalabilidade: Forneça instruções sobre como escalar e gerenciar a aplicação em ambientes Kubernetes.

Entregáveis
Repositório Git

    Código-fonte da aplicação com o Dockerfile.
    Manifests Kubernetes e Chart Helm.
    Políticas Kyverno.
    Scripts de configuração do Prometheus.
    Configuração do pipeline CI/CD com Melange.


Documentação

    Passo a passo para build e deploy da aplicação.
    Descrição das políticas Kyverno implementadas.
    Guia de configuração do Prometheus e alertas criados.
    Instruções para assinatura e verificação de imagens com Cosign.
    Explicação do pipeline CI/CD utilizando Melange.


Demonstração

    Gravação de vídeo ou demonstração ao vivo do deploy da aplicação.
    Apresentação das métricas coletadas e alertas acionados.
    Explicação das políticas de segurança e conformidade implementadas.

Avaliação
Completeness
O projeto atende a todos os requisitos definidos.

Quality
Qualidade do código, eficiência do Dockerfile, e configuração dos manifests Kubernetes.

Security
Implementação e eficácia das políticas de segurança com Kyverno e Cosign.

Documentation
Clareza e detalhamento da documentação fornecida.

Demonstration
Eficácia e clareza na demonstração das funcionalidades e configurações.
Premiação
Os dois melhores projetos serão premiados com:

    Viagem para João Pessoa com tudo pago para participar da festa da Linuxtips (somente para residentes no Brasil).
    Prêmio em dinheiro para residentes no exterior.

Regras para Participação
Post no LinkedIn

    Publique no LinkedIn sobre o desafio e sua experiência no PICK.
    Inclua no post as hashtags: #LINUXtipsChallenge e #PICKExperience.
    Mencione o perfil da Linuxtips (@LINUXtips).

Formulários de Submissão

    Primeiro Formulário: Aqui você realizará a sua inscrição no desafio e adicionará o seu perfil no LinkedIn e a URL do seu post sobre o desafio. Após o preenchimento, você receberá um e-mail com o segundo link.
    Segundo Formulário: No segundo link, você deverá fornecer o link do seu repositório GitHub com o projeto iniciado. O nome do repo deverá ser LINUXtips-PICK.
    Terceiro Formulário: Após receber o terceiro e-mail, preencha o formulário apenas quando finalizar o projeto.
    Quarto Formulário: Use o quarto link para adicionar detalhes finais da sua conclusão, incluindo vídeos, palestras, ou demonstrações.

