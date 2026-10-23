# Entre Nós

Site estático publicado pelo GitHub Pages, com autenticação e sincronização pelo Firebase Authentication + Cloud Firestore.

## Publicação

No GitHub, abra **Settings → Pages** e configure **Deploy from a branch**, branch `main`, pasta `/(root)`. Os arquivos publicados ficam na raiz do repositório; alterações enviadas à branch `main` são publicadas automaticamente.

## Firebase

- Authentication: provedor **Email/Password** habilitado.
- Firestore: publique as regras de `firestore.rules`.
- A configuração Web em `firebase-config.js` é usada pelo cliente e não é uma senha nem uma chave de administrador.
- As regras atuais do Firestore permitem acesso somente à conta com o UID definido em `firestore.rules`. Como a conta é compartilhada, proteja suas credenciais e não publique senhas no repositório.

O mural sincroniza texto e links. Fotos são adicionadas por link nesta versão; upload de arquivos exigiria configurar armazenamento adicional.
