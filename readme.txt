=== Comentario Via E-mail ===
Tags: comments, subscription, email, cometários, assiatura, assinar comentários
Contributors: Gerlis Rocha
Requires at least: 3.0
Tested up to: 3.3.1
Stable tag: trunk

Permite que o usuário inscreva-se e um comentário e recebe atualizações via e-mail.

== Description ==

SComentario Via E-mail é um plugin que permite robusto comentadores para se inscrever no e-mail de notificação de comntários. O plugin inclui um gerenciador de Assinatura que seus comentaristas podem ser usados ​​para cancelar a determinados cargos, bloquear todas as notificações, ou até mesmo mudar a sua notificação endereço de e-mail!

== Installation ==

1. Coloque comentario-via-e-mail.php dentro do diretório [wordpress_dir]/wp-content/plugins/
2. Vá para a interface de administração do WordPress e ative o plugin
3. Opcional: se o seu tema WordPress não tem o suporte comment_form, ou se você gostaria de determinar manualmente onde em formar os seus comentários na caixa de Assiantura aparece, digite o que você gostaria que ele: `<?php show_subscription_checkbox(); ?>`
4. Opcional: Se você gostaria de permitir que os usuários assinem os comentários, sem ter que primeiro deixar um comentário, coloque isso em algum lugar no seu modelo, mas verifique se ele está fora dos ** ** comentários formulário. Um bom lugar seria logo após o término `</form>` tag para formar os comentários: `<?php show_manual_subscription_form(); ?>`

== Frequently Asked Questions ==

= Como posso saber se ele está funcionando? =

1. Saia do WordPress
2. Deixe um comentário em uma entrada e marque a caixa de subscrição comentário, usando um e-mail que não é o WP e-mail-admin ou o endereço de e-mail do autor do post.
3. Deixe um comentário segundo usando um endereço de e-mail diferente daquele que você usou na etapa 2 (pode ser um endereço falso).
4. Isso deve provocar uma notificação para o primeiro endereço que você usou.

= Eu gostaria que o checkbox inscrição a ser marcada por padrão. Posso fazer isso? =

Não mais. Mas o status de seleção será lembrado em uma base por usuário.

= Minha caixa de verificação de assinatura aparece em um lugar estranho. Como faço para corrigir isso? =

Tente desmarcar a opção CSS "clear". Além disso, você está no seu próprio posicionamento com CSS.