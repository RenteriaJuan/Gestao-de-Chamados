## 🏗️ Arquitetura

O sistema segue o padrão **MVC (Model-View-Controller)** com as seguintes camadas:

```
├── Models/          # Modelos de dados (Funcionários, Chamados)
├── Controllers/     # Lógica de negócio
├── Forms/          # Interface do usuário (Windows Forms)
├── Data/           # Acesso a dados (SQL Server)
├── Interfaces/     # Contratos e interfaces
├── Config/         # Configurações do sistema
└── Database/       # Scripts SQL
```

## 📁 Estrutura do Projeto

```
SistemaChamados/
│
├── Properties/
│   ├── AssemblyInfo.cs
│   └── Resources.resx
│   └── Settings.settings
|
|
├── src/
│   ├── Models/
│   │   ├── Funcionarios.cs      # Classe base
|   |   |   Funcionario.cs       # Herda de Funcionarios
│   │   ├── Tecnico.cs           # Herda de Funcionarios
│   │   ├── ADM.cs               # Herda de Funcionarios
│   │   └── Chamados.cs          # Modelo de chamados
│   │
│   ├── Controllers/
│   │   ├── FuncionariosController.cs
│   │   └── ChamadosController.cs
│   │
│   ├── Forms/
│   │   └── LoginForm.cs             # Interface de login
│   │   └── AlterarPrioridadeForm.cs # Interface para alterar prioridade
│   │   └── AlterarStatusForm.cs     # Interface para alterar status
│   │   └── ContestacaoForm.cs       # Interface para contestações
│   │   └── CriarChamadoForm.cs      # Interface para criar chamados
│   │   └── DetalhesChamadoForm.cs   # Interface para detalhes do chamado
│   │   └── EditarUsuarioForm.cs     # Interface para editar usuário
│   │   └── GerenciarChamadosForm.cs # Interface para gerenciar chamados
│   │   └── GerenciarUsuariosForm.cs # Interface para gerenciar usuarios
│   │   └── NovoUsuarioForm.cs       # Interface para gerenciar chamados
│   │   └── VisualizarChamadosForm.cs# Interface para gerenciar chamados
│   │
│   ├── Data/
│   │   └── SqlServerConnection.cs
│   │
│   ├── Interfaces/
│   │   └── IDatabaseConnection.cs
│   │
│   ├── Config/
│   │   └── DatabaseConfig.cs
│   │
│   ├── Database/
│   │   └── SistemaChamados.sql
│   │
│   └── Program.cs               # Ponto de entrada
│
├── App.config                   # Configurações
└── README.md                    # Este arquivo
```