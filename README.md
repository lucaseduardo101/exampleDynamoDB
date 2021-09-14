dynamodb --endpoint-url http://localstack:4566 put-item --table-name tb_locadora
      --item '{"estudio": {"S": "Disney"},"titulo": {"S": "UP"},"diretor": {"S":"Fulano"},"pais": {"S": "EUA"},"idioma": {"S": "Ingles"},"genero": {"S": "Acao"}}'
      --item '{"estudio": {"S": "Disney"},"titulo": {"S": "Divertidamente"},"diretor": {"S":"Zé"},"pais": {"S": "EUA"},"idioma": {"S": "Ingles"},"genero": {"S": "Acao"}}'
