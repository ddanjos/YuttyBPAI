<h1><strong>Yutty BPAI</strong></h1>

<p>Utilitário para organizar arquivos de produção ambulatorial conforme o padrão do <strong>BPA Individualizado (BPA-I)</strong>.</p>

<hr>

<h2>Visão Geral do Sistema</h2>

<h3>1. Agrupamento por CNS / Reorganização de Folhas e Linhas</h3>

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Agrupamento por CNS</strong>
      <ul>
        <li>Identifica e separa registros por CNS.</li>
        <li>Cada profissional é tratado de forma independente.</li>
        <li>Mantém consistência estrutural.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <strong>Reorganização de Folhas e Linhas</strong>
      <ul>
        <li>Folhas numeradas de 1 a 999 por CNS.</li>
        <li>Até 99 linhas por folha.</li>
        <li>Criação automática de novas folhas quando necessário.</li>
        <li>Processamento aplicado a todos os profissionais.</li>
      </ul>
    </td>
  </tr>
</table>

<hr>

<h3>2. Reenumeração Estruturada / Normalização de Caracteres</h3>

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Reenumeração Estruturada</strong>
      <ul>
        <li>Folhas e linhas renumeradas a partir de 1 para cada CNS.</li>
        <li>Layout final conforme o padrão oficial do BPAI.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <strong>Normalização de Caracteres</strong>
      <ul>
        <li>Remoção completa de acentos (“ação” → “acao”).</li>
        <li>Remoção de símbolos e caracteres especiais.</li>
        <li>Mantém apenas caracteres válidos segundo o BPAI.</li>
      </ul>
    </td>
  </tr>
</table>

<hr>

<h3>3. Arquivo Final Padronizado</h3>

<ul>
  <li>Arquivo reorganizado, limpo e pronto para envio.</li>
  <li>Corrige erros de paginação e estrutura.</li>
  <li>Evita inconsistências técnicas e reduz retrabalho.</li>
</ul>

<hr>

<h2>Requisitos do Sistema</h2>

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Requisitos Mínimos</strong>
      <ul>
        <li>Windows 10 ou 11 (64 bits)</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <strong>Conectividade (Firewall)</strong>
      <p>O sistema precisa acessar:</p>
      <ul>
        <li>https://github.com/ddanjos/YuttyBPAI</li>
        <li>https://raw.githubusercontent.com/ddanjos/YuttyBPAI/refs/heads/main/appcast.json</li>
      </ul>
    </td>
  </tr>
</table>

<hr>

<h2>Status do Projeto</h2>
<p>Em desenvolvimento ativo, com atualizações contínuas.</p>

<hr>

<h2>Contato</h2>
<p>Para dúvidas, sugestões ou relatos de problemas, abra uma <strong>issue</strong> no repositório.</p>
