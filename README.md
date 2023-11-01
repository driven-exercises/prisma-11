# prisma-11: Migração Problemática

- Nem sempre é possível prever todas as situações que podem acontecer ao tentarmos aplicar uma migração em um banco de dados.
- Neste exercício, simularemos um cenário onde forçaremos um erro e então o corrigiremos manualmente para simular um deploy com Prisma bem sucedido.
- ➡️ O que fazer?
    - Crie um banco de dados e aplique o SQL presente em `sql/script.sql`.
    - Configure `.env` para apontar para este banco e tente aplicar o `prisma migrate deploy`.
    - O erro P3005 acontecerá. Resolva-o aplicando a migração como resolvida.