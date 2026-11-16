# ☁️ Resumo do Lab — Computação em Nuvem: Primeiro contato com o Portal do Azure

Resumo da aula **"7 Computação em nuvem – Laboratório"** da [DIO](https://www.dio.me/), parte do módulo preparatório para a certificação **AZ-900 (Microsoft Azure Fundamentals)**.

🎥 Vídeo: <https://youtu.be/O2oxmUaJ94o> (≈10 min)

---

## 🎯 Objetivo do lab

Fazer um **overview do Portal do Microsoft Azure**: personalizar a interface, navegar pelo catálogo de serviços e relacionar o que aparece no portal com os conceitos vistos nas aulas teóricas (computação, redes e armazenamento).

> ⚠️ **Pré-requisito:** ter uma conta gratuita do Azure (período de avaliação de 30 dias com créditos). A criação da conta é explicada no vídeo introdutório do módulo.

---

## 1. O portal é o mesmo para todo mundo

- O portal da conta gratuita é **visualmente igual** ao de uma grande empresa.
- Diferença: a conta **trial** pode ser **bloqueada para criar alguns recursos** (por custo alto) ou em **algumas regiões**.
- Isso é limitação de **disponibilidade do serviço**, não erro seu.

---

## 2. Personalizando o portal

Acesso: ícone de **engrenagem ⚙️** no canto superior direito, após o login.

| Opção | O que muda |
|---|---|
| **Idioma e região** | Idioma da interface (português, inglês etc.) |
| **Aparência + exibições de inicialização** | Menu encaixado ou flutuante, tema/cores do portal |

Dica: teste à vontade. Se não gostar, é só voltar a configuração.

---

## 3. Explorando "Todos os serviços"

O botão **Todos os serviços** lista tudo o que existe no Azure, **organizado por categorias**:

- IA + Machine Learning
- Análise
- Computação
- Contêineres
- Bancos de dados
- DevOps
- Híbrido + multinuvem
- …e várias outras

### 💻 Computação

- Área de Trabalho Virtual do Azure (Azure Virtual Desktop)
- Chaves SSH
- Conjuntos de disponibilidade
- Contas de laboratório
- Imagens, **máquinas virtuais** e discos
- Serviços já categorizados como **PaaS** (Plataforma como Serviço)

### 🌐 Redes

- **Azure Bastion** ("Bastião" na documentação em PT): acesso seguro às máquinas. Funciona como um **jump server** — um servidor usado como ponte para conectar em outras máquinas.
- Endereços IP públicos
- Gateways
- Zonas de DNS
- ExpressRoute
- Firewall
- **Peering** (emparelhamento de rede virtual)
- Load balancer (balanceamento de carga)

> 💡 A nuvem é, na prática, o ambiente **on-premises virtualizado**. Os nomes mudam, mas os conceitos continuam lá.

> 🔒 **Estar na nuvem não significa estar seguro.** A configuração de segurança dos recursos é responsabilidade de quem cria.

### 🗄️ Armazenamento

- Servidores, discos e **migração**.
- Ponto de atenção: migrar **terabytes** de uma empresa só pela internet é inviável. O Azure tem **estratégias específicas** para grandes volumes de dados.

---

## 4. ⚠️ Recursos em "Versão prévia" (Preview)

Alguns serviços aparecem marcados como **versão prévia**.

- O serviço **está começando a ser disponibilizado** e ainda está em avaliação.
- A Microsoft **pode descontinuá-lo** se não for aprovado.
- **Não tem SLA** (*Service Level Agreement* — acordo de nível de serviço, ou seja, a garantia).
- Se você usar em **produção** e tudo cair, **não há a quem reclamar**: foi por sua conta e risco.

✅ **Regra prática:** não use recursos em versão prévia em ambientes de produção.

---

## 5. Por que isso importa

Computação em nuvem **já é o presente** em todas as áreas de TI: desenvolvimento, inteligência artificial, banco de dados, infraestrutura. A AZ-900 é introdutória, mas dá a base para os próximos passos na carreira.

---

## 📚 Glossário rápido

| Termo | Significado |
|---|---|
| **AZ-900** | Certificação Microsoft Azure Fundamentals |
| **Trial** | Conta de avaliação gratuita (30 dias + créditos) |
| **PaaS** | Plataforma como Serviço |
| **Jump server** | Servidor-ponte para acessar outras máquinas |
| **Bastion** | Serviço do Azure que faz o papel de jump server |
| **Peering** | Emparelhamento entre redes virtuais |
| **SLA** | Acordo de nível de serviço (garantia de disponibilidade) |
| **Preview** | Recurso em versão prévia, sem SLA |

---

## ✅ Checklist do lab

- [ ] Criar a conta gratuita do Azure
- [ ] Trocar o idioma do portal
- [ ] Ajustar a aparência (menu e tema)
- [ ] Abrir **Todos os serviços** e navegar pelas categorias Computação, Redes e Armazenamento
- [ ] Identificar ao menos um serviço em **versão prévia**
