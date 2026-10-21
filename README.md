# Entre Nós

Site privado de um cantinho compartilhado, hospedado no GitHub Pages e sincronizado com Firebase Authentication + Cloud Firestore.

## Configurar uma vez

1. Crie um projeto em https://console.firebase.google.com/ (plano Spark).
2. Em **Authentication > Sign-in method**, ative **Email/Password**.
3. Em **Firestore Database**, crie o banco de dados.
4. Em **Project settings > Your apps**, crie um app Web e copie os dados de configuração para `firebase-config.js`.
5. Publique as regras de `firestore.rules` no Firestore Rules.
6. Abra **Authentication > Users** e crie uma conta compartilhada pelo site (ou use o botão “criar a conta compartilhada”). Entre com essa mesma conta nos dois aparelhos.
7. No GitHub, vá em **Settings > Pages** e publique a branch `main`, pasta `/ (root)`.

## Importante sobre acesso

As regras iniciais exigem autenticação, mas permitem que qualquer conta autenticada leia o mural. Para um uso privado, configure regras com os UIDs específicos dos usuários autorizados antes de colocar informações pessoais. Não coloque senhas no repositório.

O mural sincroniza texto e links. Fotos devem ser adicionadas por link nesta primeira versão; upload de arquivos precisa de armazenamento adicional.
