bot.command({
  name: "say", //Nome do comando
  aliases: [""], //Sinônimos aqui
  code: `
$message
$argsCheck[>1;**❌ Está faltando 1 argumento! \`{prefixo}say [mensagem]\`**]
$onlyPerms[managemessages;**❌ Você precisa da permissão \`Gerenciar_mensagens\` para isso.**]
`
}) //Um simples comando de say! Em breve trago mais
