# Nexus-Leads

Como funciona
    • Salvamento: cada lead, negócio, nota, etapa e dado da empresa é gravado no navegador a cada alteração. Os dados ficam no computador de quem usa, não dentro do arquivo HTML. 
    • Backup: o botão “Baixar backup (.json)” gera um arquivo com data e hora no nome, com todos os leads, negócios e notas. 
    • Restaurar: ao carregar o backup, aparece uma escolha: 
        ◦ Substituir tudo: troca os dados atuais pelos do arquivo. 
        ◦ Somar aos atuais: mantém o que a pessoa já tem e acrescenta só o que falta, sem duplicar. 
O que acrescentei
    • Aviso de falha: se o navegador não conseguir salvar (espaço cheio ou modo anônimo), aparece um aviso pedindo para baixar o backup. Antes ele falhava sem avisar. 
    • Armazenamento mais protegido: o arquivo agora pede ao navegador para não apagar os dados sozinho quando faltar espaço. 
    • Status do backup: na barra lateral aparece a data do último backup e quantas alterações foram feitas desde então. O texto fica amarelo se nunca houve backup ou se passaram de 20 alterações. 
Limites que valem para qualquer versão
    • Os dados ficam no navegador onde foram criados. Se a pessoa limpar os dados do navegador ou trocar de computador, só o arquivo de backup recupera tudo. 
    • Dentro de um mesmo navegador, todos os logins compartilham a mesma base de leads. Se quiser uma base separada por login, dá para fazer, mas é preciso decidir o que acontece com os leads que já existem. 
    • O backup não inclui os logins e senhas dos usuários, só os leads e o que está ligado a eles.
