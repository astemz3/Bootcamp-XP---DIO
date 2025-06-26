Cloud com Inteligência Artificial

Bootcamp XP - DIO

💻 Criando uma Máquina Virtual no Microsoft Azure
Este repositório contém minhas anotações, resumos e dicas sobre como criar uma máquina virtual (VM) no Microsoft Azure. 
Esse material serve como apoio para meus estudos e para consultar no futuro sempre que eu precisar repetir o processo.

🌐 O que é o Microsoft Azure?
O Microsoft Azure é uma plataforma de computação em nuvem da Microsoft. 
Com ela, podemos criar e usar serviços como servidores, bancos de dados,
inteligência artificial e muito mais, tudo pela internet.

⚙️ Passo a passo para criar uma máquina virtual no Azure:

1. Criar uma conta no Azure
   
    Acesse: https://azure.microsoft.com

    Clique em Comece gratuitamente.

⚙️ Preencha seus dados e finalize o cadastro.

2. Acessar o portal do Azure
   
    Vá para https://portal.azure.com

    Faça login com sua conta.

4. Criar uma nova máquina virtual (VM)
   
    No menu à esquerda, clique em Máquinas Virtuais.

    Clique em + Criar > Máquina virtual.

⚙️ Preencha as informações básicas:

    Nome da VM: vm-teste
    Região: Brasil Sul (ou a mais próxima de você)
    Sistema operacional: Ubuntu ou Windows, conforme sua preferência
    Tamanho da VM: escolha uma opção gratuita ou de baixo custo, como B1s
    Usuário e senha: crie um nome de usuário e uma senha segura

4. Configurações finais
   
    Nas abas seguintes, pode manter as opções padrão.

    Clique em Revisar + Criar

    Depois, clique em Criar

6. Acessar sua VM
   
    Após a criação, vá até a VM na sua lista.

    Copie o IP público.

    Use um programa como PuTTY (Windows) ou o terminal (Linux/Mac) para se conectar via SSH:

💡 Dicas e Anotações

    ⚠️ Importante: Ao terminar seus testes, desligue a VM para evitar cobranças.
    
    👨‍💻 O Azure tem uma interface amigável, mas muitos menus podem confundir no começo. Vá com calma e siga os tutoriais.
    
    🔒 Use senhas fortes e evite deixar sua VM exposta sem proteção.
    
    📌 Você pode alterar o tamanho da VM ou sistema operacional depois, mas algumas alterações exigem recriar a máquina.
    
    🧪 Use a camada gratuita para aprender sem custos.

🧠 Conclusão

Criar uma máquina virtual no Azure foi uma experiência legal e útil. 
Com isso, aprendi mais sobre como funcionam servidores na nuvem e como acessar eles remotamente. Pretendo usar esse conhecimento em projetos futuros e continuar explorando os serviços do Azure.

📎 Referências

Documentação oficial do Azure

https://learn.microsoft.com/pt-br/azure/?product=popular

Tutorial rápido do Azure: Criar uma VM

https://learn.microsoft.com/pt-br/azure/virtual-machines/linux/quick-create-portal?tabs=ubuntu

