# SafeGuard
Sistema embarcado de monitoramento e alerta para prevenção de quedas em idosos, focado em detectar tentativa de levantar do leito sem autorização de forma automática garantindo a segurança do paciente. 

## Sobre o Projeto
Este é um projeto em desenvolvimento de um sistema embarcado voltado para tecnologia assistiva em lares de idosos. O objetivo principal é prevenir quedas e acidentes noturnos monitorando a evasão de leito, alertando a equipe de cuidadores de forma rápida e confiável.

## Como Funciona (Arquitetura Inicial)
O sistema utiliza sensores para identificar quando o idoso tenta se levantar da cama. Ao detectar essa ação de risco, um alerta é disparado diretamente para a sala dos funcionários.

Para garantir alta confiabilidade — mesmo em casos de queda de energia ou falha de dispositivos móveis —, o sistema conta com:
- **Monitoramento local:** Sensores infravermelhos e de presença no leito.
- **Alarme redundante:** Sinalização física (luzes e som) na sala dos funcionários, além de opções de desligamento via botão físico ou digital.

## Status do Desenvolvimento
**Fase de Prototipagem:** Atualmente, a equipe está testando a melhor lógica de detecção para evitar falsos positivos (avaliando variáveis como diminuição de peso no colchão vs. tempo de apoio na borda da cama).

## Componentes de Hardware Previstos
- Sensor de Força FSR
- Módulo Sensor Infravermelho de Obstáculo
- Microcontrolador Principal: Módulo ESP32
- Alarme Sonoro Sonalarme Buzzer Led
- Módulo Relé 1 Canal 10a 
- Carregador bateria portátil de 5V (Power Bank)
- Carregador de celular comum (5V / USB) e um cabo  
- Cabos
- Resistores 