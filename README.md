<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/leonifrazao/Raxy-Microsoft">
    <h1>Raxy Microsoft</h1>
  </a>

  <h3 align="center">Automação do Microsoft Rewards</h3>

  <p align="center">
    Automatize o processo de ganhar pontos no Microsoft Rewards e converta-os em Robux!
    <br />
    <a href="https://github.com/leonifrazao/Raxy-Microsoft"><strong>Explore a documentação »</strong></a>
    <br />
    <br />
    <a href="https://github.com/leonifrazao/Raxy-Microsoft/issues/new?labels=bug&template=bug-report---.md">Reportar Bug</a>
    ·
    <a href="https://github.com/leonifrazao/Raxy-Microsoft/issues/new?labels=enhancement&template=feature-request---.md">Solicitar Funcionalidade</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Índice</summary>
  <ol>
    <li>
      <a href="#sobre-o-projeto">Sobre o Projeto</a>
      <ul>
        <li><a href="#construído-com">Construído Com</a></li>
      </ul>
    </li>
    <li>
      <a href="#começando">Começando</a>
      <ul>
        <li><a href="#pré-requisitos">Pré-requisitos</a></li>
        <li><a href="#instalação">Instalação</a></li>
      </ul>
    </li>
    <li><a href="#uso">Uso</a></li>
    <li><a href="#principais-funcionalidades">Principais Funcionalidades</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contribuindo">Contribuindo</a></li>
    <li><a href="#licença">Licença</a></li>
    <li><a href="#contato">Contato</a></li>
    <li><a href="#agradecimentos">Agradecimentos</a></li>
    <li><a href="#aviso-legal">Aviso Legal</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## Sobre o Projeto

Este projeto foi desenvolvido para automatizar o processo de ganhar pontos no Microsoft Rewards utilizando vários aplicativos do Windows, como Xbox 🎮, Microsoft Rewards e Microsoft Store. O script realiza milhares de pesquisas por segundo em diferentes países para maximizar o acúmulo de pontos, que são então convertidos em Robux, a moeda virtual usada no Roblox.

### Por que usar Raxy Microsoft?

* **Economize Tempo**: Automatize o processo de ganhar pontos sem esforço manual
* **Maximize Ganhos**: Execute milhares de pesquisas por segundo para acumular pontos rapidamente
* **Multi-Regional**: Aproveite ofertas de recompensas de diferentes países
* **Conversão Automática**: Converta seus pontos em Robux automaticamente

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

### Construído Com

* [![Python][Python.py]][Python-url]
* [![Firebase][Firebase]][Firebase-url]

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- GETTING STARTED -->
## Começando

Para começar a usar o Raxy Microsoft, siga estas etapas simples de instalação.

### Pré-requisitos

Antes de começar, certifique-se de ter os seguintes requisitos:

* **Sistema Operacional**: Windows 10/11
* **Python**: Versão 3.7 ou superior
  ```sh
  python --version
  ```
* **Conta Microsoft**: Com Microsoft Rewards habilitado
* **Conta Roblox**: Para receber os Robux

### Instalação

1. Clone o repositório
   ```sh
   git clone https://github.com/leonifrazao/Raxy-Microsoft.git
   ```

2. Navegue até o diretório do projeto
   ```sh
   cd Raxy-Microsoft
   ```

3. Instale as dependências necessárias
   ```sh
   pip install -r requirements.txt
   ```

4. Configure o banco de dados Firebase no arquivo `configs.json`
   ```json
   {
     "database": "https://contas2-b9481-default-rtdb.firebaseio.com/"
   }
   ```

5. Execute o script de automação
   ```sh
   python Raxy.py
   ```

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- USAGE -->
## Uso

1. **Configuração Inicial**: Certifique-se de que sua conta Microsoft tem acesso ao Microsoft Rewards
2. **Execução**: Execute o script `python Raxy.py` para começar a ganhar pontos automaticamente
3. **Automação**: O script lidará automaticamente com:
   - Alternância entre diferentes países
   - Realização de pesquisas otimizadas
   - Acúmulo de pontos da maneira mais rápida possível
4. **Conversão**: Após acumular pontos suficientes, o script iniciará automaticamente a conversão dos pontos em Robux

_Para mais informações sobre configuração avançada, consulte a [Documentação](https://github.com/leonifrazao/Raxy-Microsoft)_

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- FEATURES -->
## Principais Funcionalidades

- [x] **Pesquisas Automatizadas**: Automação de consultas no sistema Microsoft Rewards
- [x] **Integração Multi-Aplicativo**: Utiliza Xbox, Microsoft Rewards e Microsoft Store
- [x] **Alta Velocidade**: Executa milhares de pesquisas por segundo
- [x] **Alternância de Países**: Otimiza pontos em diferentes regiões
- [x] **Conversão Automática**: Converte pontos em Robux automaticamente
- [x] **Integração Firebase**: Armazenamento seguro de contas
- [ ] Dashboard de Estatísticas
- [ ] Notificações de Pontos
- [ ] Suporte Multi-idioma

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Implementação de pesquisas automatizadas
- [x] Sistema de alternância de países
- [x] Integração com Firebase
- [ ] Adicionar interface gráfica (GUI)
- [ ] Implementar sistema de logs detalhado
- [ ] Adicionar suporte para mais regiões
- [ ] Sistema de alertas e notificações
- [ ] Modo stealth para evitar detecção
- [ ] Dashboard de estatísticas em tempo real

Veja as [issues abertas](https://github.com/leonifrazao/Raxy-Microsoft/issues) para uma lista completa de funcionalidades propostas e problemas conhecidos.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- CONTRIBUTING -->
## Contribuindo

As contribuições são o que tornam a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

Se você tiver uma sugestão para melhorar o projeto, faça um fork do repositório e crie um pull request. Você também pode simplesmente abrir uma issue com a tag "enhancement".
Não se esqueça de dar uma estrela ao projeto! Obrigado novamente!

1. Faça um Fork do Projeto
2. Crie sua Branch de Funcionalidade (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas Mudanças (`git commit -m 'Adiciona NovaFuncionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- LICENSE -->
## Licença

Distribuído sob a Licença CC0-1.0. Veja `LICENSE` para mais informações.

Copyright © 2024 RAXY

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- CONTACT -->
## Contato

Leoni Frazão - [@leonifrazao](https://github.com/leonifrazao)

Link do Projeto: [https://github.com/leonifrazao/Raxy-Microsoft](https://github.com/leonifrazao/Raxy-Microsoft)

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Agradecimentos

Recursos úteis que ajudaram no desenvolvimento deste projeto:

* [Python Documentation](https://docs.python.org/)
* [Firebase Realtime Database](https://firebase.google.com/docs/database)
* [Microsoft Rewards](https://www.microsoft.com/rewards)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- WARNING -->
## ⚠️ Aviso Legal

> **IMPORTANTE**: Este projeto é apenas para fins educacionais. 

Automatizar o Microsoft Rewards pode violar os **termos de serviço da Microsoft**, o que pode resultar em:
- Suspensão da conta
- Banimento permanente
- Perda de pontos acumulados

**Use por sua conta e risco.** Os desenvolvedores não se responsabilizam por quaisquer consequências do uso deste software.

<p align="right">(<a href="#readme-top">voltar ao topo</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/leonifrazao/Raxy-Microsoft.svg?style=for-the-badge
[contributors-url]: https://github.com/leonifrazao/Raxy-Microsoft/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/leonifrazao/Raxy-Microsoft.svg?style=for-the-badge
[forks-url]: https://github.com/leonifrazao/Raxy-Microsoft/network/members
[stars-shield]: https://img.shields.io/github/stars/leonifrazao/Raxy-Microsoft.svg?style=for-the-badge
[stars-url]: https://github.com/leonifrazao/Raxy-Microsoft/stargazers
[issues-shield]: https://img.shields.io/github/issues/leonifrazao/Raxy-Microsoft.svg?style=for-the-badge
[issues-url]: https://github.com/leonifrazao/Raxy-Microsoft/issues
[license-shield]: https://img.shields.io/github/license/leonifrazao/Raxy-Microsoft.svg?style=for-the-badge
[license-url]: https://github.com/leonifrazao/Raxy-Microsoft/blob/main/LICENSE
[Python.py]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Firebase]: https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black
[Firebase-url]: https://firebase.google.com/
