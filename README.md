# Configurar VPS SSH/SQUID3 & MANAGER

<body>
  <table>
    <tr>
      <td width="100px" class="main2"><b>Ferramenta:</b></td>
      <td width="780px" class="main2"><b>ZWDConfig 0.1</b></td>
    </tr>
    <tr>
      <td width="100px" class="main2"><b>Autor:</b></td>
      <td width="780px">AltoArthur</td>
    </tr>
    <tr>
      <td width="100px" class="main2"><b>Versão:</b></td>
      <td width="780px">1.5</td>
    </tr>
    <tr>
      <td width="100px" class="main2"><b>Termos:</b></td>
      <td width="780px">Em caso de dúvidas, erros ou sugestões de melhorias, entre em contato pelo Telegram.</td>
    </tr>
    <tr>
      <td width="100px" class="main2"><b>Novidades v1.5:</b></td>
      <td width="780px">Melhorias no código</td>
    </tr>
    <tr>
      <td width="100px" class="main2"><b>Contato Privado:</b></td>
      <td width="780px">@SeichMachine740</td>
    </tr>
    <tr>
      <td width="100px" class="main2">&#9733; <b>Descrição:</b></td>
      <td width="780px">
        O ZWDConfig é um script em Python 3 que, ao configurar uma VPS, detecta se a pasta do Squid é "squid" ou "squid3", permitindo a configuração em qualquer servidor. 
        Para editar o arquivo <code>/etc/ssh/sshd_config</code>, ele substitui a linha <code>Port 22</code> por <code>Port 22,443</code> no meio do código, mantendo o arquivo intacto. 
        Isso evita o comportamento de outros scripts em Shell, que reescrevem o arquivo inteiro ou adicionam <code>Port 443</code> ao final, o que pode causar erros na sua VPS.
      </td>
    </tr>
    <tr>
      <td colspan="2" class="main3" width="890px">&#9733; <b>Modo de usar:</b></td>
    </tr>
    <tr>
      <td colspan="2" class="main">
        <br>wget https://raw.githubusercontent.com/GMagNLL/ZWD-Config/master/.config.py<br/>
        <br>chmod +x .config.py<br/>
        <br>python3 .config.py<br/>
        <br><b>Caso o Python 3 não esteja instalado:</b><br/>
        apt-get install python3<br/>
      </td>
    </tr>
  </table>
</body>
</html>
