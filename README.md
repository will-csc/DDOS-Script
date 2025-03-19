# DDOS Script
Este projeto tem o objetivo de **simular um ataque DDOS** a um endereço IP, útil para **testes de carga e estudo de redes**. O código cria várias **threads** que estabelecem conexões com um host-alvo e enviam requisições simples.

![image](https://github.com/user-attachments/assets/ff481b21-d066-48fb-8144-6b5616009db8)


⚠️ **Aviso**: Este script deve ser usado **somente para fins educacionais e testes autorizados**. Executá-lo sem permissão contra servidores de terceiros pode violar **leis de segurança cibernética**.

---

## 🚀 Como funciona

1. Cria **500 threads**, cada uma estabelecendo uma conexão com o servidor-alvo.
2. Envia pacotes de requisição via **socket**.
3. Exibe um contador de conexões bem-sucedidas a cada **500 tentativas**.

---

## 🛠️ Como usar

1. **Configure o alvo**
   - No código, substitua `"ip p/ ataque"` pelo **endereço IP ou domínio do servidor que você deseja testar**.
   - Defina `port` para a porta do serviço que será testado (padrão: 80 para HTTP).

2. **Configure seu IP** *(Opcional)*
   - `"seu ip (ocultado)"` pode ser usado para identificar sua própria máquina na comunicação.

3. **Execute o código**
   ```bash
   python main.py
   ```
---

## Uso Responsável

Esse script não deve ser usado para sobrecarregar servidores sem autorização.
Use apenas para testes internos, aprendizado ou ambientes autorizados.
Para testes legítimos, ferramentas como Apache JMeter ou locust.io são mais adequadas.
