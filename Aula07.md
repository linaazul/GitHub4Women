## Actions

### ✅ Eventos
São gatilhos (triggers) que disparam ações automatizadas.

Exemplo (GitHub):

- Criar um Pull Request.

- Fazer push de código.

- Criar uma nova issue.

Essas ações são eventos que podem iniciar um workflow no GitHub Actions, por exemplo.

### 📋 Logs
São os registros de tudo que acontece em um sistema, aplicação ou processo automatizado.

Exemplo:

- Quando você executa um script no GitHub Actions, ele gera logs mostrando cada passo: instalar dependência, rodar testes, etc.

- Se deu erro, o log mostra o motivo.

### 🔐 Cofres de segredo (Secrets Vault)
São lugares seguros para guardar informações sensíveis, como:

- Senhas

- Tokens de acesso

- Chaves de API

GitHub Secrets é um exemplo: você pode armazenar tokens e usá-los em workflows sem que fiquem visíveis no código.

### 🤖 Runners
São os servidores (máquinas) responsáveis por executar os workflows.

Tipos:

- **GitHub-hosted runner:** já vem pronto, fornecido pelo GitHub.

- **Self-hosted runner:** você configura a máquina onde os workflows vão rodar.

Exemplo: quando você faz push no GitHub e ele roda testes automáticos, é o runner que está executando esse trabalho por trás.
