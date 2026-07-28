# Criptografia XOR em Python

Sistema simples de criptografia e descriptografia de mensagens em Python, utilizando cifra **XOR** com uma chave simétrica gerada aleatoriamente.

Projeto desenvolvido para a matéria de Introdução à Programação Estruturada (IPE).

## Como funciona

1. O programa gera automaticamente uma **chave aleatória de 1024 caracteres**, combinando letras maiúsculas, minúsculas, números e caracteres especiais.
2. O usuário define uma **senha** e digita a **mensagem** que deseja proteger.
3. A mensagem é criptografada aplicando a operação **XOR** entre cada caractere da mensagem e da chave.
4. Para recuperar a mensagem original, o usuário precisa informar a senha correta.
5. Caso a senha esteja incorreta, o sistema não revela o conteúdo.

## Requisitos

- Python 3.x

## Como executar

```bash
python criptografia.py
```

O terminal vai pedir:
- A senha desejada
- A mensagem secreta a ser criptografada

Em seguida, o programa exibe a mensagem criptografada e pede a senha novamente para descriptografá-la.

## Exemplo

```
Digite a senha desejada para dar continuidade a criptografia: 1234
Digite a mensagem secreta: Olá, Pessoal

Mensagem criptografada: (S↓tB<↔☻#9M↑

Digite a senha: 1234
Mensagem descriptografada:
Olá, Pessoal
```

## Observações

- A chave é gerada de forma aleatória a cada execução, portanto não é reutilizável entre sessões diferentes.
- O sistema permite apenas **uma tentativa** de senha para a descriptografia, como medida de segurança.
- Este é um projeto acadêmico com fins didáticos, não recomendado para proteger dados sensíveis em produção.

## Autor

Danilo Bortoletto
