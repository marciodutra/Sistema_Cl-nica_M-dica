
# Sistema de agendamento de consultas médicas de código aberto usando PHP
![](https://github.com/hshnudr/edoc-echanneling/blob/main/Screenshots/Screenshot%20(1).png)

[Edoc](https://github.com/HashenUdara/edoc-doctor-appointment-system/) é um projeto web simples feito para canalização eletrônica usando PHP, HTML e CSS.
Esta iniciativa facilita a solicitação de consultas online para clientes ou pacientes de estabelecimentos médicos, incluindo clínicas e hospitais. Este projeto também pode ajudar os médicos a administrar as consultas com seus pacientes. Este sistema de consultas médicas organizará os horários das consultas de cada paciente, que serão submetidas como solicitação ao médico por ele selecionado. O sistema compreende três funções principais: administrador, médico e paciente. O administrador do sistema preencherá a lista de médicos com suas especialidades e junto com os dados do médico e credenciais do sistema. O paciente pode navegar no site do sistema de consulta médica para encontrar um médico que tenha a especialidade de sua necessidade. Os pacientes podem revisar a agenda semanal do médico, permitindo-lhes selecionar o dia e horário adequados para a consulta. Posteriormente, eles podem enviar seu pedido de nomeação. Depois disso, os médicos poderão visualizar todas as suas consultas e a solicitação de consulta dos pacientes quanto à sua disponibilidade.

## Características

### Administrador
  
- O administrador pode adicionar médicos, editar médicos, excluir médicos
- Agende novas sessões médicas, remova sessões
- Ver detalhes dos pacientes
- Ver reserva de pacientes
    
    
 
 
### Médicos

- Veja seu compromisso
- Veja suas sessões agendadas
- Ver detalhes dos pacientes
- Deletar conta
- Editar configurações da conta
    

    
### Pacientes (Clientes)
  
  - Marcar consulta on-line
  - Crie contas você mesmo
  - Veja sua reserva antiga
  - Deletar conta
  - Editar configurações da conta

    
| Painel de administração |    Painel do médico    | Painel do Paciente |
| -------| -------| -------|
| Email: `admin@edoc.com` | Email:`doctor@edoc.com`|  Email: `patient@edoc.com` | 
| Password: `123`         |  Password: `123`       |  Password: `123` |


 
  
-----------------------------------------------


# INICIAR

1. Abra o Painel de Controle do XAMPP e inicie o Apache e o MySQL.
2. Extraia o arquivo zip do código-fonte baixado.
3. Copie a pasta do código-fonte extraído e cole-a no diretório “htdocs” do XAMPP.
4. Navegue no PHPMyAdmin em um navegador. ou seja, http://localhost/phpmyadmin
5. Crie um novo banco de dados denominado `edoc`.
6. Importe o arquivo SQL fornecido. O arquivo é conhecido como DATABASE edoc.sql localizado dentro da pasta raiz do código-fonte.
7. Navegue pelo Sistema de Consultas Médicas em um navegador. ou seja, http://localhost/edoc-echanneling-main/.




# O Projeto foi desenvolvido utilizando o seguinte:

Versão do Apache: `2.4.39`

Versão do PHP: `7.3.5`

Software de servidor: `Apache/2.4.39 (Win64) PHP/7.3.5`

Versão do MySQL: `5.7.26`





