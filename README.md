<h1>🚀 Guia Completo de Comandos Git e GitHub</h1>

<p>Este projeto contém uma documentação detalhada de todos os comandos Git e GitHub, explicando suas funcionalidades com exemplos práticos para facilitar o uso de controle de versão.</p>

<h2>📋 Comandos Principais</h2>

<p>Lista dos principais comandos do Git, explicando sua funcionalidade e aplicação.</p>

<h3><code>git config</code></h3>
<p>Configura preferências globais como nome de usuário e e-mail, que são usados nos commits.</p>

<pre><code>git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
</code></pre>

<h3><code>git init</code></h3>
<p>Inicializa um novo repositório Git no diretório atual.</p>

<pre><code>git init</code></pre>

<h3><code>git clone</code></h3>
<p>Clona um repositório existente do GitHub para o seu computador.</p>

<pre><code>git clone https://github.com/seu-usuario/seu-repositorio.git</code></pre>

<h3><code>git status</code></h3>
<p>Verifica o status atual dos arquivos no repositório, mostrando quais foram modificados, adicionados ou preparados para commit.</p>

<pre><code>git status</code></pre>

<h3><code>git add</code></h3>
<p>Adiciona arquivos ou mudanças ao stage para o próximo commit.</p>

<pre><code>git add nome_do_arquivo.txt
git add .
</code></pre>

<h3><code>git commit</code></h3>
<p>Salva as mudanças feitas nos arquivos adicionados ao stage em um novo commit.</p>

<pre><code>git commit -m "Descrição do que foi alterado"</code></pre>

<h3><code>git push</code></h3>
<p>Envia os commits do repositório local para o repositório remoto no GitHub.</p>

<pre><code>git push origin main</code></pre>

<h3><code>git pull</code></h3>
<p>Baixa as alterações do repositório remoto e as mescla com o branch local.</p>

<pre><code>git pull origin main</code></pre>

<h2>🎯 Pré-requisitos</h2>

<p>Você precisará ter o Git instalado no seu sistema. Aqui estão as instruções para instalar:</p>

<ul>
  <li><strong>Windows</strong>: Baixe e instale o Git do <a href="https://git-scm.com/download/win">site oficial</a>.</li>
  <li><strong>MacOS</strong>: Instale com Homebrew:
    <pre><code>brew install git</code></pre>
  </li>
  <li><strong>Linux</strong>: Instale com APT:
    <pre><code>sudo apt install git</code></pre>
  </li>
</ul>

<p>Além disso, você precisará criar uma conta no <a href="https://github.com/">GitHub</a> para poder gerenciar repositórios remotos.</p>

<h2>🛠️ Instalação</h2>

<p>Após instalar o Git, configure seu nome e e-mail:</p>

<pre><code>git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
</code></pre>

<h2>⚙️ Executando os Comandos</h2>

<p>Depois de instalar e configurar o Git, você pode começar a executar comandos para gerenciar seu repositório.</p>

<h3>Clonar um repositório</h3>

<pre><code>git clone https://github.com/seu-usuario/seu-repositorio.git</code></pre>

<h3>Adicionar mudanças e fazer commit</h3>

<pre><code>git add .
git commit -m "Mensagem do commit"
</code></pre>

<h3>Enviar alterações para o repositório remoto</h3>

<pre><code>git push origin main</code></pre>

<h2>✅ Gerenciamento de Branches</h2>

<p>Branches permitem que você trabalhe em diferentes funcionalidades ou correções sem afetar o código principal.</p>

<h3><code>git branch</code></h3>
<p>Listar branches existentes ou criar um novo.</p>

<pre><code>git branch
git branch nome_do_branch
</code></pre>

<h3><code>git checkout</code></h3>
<p>Trocar de branch.</p>

<pre><code>git checkout nome_do_branch</code></pre>

<h3><code>git merge</code></h3>
<p>Mesclar as mudanças de um branch para outro.</p>

<pre><code>git merge nome_do_branch</code></pre>

<h2>🚀 Histórico de Commits</h2>

<p>Comandos para visualizar o histórico de commits e informações detalhadas.</p>

<h3><code>git log</code></h3>
<p>Exibe o histórico completo de commits do repositório.</p>

<pre><code>git log</code></pre>

<h3><code>git show</code></h3>
<p>Exibe detalhes sobre um commit específico.</p>

<pre><code>git show commit_id</code></pre>

<h2>📦 Implementação com Repositórios Remotos</h2>

<p>Comandos que interagem com repositórios remotos no GitHub.</p>

<h3><code>git remote</code></h3>
<p>Adicionar um repositório remoto ou listar os remotos disponíveis.</p>

<pre><code>git remote add origin https://github.com/seu-usuario/seu-repositorio.git
git remote -v
</code></pre>

<h3><code>git fetch</code></h3>
<p>Baixa atualizações do repositório remoto sem fazer merge.</p>

<pre><code>git fetch origin</code></pre>

<h3><code>git pull</code></h3>
<p>Baixa atualizações e as mescla diretamente com o branch local.</p>

<pre><code>git pull origin main</code></pre>

<h2>🛠️ Ferramentas Utilizadas</h2>

<p>Este guia foi construído usando as seguintes tecnologias:</p>

<ul>
  <li><strong>Git</strong> - Sistema de controle de versão distribuído.</li>
  <li><strong>GitHub</strong> - Plataforma para hospedagem de repositórios Git.</li>
</ul>

<h2>✒️ Contribuidores</h2>

<p>Este guia foi criado por:</p>

<ul>
  <li><strong>Seu Nome</strong> - Desenvolvedor - <a href="https://github.com/seu-usuario">GitHub</a></li>
</ul>

<h2>📌 Versão</h2>

<p>Este é o guia versão 1.0.0.</p>

<h2>📄 Licença</h2>

<p>Este projeto está licenciado sob a licença MIT - veja o arquivo <a href="LICENSE.md">LICENSE.md</a> para mais detalhes.</p>

<h2>🎉 Agradecimentos</h2>

<p>Agradecimentos a todos que contribuíram para o desenvolvimento deste guia e à comunidade GitHub por fornecer suporte contínuo.</p>
